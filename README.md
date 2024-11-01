# LangChain - Develop LLM powered applications with LangChain
## LLM ReActAgents - Diving Deep into ReAct Agents

### This Application count the no of characters in the string using Large Language Models

### Application Logs

Hello ReAct LangChain!
***Prompt to LLM was:***
Human: 
    Answer the following questions as best you can. You have access to the following tools:

    get_text_length(text: str) -> int - Returns the length of a text by characters

    Use the following format:

    Question: the input question you must answer
    Thought: you should always think about what to do
    Action: the action to take, should be one of [get_text_length]
    Action Input: the input to the action
    Observation: the result of the action
    ... (this Thought/Action/Action Input/Observation can repeat N times)
    Thought: I now know the final answer
    Final Answer: the final answer to the original input question

    Begin!

    Question: What is the length of the word: DOG
    Thought: 
    
**********
***LLM Response:***
I should use the get_text_length function to determine the length of the word "DOG".
    Action: get_text_length
    Action Input: "DOG"
    
**********
tool='get_text_length' tool_input='DOG"\n' log='I should use the get_text_length function to determine the length of the word "DOG".\n    Action: get_text_length\n    Action Input: "DOG"\n    '
get_text_length enter with text='DOG"\n'
observation=3
***Prompt to LLM was:***
Human: 
    Answer the following questions as best you can. You have access to the following tools:

    get_text_length(text: str) -> int - Returns the length of a text by characters

    Use the following format:

    Question: the input question you must answer
    Thought: you should always think about what to do
    Action: the action to take, should be one of [get_text_length]
    Action Input: the input to the action
    Observation: the result of the action
    ... (this Thought/Action/Action Input/Observation can repeat N times)
    Thought: I now know the final answer
    Final Answer: the final answer to the original input question

    Begin!

    Question: What is the length of the word: DOG
    Thought: I should use the get_text_length function to determine the length of the word "DOG".
    Action: get_text_length
    Action Input: "DOG"
    
Observation: 3
Thought: 
    
**********
***LLM Response:***
I now know the final answer
Final Answer: 3
**********
return_values={'output': '3'} log='I now know the final answer\nFinal Answer: 3'
### AgentFinish ###
{'output': '3'}


### Steps to run the application

1. Install Python=3.13.
2. Install Pycharm
3. Clone the repository
4. Generate a separate interpretor by following these steps
     1. Open Interpretor in Preferences
     2. Add Local Interpretor using this image ![image](https://github.com/user-attachments/assets/c65b6f06-66a0-4d12-87a8-5bbc557c7665)
     3. Click on Pipenv Environment
     4. Add Base Interpretor (Python path where its installed by using "which python3" on terminal)
     5. Add Pipenv executable (Python path where its installed by using "which pipenv" on terminal)
     6. See this screenshot for Step 4.4 and 4.5 ![image](https://github.com/user-attachments/assets/4981800a-0c55-4307-ab69-220f0f312355)
5. Generate .env file and store API Keys as in image ![image](https://github.com/user-attachments/assets/015a2746-d1a6-4365-b1ef-d874aad0d7af)
6. KEY DETAILS:
     1. OPENAI_API_KEY (CHATGPT Model)
     2. PROXYCURL_API_KEY (Accessing LinkedIn Profiles)
     3. TAVILY_API_KEY (Search Engine API developed for search in LLM)
     4. LANCHAIN_X (Debugging Using LangSmith)
8. Start "pipenv shell" environment in terminal (Make sure you're in working directory) ![image](https://github.com/user-attachments/assets/09759085-e140-4197-9819-af3a32168510)
9. Run the application in pycharm.

** This is a test applications. Errors and Ommissions are accepted ** 
** Developed & Tested this LangChain basic application in macOS **

*** In case of any errors, contact at "haseebahmed02@gmail.com" or Whatsapp "+447949067041". Will debug the application at your end and let it run ***

Thanks for your visit to my profile.

