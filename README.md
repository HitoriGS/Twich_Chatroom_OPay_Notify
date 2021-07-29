# 在 Twitch 聊天室顯示歐付寶訊息

修改自 https://github.com/frostiness520/Twich_Chatroom_OPay_Notify


## 使用方法

### 安裝

``` 
git clone https://github.com/HitoriGS/Twich_Chatroom_OPay_Notify
```

### 進入資料夾
```
cd Twich_Chatroom_OPay_Notify
```

### 安裝套件
```
npm install
```

1. 先到[Twitch tmi](https://twitchapps.com/tmi/)取得聊天室金鑰(oath)
2. 再到歐付寶Donate取得 https://payment.opay.tw/Broadcaster/Donate/xxxxxxx 中的 xxxxxxx(歐付寶ID)
![](https://i.imgur.com/CiV8FNb.jpg)

### 修改 config.json

```
"username" : "你的Twitch ID",
"oath" : "oath:輸入取得的聊天室金鑰",
"channel" : "#頻道名稱",
"OPayKey" : "歐付寶ID",
"modName" : "你的Twitch ID",
"testCommand" : "!testCommand",
"streamLabsToken" : "streamLabsToken"
```

### 執行程式
```
node bot.js
```
