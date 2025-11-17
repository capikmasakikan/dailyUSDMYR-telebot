# dailyUSDMYR-telebot
make a telegram bot that send daily price of USD-MYR

using n8n and several API
I created a telegram bot and used it as a daily publisher for price of USD-MYR

I posted the n8n node workflow:
1) start with schedule trigger node (set it to daily 12pm)
2) HTTP request node (obtain the api and using GET method)
3) Send message via Telegram (connect with telegram API and make a bot called USDMYR)

Tested the workflow and it ran smoothly:
Everyday on 12pm, it will automately post the price of USD-MYR inside the telegram group (see in the output.png)
