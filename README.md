# splat-bot

Basic responder for common questions and problems in the channels that SPLAT helps moderate.

## Building
~~~
podman build .
~~~

## Running
~~~
./slack-bot  --slack-token-path creds/bot-token --slack-signing-secret-path creds/signing-secret 
~~~
