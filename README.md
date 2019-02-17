# line-bot-nodejs-starter
starter point to create new line bot project

## How it work
Start express server to handle webhook from LINE

# Install
Clone and run
```
npm install
```
Modify `config.json`
```json
{
  "port" : "3000",
  "channelAccessToken": "5AqP8/7nEsFcZv4SRwtQ8t7Byv/hwZeT3UUrBZa4EA2bzP2bsE9EIk/vmcCv3jpVLk/QypO4XVyGmmasgvWNKAugE3IlkMOuUWQii1x39G4W9xUAF2QmVquR/KtSG7GMOfdPYdyqP414zQdGfiQd2QdB04t89/1O/w1cDnyilFU=",
  "channelSecret": "2e3fdbab4a41e9b0e6723ba1829d1463"
}
```
Run
```
npm start
```
then you can access [http://localhost:3000](http://localhost:3000)

Use [ngrok](https://ngrok.com/) to expose your local url
```
path/to/ngrok http 3000
```
config webhook url in developer console then enjoy your bot!

## Author
Sitthi Thiammekha
