Workshop: AI Agents for Network Automation

# Please complete as you seat in your seats:

## Task 1: Connect to dcloud.
Take a piece of paper from your table with your dcloud credentials. It will include: URL, username and password.
Use anyconnect o connect to the setup (use your credentials):

<img width="430" height="300" alt="Screenshot 2025-08-20 at 19 17 34" src="https://github.com/user-attachments/assets/4295ce84-7487-4c4e-a237-a6b1e57f801d" />

<img width="300" height="200" alt="Screenshot 2025-08-20 at 19 19 28" src="https://github.com/user-attachments/assets/cbe178a4-4da4-40ea-9bd6-b5a6fd16c9f9" />


## Task 2: Linux/MAC users  (Windows see below)::
  1- Open Terminal

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
  python3 -m streamlit run agent_main.p
  ```
  5- You can now view your Streamlit app in your browser.
 
  Local URL: http://localhost:8501

  6- In the Agent Settings to the left-hand side, select the LLM provider. Then enter the LLM you will use (gpt-4.1) and press Enter. Keep all other settings at their default values and select 
Click to Activate and verify AI agent readiness. You should see three validations in green color, meaning that your AI agent is ready to be used. See picture below for reference:  

<img width="3832" height="2098" alt="Screenshot 2025-08-19 at 19 02 35" src="https://github.com/user-attachments/assets/68720d49-eb87-4cc0-bd5e-8265215410fe" />


## Windows users:
  1- Open Power Shell as an Adminstrator

  2- Go to your ai-agent-playground folder:
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
