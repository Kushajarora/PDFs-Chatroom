# PDFs Chatroom

PDFs chatroom is an application for the 
## Installation
Download the repository 
git clone https://github.com/Kushajarora/PDFs-Chatroom.git


```bash
git clone https://github.com/Kushajarora/PDFs-Chatroom.git
```

## Installing Dependencies:
Navigate to the application's directory in your terminal or command prompt.

Run the following command to install the required dependencies using pip:


```bash
pip install -r requirements.txt
```

## Create a .env File:
In the application's directory, create a .env file to securely store sensitive information, such as your OPEN_AI API KEY.
```bash
touch .env
```
The .env file will be used to store environment variables, ensuring that your API key is kept confidential.

Store Your OPEN_AI API KEY in .env:

Open the .env file using a text editor of your choice.

Add the following line to store your OPEN_AI API KEY as an environment variable:

makefile
```bash
OPENAI_API_KEY=your_api_key_here
```
Replace your_api_key_here with your actual OPEN_AI API KEY.

## Run the Application:
After successfully creating the .env file and storing your API key, you can start the PDFs Chatroom application.

Run the application using the command
```bash
streamlit run app.py
```

Enjoy!!!!
