# Kleros slack invite automation

A tiny web application to invite a user into Kleros team.

## Installation

Go to https://api.slack.com/custom-integrations/legacy-tokens to get the token.

Set `process.env.SLACK_TOKEN` with the slack token.

```
export PORT=80
export SLACK_TOKEN=token_value
npm i
nohup npm start &
```
