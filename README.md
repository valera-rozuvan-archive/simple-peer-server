# simple-peer-server

## wip has moved

Future work on this repository has moved to the monorepo [valera-rozuvan/experiments](https://github.com/valera-rozuvan/experiments). This repo is archived for historic purposes (to preserve commit history). Navigate over to [experiments/simple-peer-server](https://github.com/valera-rozuvan/experiments/tree/main/simple-peer-server) to see updates (if any).

## introduction

simple-peer-server

To generate `server.key` and `server.crt`, use the command:

```
openssl req -x509 -sha256 -nodes -days 365 -newkey rsa:2048 -keyout server.key -out server.crt
```

Or more thorough case - see
[How to generate self-signed certificate for usage in Express4 or Node.js HTTP](https://matoski.com/article/node-express-generate-ssl/).
