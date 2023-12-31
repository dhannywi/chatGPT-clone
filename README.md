# chatGPT Clone

<img src='./django_chatbot/images/ChatGPT.webp'>

A ChatGPT clone created using Django with OpenAI API integration. Current iteration of the project focuses on the backend framework and OpenAI API intergration. The front-end component is under active development to improve the look and feel of the UI design.

## Installation
Ensure that you have `Python 3.11.4` or higher installed, as well as the latest version of `pip` and `pipenv`.
OpenAI API token is needed to run this project. You can get it at: https://platform.openai.com
* `git clone https://github.com/dhannywi/chatGPT-clone.git` to clone repository
* `pipenv shell` to activate a virtual environment with requirements installed
*  Create a `.env` file inside `chatbot` folder and insert your OpenAI API token in this format: `OPENAI_API_KEY=XXX`. Replace `XXX` with the API token generated for you by OpenAI

## Running the app
Once the virtual environment is activated, we can run the app.
* From the root directory of the app: `cd django_chatbot`
* `python3 manage.py runserver`
A local server of the app is now available for access at `http://127.0.0.1:8000/`

## Features & Endpoints
| Route | Feature |
|------ | ------- |
| / | Homepage |
| /chat | Chatbot page, requires user login |
| /login | User login page |
| /register | User registration page for new users |
| /logout | Logs user out |
| /admin | Admin users can login to access user information and chat history of each user |

## Future work
I am currently working on implementing the front-end for the app so that it resemble chatGPT.