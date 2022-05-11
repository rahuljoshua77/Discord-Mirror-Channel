# Discord-Mirror-Channel
A Tool chat can Mirror channel to channel

Once the Bot.json file is configured in the config folder, we will proceed to install the missing libraries to start the program.

- It is necessary to have Nodejs already installed

1. In the folder where we unzipped the .zip file we will open a cmd
2. 
 ![image](https://user-images.githubusercontent.com/73378179/167898769-d9799bc3-5dce-4d41-abdc-e285efbbfe16.png)

1.1 Type cmd

2. In cmd type the command: npm install
2.1. This command is only executed once, because it is only to install the missing libraries

3. Now type the command: node main.js
3.1. This command is executed every time you want to start the program

 
Explanation of variables:

"token": ""
- The token for your discord account, I have already mentioned before how to get the token

"info": false
- There are only two exact values: true or false
- This causes the messages to be sent with the icon and the original name of the person who sent them, in case you do not want to show this information leave it false.

"channels": {}
"Channel ID": "Webhook URL"
The channel id is where the messages come from


• Here is an example of the Bot.json file
• Remember that these values are filled in with the information previously sent.
