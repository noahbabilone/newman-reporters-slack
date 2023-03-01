# newman-reporters-slack

Custom [Newman](https://github.com/postmanlabs/newman) reporter to send message to [Slack](https://slack.com/)

<img src="https://github.com/noahbabilone/newman-reporters-slack/blob/master/testResults.png?raw=true" width="450"  height="550">

## Before you get started
- Install [Newman](https://github.com/postmanlabs/newman) ``` $ npm run i -g newman ```
- Create a [Slack incoming webhook url](https://api.slack.com/messaging/webhooks)
or
- Create a [Slack bot to send to channel or user dynamically](https://api.slack.com/messaging/sending)

## Installation
 ```CLI
 npm i -g newman-reporter-slackmsg
 ```

## Usage
```CLI
 newman run <collectionFile> -e <environmentFile> --suppress-exit-code -r slackmsg --reporter-slackmsg-webhookurl '<webhookurl>'
```
