# Anonymous Chat Bot

This is a Python-based Telegram bot project designed for anonymous chatting. The bot facilitates interactions between users while maintaining their anonymity, and it includes options for selecting users by gender or randomly.

## Features
- **Anonymous Chat:** Users can initiate chats with anonymity.
- **Gender Selection:** Allows users to choose to chat with a male, female, or random user.
- **Message Handling:** Efficiently relays messages between users until they end the chat.
- **User Data Management:** User information is securely stored in a database for better management.

## Files in the Project
- **main.py:** Main script to run the Telegram bot.
- **app.py:** Manages bot operations and interactions.
- **telegram_users.db:** SQLite database for storing user data.

## Getting Started
1. Clone the repository.
2. Ensure you have Python and required libraries installed.
3. Run the bot with the command:
   ```bash
   python main.py