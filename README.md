# Ember-cli-slack-chat-node-server

This is a simple node.js server component to go with [Ember-cli-slack-chat](https://github.com/fiddler/ember-cli-slack-chat).

## Installation

* You have to setup a Slack API key to access the API. You can do that at [https://api.slack.com/web](https://api.slack.com/web)
* Setup the API key as a Environment variable named SLACK_API_TOKEN or set it up in the server.js.
* Point your Ember-cli-slack-chat to the the server.

## Considerations

This is just a quick example and allows any origin for requests, so edit to your needs.


## Running
1. git clone git@github.com:snap-fnb/ember-cli-slack-chat-node-server.git
2. cd ember-cli-slack-chat-node-server
3. npm install
4. . setSlackApiToken.sh (setSlackApiToken.sh is not in git, see Matt)
5. node server.js

