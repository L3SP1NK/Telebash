# Telebash

Bash script to send messages on telegram with bot.

You don't have a bot yet? It's super easy:

1). Create one directly on Telegram with @botfather.

2). Add your bot to the group you want to talk to.

3). Get your group ID using: curl -s "https://api.telegram.org/bot<bot key>/getUpdates" (If it doesn't work, you may need to remove then re-add your bot to the group).

4). Create a telegram_token.txt file inside the "config" directory with: TELEGRAM_TOKEN="<your token>".

5). Create a telegram_group-id.txt file inside the "config" directory with: GROUP_ID="<your token>".

Information on the Telegram API here -> https://core.telegram.org/bots/api

Highly inspired by -> https://www.youtube.com/watch?v=RD8ALJ4Zrz8 (FR)
