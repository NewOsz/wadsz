# Telegram Auto Forward Bot

A powerful Telegram bot for managing and automating message forwarding across groups and channels. This bot offers multiple features, such as whitelist management, manual and auto-forwarding, and a user-friendly interface, all designed to make your Telegram experience seamless.

## Features

### 1. **Group & Channel Management**

- View the list of connected groups and channels, including their ID and username.
- Only displays groups and channels where the bot is a member, ensuring accurate visibility of your managed groups.

### 2. **Whitelist Management**

- Add and manage group/channel IDs to a whitelist, allowing only approved content to be forwarded.
- Easily remove IDs from the whitelist using an inline keyboard for smooth interactions.
- Ensures only authorized groups and channels can receive forwarded messages.

### 3. **Auto-Forward Feature**

- Set a time interval (in minutes) to automatically forward messages to all whitelisted IDs.
- Specify which message should be forwarded automatically.
- Includes support for customizable delay between forwards to avoid hitting rate limits.
- Ability to disable auto-forward while retaining message and interval settings.

### 4. **Manual Forwarding**

- Forward messages manually to all whitelisted IDs.
- Real-time progress bar and statistics (success/failure) to track the status of the forwarded messages.
- Provides granular control over the forwarding process.

### 5. **Security & Reliability**

- Implements a whitelist system, ensuring that only authorized users can control the bot.
- Robust error handling ensures stability and prevents interruptions in the bot’s operation.
- Saves configuration and data to files, allowing the bot to persist even when it is stopped or restarted.

### 6. **Intuitive User Interface**

- Uses easy-to-remember commands that make interacting with the bot simple.
- Provides clear and detailed feedback for each user action.
- Access a full guide by typing `/start` to help users get familiar with all available features.
