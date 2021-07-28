**Discord 掃毒機器人**
用VirusTotal掃描DC伺服器中的網址及檔案


第一次執行的時候會產生錯誤並創建一個叫做config.json的檔案，用你的discord bot token及你的VirusTotal Api Token把他填好再次執行
可以去settings.py(Cogs/settings.py)設定停止對其他Bot或特定文件類型檢查

```
# VirusTotalDiscordBot
Simple Discord Bot that scans messages in Servers for urls and files and checks them with virus total

Why this instead of the one already hosted? Many people want to know who gets their files and can read their messages or want to change parts of the code. So i quickly wrote this bot in python, which allows it to be integrated into most other bots as well



It is still in alpha and im working on it


If you want to use it i suggest running it in a docker container


On first loading it will throw an error after creating a config.json file, fill it with you discord bot token and your VirusTotal Api Token, then reload the bot
There is a different file names settings.py(Cogs/settings.py) where you can disable checks on other bots
or specific file types

Now the bot should send warnings on servers where urls, files and domains get posted and should test them
```
