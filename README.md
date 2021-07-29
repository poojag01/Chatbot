# Chatbot

## Conversational AI Test Automation

# Objective – To create an application that can automatically match and validate flows of a given bot.
# Current challenge is that the response of bot varies as the output template values may differ over
# period of time. i.e.
USER – Hi
BOT – Good Morning
USER – Price of Baleno
BOT – THE price of baleno is {XXXX} rs.
Here the {XXXX} can change at any point of time and thus a simple string match wont suffice.

## Input - CSV

• Session ID – Unique ID for a conversation
• Date Time – Date time
• Input Query - Query Made by User
• Output Query – The query made by bot
• Expected Query – The query that is actually expected.

## Output – CSV
All the columns of Input Query with addition of
• Success – Pass / Fail

All conversations between a bot and user is given a single unique ID (Session ID). The input CSV
should be able to validate multiple such conversation for any number of users.
