# discord-bot-mestre-supremo
Simple discord music bot wrote on Python and using discor.py and youtube-dl

## Main Requirements
Python3.x.x

## How to use
Create a folder to store this project. Open this folder on terminal and run the following commands

### 1. Clone the project
git clone https://github.com/rodrigoddc/polls-tutorial.git

### 2. Create a virtual environment
python3 -m venv venv

### 3. Activate the the virtual environment previously created
on linux: source ./venv/bin/activate
on windows: ./venv/Scripts/activate.bat

### 4. Installing libs
pip install -r requirements.txt

### 5. Create .env file to keep your tokens
touch .env
echo "DISCORD_TOKEN=your_discord_token" >> .env

### 5. Running
python bot.py
