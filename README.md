# NBA-API-project
## Overview:
This Python script facilitates the retrieval of NBA basketball game information from the ESPN API, processes the data, and then sends notifications to both a Telegram group and a WhatsApp group.

## How to Use:
### 1 - Install the required libraries:
pip install requests telepot
### 2 - Update API keys and group IDs in the script:
Telegram: Replace 'token' and 'chat_id' with your bot token and group chat ID.
WhatsApp: Replace 'apikey' and 'group' with your WhatsApp API key and group ID.
### 3 - Run the script:
python script_name.py

Functionality:
- Retrieves NBA game data from the ESPN API.
- Formats the data into a readable string.
- Sends the formatted data to a Telegram group using the Telepot library.
- Sends the formatted data to a WhatsApp group using the RapidAPI.
