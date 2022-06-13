# splat-bot

Basic responder for common questions and problems in the channels that SPLAT helps moderate.  This bot is derived from a [Slack bot in ci-tools](https://github.com/openshift/ci-tools/tree/master/cmd/slack-bot)

## Building
~~~
podman build .
~~~

## Running
~~~
./slack-bot  --slack-token-path creds/bot-token --slack-signing-secret-path creds/signing-secret 
~~~
