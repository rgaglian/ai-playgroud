# Workshop: AI Agents for Network Automation

Please complete as you seat in your seats. There are Three tasks in this instructions.

Note: Pre-requirement: All the pre-requirement work is listed here (VPN required): https://wwwin-github.cisco.com/jantich/ai-agent-playground/blob/master/docs/QUICKSTART.md

## Task 1: Update your code (we found some problems...):
### Note: If you used the ZIP instructions for creating your lab, please check alternative instructions at the end of the document.
  1- Connect to Cisco Corportate VPN
  
  2- Open a new Terminal or Power Shell

  3- Go to your ai-agent-playground folder:
  ```bash
   cd ai-agent-playground
  ```
  4- Perform the GIT Pull from the repository
  ```bash
    git pull
  ```
  You should have the following output or similar (depending of when you did your pre-work):
  ```
 ai-agent-playground % git pull
Enter passphrase for key '/Users/rogaglia/.ssh/id_rsa':
Updating 6a44ce6..e81aa21
Fast-forward
 agent/agent_core.py | 31 +++++++++++++++++++++++++++++--
 llm/llm_utils.py    | 23 +++++++++++++++++------
 2 files changed, 46 insertions(+), 8 deletions(-)
 ai-agent-playground %
  ```

  5- Disconnect from Cisco Corporate VPN

## Task 2: Connect to dcloud.
Take a piece of paper from your table with your dcloud credentials. It will include: URL, username and password.
Use anyconnect o connect to the setup (use your credentials):

<img width="430" height="300" alt="Screenshot 2025-08-20 at 19 17 34" src="https://github.com/user-attachments/assets/4295ce84-7487-4c4e-a237-a6b1e57f801d" />

<img width="300" height="200" alt="Screenshot 2025-08-20 at 19 19 28" src="https://github.com/user-attachments/assets/cbe178a4-4da4-40ea-9bd6-b5a6fd16c9f9" />

## Task 3: Activate your virtual environment and run playground
### Instructions Linux/MAC users  (Windows see below)::
  1- Open a new Terminal

  2- Go to your ai-agent-playground folder:
  ```bash
   cd ai-agent-playground
  ```
  3- Activate your virtual environment:
  ```bash
  source agent_workshop/bin/activate
  ```
  4- Run the application and connect to port 8501:
  ```bash
  python3 -m streamlit run agent_main.py
  ```
  5- You can now view your Streamlit app in your browser.
 
  Local URL: http://localhost:8501

  6- In the Agent Settings to the left-hand side, select the LLM provider. Then enter the LLM you will use (gpt-4.1) and press Enter. Keep all other settings at their default values and select 
Click to Activate and verify AI agent readiness. You should see three validations in green color, meaning that your AI agent is ready to be used. See picture below for reference:  

<img width="3832" height="2098" alt="Screenshot 2025-08-19 at 19 02 35" src="https://github.com/user-attachments/assets/68720d49-eb87-4cc0-bd5e-8265215410fe" />


### Instructions Windows users:
  1- Open Power Shell as an Adminstrator

  2- Go to your ai-agent-playground folder if you are not already there:
  ```bash
   cd ai-agent-playground
  ```

  3- Activate your virtual environment:
  ```bash
  .\agent_workshop\Scripts\activate
  ```

  4- Run the application:
  ```bash
  python3 -m streamlit run agent_main.py
  ```

  5- You can now view your Streamlit app in your browser.
 
  Local URL: http://localhost:8501

  6- In the Agent Settings to the left-hand side, select the LLM provider. Then enter the LLM you will use (gpt-4.1) and press Enter. Keep all other settings at their default values and select 
Click to Activate and verify AI agent readiness. You should see three validations in green color, meaning that your AI agent is ready to be used. See picture below for reference:  

<img width="3832" height="2098" alt="Screenshot 2025-08-19 at 19 02 35" src="https://github.com/user-attachments/assets/68720d49-eb87-4cc0-bd5e-8265215410fe" />

### Task 1:Instructions for people using ZIP file to download environment:
In an initial version fo the instructions, we included the option to download ZIP files and locally run the environment. This is a challenge to perform some updates.

Here are the options:

1- Redo: 
  Copy your .env file somewhere you can re-use it later.
  
  Re-start the setup using the "git clone" option or downloading a new ZIP with the current version of the environment.
  You can use a new folder to host the new environment or delete the old folder.

  Re-use your .env file in the new folder, just to be sure you have the right encoding.

2- Update space:

  a- Download the new ZIP file from the Corporate git: https://wwwin-github.cisco.com/jantich/ai-agent-playground.git

  b- Unzip the new file in a different folder

  c- Overwrite all the files from the new folder into the old folder. 
  
  d- Just check that your .env file is still valid.
  
When done, you can continue to connect to the dcloud environment on Task 2.

