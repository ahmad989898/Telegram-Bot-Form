# Telegram-Bot-Form
Bot that retrieve data from Google Sheets and automatically update it in Telegram by the time the Google Form is submitted.


Step by step to make Telegram BOT that can retrieve data from Google Form and automatically update to Telegram

Create a Google Form:
-Begin by designing your Google Form to collect the desired data.

Create a Telegram Bot:
-Utilize BotFather in Telegram to generate your Telegram Bot.

Retrieve Bot Token:
-Obtain the Bot Token (API) from BotFather and securely store it.

Add "Raw Data Bot" to Telegram Group:
-Include "Raw Data Bot" in your Telegram group to acquire the Chat ID and save this information.

Review Google Form Responses:
-Examine the collected responses in your Google Sheet associated with the Google Form.

Access Apps Script:
-Open "Apps Script" through the "Extension" button in Google Sheets.

Paste GitHub Code:
-Paste the provided code from GitHub into the "Apps Script" editor.

Modify Code Parameters:
-Adjust the code, Token ID, Chat ID, and Form ID to match your specific data.

Save the Code:
-Save the modified code in the "Apps Script" editor.

Add Trigger:
-Integrate a trigger and select "onFormSubmit" to activate the script upon form submission.

Include Bot in Group:
-Add your Telegram Bot to the designated group.

Test and Enjoy:
-Execute a test of your code to ensure proper functionality and enjoy the automated data retrieval and updates.
