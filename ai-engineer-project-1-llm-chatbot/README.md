# AI ENGINEERING

## Project
The goal of this project is to buidl a functional command-line chatbot that manages conversation history and is aware of token limits and costs.

## Provider
In this project, I will be using Gemini API specifically gemini-2.5-flash model.

## Setup
The following are the steps to create and activate a virtual environment in python.

While in the root directory of your project, run the following commands:

Creating a virtual environment
`python -m venv venv-name`

Activating a virtual environment
### Windows 
`venv-name\Scripts\Activate`

### Linux/macOS
`source venv-name/bin/activate`

After following the above instructions, you should see `(venv)` at the beginning of your terminal prompt.
Once the virtual environment is active, install the dependencies. 

## Running Day 1
To run today's project, follow the instructions below.
`git clone <repo-url>`
`cd project-folder`

`python -m venv venv`

Activate the virtual enviornment, then run

`pip install -r requirements.txt`

Navigate to `ai-engineer-project-1-llm-chatbot/src/day_01`

Then run: `python3 day_01_hello_world.py`


## Troubleshooting
In case you encounter a problem, confirm if you added your gemini API key to the .env file in your root directory and that your virtual environment is activated.