# hubot-openshift-slack-bot

Intracts with OpenShift cli and fetch data.

See [`src/openshift-slack-bot.coffee`](src/openshift-slack-bot.coffee) for full documentation.

## Installation

In hubot project repo, run:

`npm install hubot-openshift-slack-bot --save`

Then add **hubot-openshift-slack-bot** to your `external-scripts.json`:

```json
[
  "hubot-openshift-slack-bot"
]
```

## Sample Interaction

```
user1>> oc get pods
hubot>> oc get logs
```

## NPM Module

https://www.npmjs.com/package/hubot-openshift-slack-bot