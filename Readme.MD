# Node Logging System
Built with;
- Fastify
- node-fetch
- middie

> To Run
```bash
$ NODE_ENV=development LOGSTASH=localhost:7777 \
  node web-api/consumer-http-logs.js
$ node recipe-api/producer-http-basic.js
$ brew install watch # required for macOS
$ watch -n5 curl http://localhost:3000
$ watch -n13 curl http://localhost:3000/error
```