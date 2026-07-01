# telegram-bot-autoresponder
A real-time Make.com automation blueprint that watches incoming Telegram bot updates and triggers instant text responses or replies.
# Telegram Bot Autoresponder Automation

This repository houses a Make.com (formerly Integromat) scenario blueprint that creates a real-time interaction loop for a Telegram Bot using webhooks.

## 🚀 How It Works
1. **Trigger (Telegram Bot - Watch Updates):** Listens instantly for any incoming messages, commands, or media updates sent by users directly to your bot.
2. **Action (Telegram Bot - Send a Text Message or a Reply):** Captures the sender data or user message context and immediately replies with a programmed text message or dynamic response string.

## 📦 What's Included
* `/blueprints/telegram-bot-autoresponder.json`: The complete exported Make.com scenario blueprint configuration file.

## 🔧 Setup Instructions
1. Open your **Make.com** dashboard.
2. Create a new scenario, click the three dots (`...`) located on the bottom navigation control panel, and choose **Import Blueprint**.
3. Upload the `.json` blueprint file from this repository.
4. Establish your bot credentials:
   * Generate an API Token by messaging Telegram's official `@BotFather`.
   * Open the **Watch Updates** module configuration and create a new connection using your token to initialize the webhook.
   * Ensure the second **Telegram Bot** module uses the same connection.
5. Map fields like `Chat ID` and `Message ID` dynamically to ensure replies go to the correct user or thread.
6. Save the configuration and flip the main scheduling toggle switch to **ON**.
