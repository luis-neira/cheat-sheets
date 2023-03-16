- Xlien API is on Master up-to-date
- Claims Specialist Interface up-to-date

```

> fastlane-payoff-api@10.4.0 docker:start
> ./bin/docker/start.sh


> Loading environment variables from '/Users/luisneira/Documents/code/lossexpress/xlien-api/.env'...


> Starting the application...

> fastlane-payoff-api@10.4.0 vanity
> node ./utilities/vanity.js



 ██╗       ██████╗  ███████╗ ███████╗ ███████╗ ██╗  ██╗ ██████╗  ██████╗  ███████╗ ███████╗ ███████╗      █████╗  ██████╗  ██╗
 ██║      ██╔═══██╗ ██╔════╝ ██╔════╝ ██╔════╝ ╚██╗██╔╝ ██╔══██╗ ██╔══██╗ ██╔════╝ ██╔════╝ ██╔════╝     ██╔══██╗ ██╔══██╗ ██║
 ██║      ██║   ██║ ███████╗ ███████╗ █████╗    ╚███╔╝  ██████╔╝ ██████╔╝ █████╗   ███████╗ ███████╗     ███████║ ██████╔╝ ██║
 ██║      ██║   ██║ ╚════██║ ╚════██║ ██╔══╝    ██╔██╗  ██╔═══╝  ██╔══██╗ ██╔══╝   ╚════██║ ╚════██║     ██╔══██║ ██╔═══╝  ██║
 ███████╗ ╚██████╔╝ ███████║ ███████║ ███████╗ ██╔╝ ██╗ ██║      ██║  ██║ ███████╗ ███████║ ███████║     ██║  ██║ ██║      ██║
 ╚══════╝  ╚═════╝  ╚══════╝ ╚══════╝ ╚══════╝ ╚═╝  ╚═╝ ╚═╝      ╚═╝  ╚═╝ ╚══════╝ ╚══════╝ ╚══════╝     ╚═╝  ╚═╝ ╚═╝      ╚═╝


no container to killGoing to remove xlien-api-payoff-1
[+] Running 1/0
 ⠿ Container xlien-api-payoff-1  Removed                                                                                                  0.0s
[+] Running 5/5
 ⠿ Container xlien-api-samlidp-1    Running                                                                                               0.0s
 ⠿ Container xlien-api-redis-1      Running                                                                                               0.0s
 ⠿ Container xlien-api-golismero-1  Started                                                                                               0.3s
 ⠿ Container xlien-api-payoffdb-1   Running                                                                                               0.0s
 ⠿ Container xlien-api-payoff-1     Started                                                                                               1.5s
xlien-api-payoff-1  | ===============================================================================
xlien-api-payoff-1  | --- PM2 development mode ------------------------------------------------------
xlien-api-payoff-1  | Apps started         : server
xlien-api-payoff-1  | Processes started    : 1
xlien-api-payoff-1  | Watch and Restart    : Enabled
xlien-api-payoff-1  | Ignored folder       : node_modules
xlien-api-payoff-1  | ===============================================================================
xlien-api-payoff-1  | [rundev] App server restarted
xlien-api-payoff-1  | server-0  | info: Server starting... {"service":"xLien"}
xlien-api-payoff-1  | server-0  | - Initializing server...
xlien-api-payoff-1  | server-0  | info: [plugins] undefined success! {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: [plugins] undefined success! {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: [plugins] undefined-auth-plugin success! {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: [plugins] awilix success! {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: [plugins] undefined-cookie-auth-plugin success! {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: [plugins] logging-plugin success! {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: [plugins] le-blipp success! {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: [plugins] undefined-saml-plugin success! {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: [plugins] fastlane-payoff-api-session-auth-plugin success! {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: [plugins] undefined-vendor-auth-plugin success! {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: [plugins] undefined-worker-cookie-auth-plugin success! {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: [plugins] undefined-grant-plugin success! {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: [plugins] le-hapi-pulse success! {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: [plugins] undefined-gcm-auth-plugin success! {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: [plugins] undefined-queue-ui success! {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: Registered plugins successfully. {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: Registered api successfully. {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: Finished registering all plugins and routes. {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: Loading document templates... {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: Finished loading document templates! {"service":"xLien"}
xlien-api-payoff-1  | server-0  | info: Total disk space available {"available":25471361024,"free":28688076800,"service":"xLien","total":62671097856}
xlien-api-payoff-1  | server-0  | ✔ Server initialized!
xlien-api-payoff-1  | server-0  | - Starting up ngrok...
xlien-api-payoff-1  | server-0  | ✔ ngrok started on: https://dev7.ngrok.lossexpress.com > PHONE: +12149494404
xlien-api-payoff-1  | server-0  | - Starting up Bee Queue Arena...
xlien-api-payoff-1  | server-0  | Arena is running on port 4567 at host 0.0.0.0
xlien-api-payoff-1  | server-0  | [1676016558658] INFO (24 on c7d4f1f85d3a): server started
xlien-api-payoff-1  | server-0  |     created: 1676016549237
xlien-api-payoff-1  | server-0  |     started: 1676016558657
xlien-api-payoff-1  | server-0  |     host: "0.0.0.0"
xlien-api-payoff-1  | server-0  |     port: 3000
xlien-api-payoff-1  | server-0  |     protocol: "http"
xlien-api-payoff-1  | server-0  |     id: "c7d4f1f85d3a:24:ldy8za0l"
xlien-api-payoff-1  | server-0  |     uri: "http://0.0.0.0:3000"
xlien-api-payoff-1  | server-0  |     address: "0.0.0.0"
xlien-api-payoff-1  | server-0  | [1676016583148] ERROR (24 on c7d4f1f85d3a):
xlien-api-payoff-1  | server-0  |     request: "1676016583144:c7d4f1f85d3a:24:ldy8za0l:10017"
xlien-api-payoff-1  | server-0  |     tags: [
xlien-api-payoff-1  | server-0  |       "auth",
xlien-api-payoff-1  | server-0  |       "unauthenticated",
xlien-api-payoff-1  | server-0  |       "error",
xlien-api-payoff-1  | server-0  |       "twilio"
xlien-api-payoff-1  | server-0  |     ]
xlien-api-payoff-1  | server-0  |     channel: "internal"
xlien-api-payoff-1  | server-0  |     req: {
xlien-api-payoff-1  | server-0  |       "id": "1676016583144:c7d4f1f85d3a:24:ldy8za0l:10017",
xlien-api-payoff-1  | server-0  |       "method": "post",
xlien-api-payoff-1  | server-0  |       "url": "/jobs/call/connect",
xlien-api-payoff-1  | server-0  |       "headers": {
xlien-api-payoff-1  | server-0  |         "host": "dev7.ngrok.lossexpress.com",
xlien-api-payoff-1  | server-0  |         "user-agent": "TwilioProxy/1.1",
xlien-api-payoff-1  | server-0  |         "content-length": "300",
xlien-api-payoff-1  | server-0  |         "content-type": "application/x-www-form-urlencoded; charset=UTF-8",
xlien-api-payoff-1  | server-0  |         "i-twilio-idempotency-token": "47f76123-732c-4d97-a9af-9a8978e78336",
xlien-api-payoff-1  | server-0  |         "x-forwarded-for": "35.174.168.70",
xlien-api-payoff-1  | server-0  |         "x-forwarded-proto": "http",
xlien-api-payoff-1  | server-0  |         "x-home-region": "us1",
xlien-api-payoff-1  | server-0  |         "x-twilio-signature": "IQToFtQYLBllHhk1kDeIKsR6F4U=",
xlien-api-payoff-1  | server-0  |         "accept-encoding": "gzip"
xlien-api-payoff-1  | server-0  |       },
xlien-api-payoff-1  | server-0  |       "remoteAddress": "127.0.0.1",
xlien-api-payoff-1  | server-0  |       "remotePort": 41698
xlien-api-payoff-1  | server-0  |     }
xlien-api-payoff-1  | server-0  |     error: {
xlien-api-payoff-1  | server-0  |       "data": null,
xlien-api-payoff-1  | server-0  |       "isBoom": true,
xlien-api-payoff-1  | server-0  |       "isServer": false,
xlien-api-payoff-1  | server-0  |       "output": {
xlien-api-payoff-1  | server-0  |         "statusCode": 401,
xlien-api-payoff-1  | server-0  |         "payload": {
xlien-api-payoff-1  | server-0  |           "statusCode": 401,
xlien-api-payoff-1  | server-0  |           "error": "Unauthorized",
xlien-api-payoff-1  | server-0  |           "message": "Invalid headers supplied"
xlien-api-payoff-1  | server-0  |         },
xlien-api-payoff-1  | server-0  |         "headers": {
xlien-api-payoff-1  | server-0  |           "WWW-Authenticate": "Basic realm=\"LossExpress\""
xlien-api-payoff-1  | server-0  |         }
xlien-api-payoff-1  | server-0  |       }
xlien-api-payoff-1  | server-0  |     }
xlien-api-payoff-1  | server-0  | [1676016584617] ERROR (24 on c7d4f1f85d3a):
xlien-api-payoff-1  | server-0  |     request: "1676016584615:c7d4f1f85d3a:24:ldy8za0l:10022"
xlien-api-payoff-1  | server-0  |     tags: [
xlien-api-payoff-1  | server-0  |       "auth",
xlien-api-payoff-1  | server-0  |       "unauthenticated",
xlien-api-payoff-1  | server-0  |       "error",
xlien-api-payoff-1  | server-0  |       "twilio"
xlien-api-payoff-1  | server-0  |     ]
xlien-api-payoff-1  | server-0  |     channel: "internal"
xlien-api-payoff-1  | server-0  |     req: {
xlien-api-payoff-1  | server-0  |       "id": "1676016584615:c7d4f1f85d3a:24:ldy8za0l:10022",
xlien-api-payoff-1  | server-0  |       "method": "post",
xlien-api-payoff-1  | server-0  |       "url": "/jobs/call/CA73e8de5b0985ea10416c61d588f289e7/status-update/6681f970-ae57-46c8-bd7a-795d833b2c03",
xlien-api-payoff-1  | server-0  |       "headers": {
xlien-api-payoff-1  | server-0  |         "host": "dev7.ngrok.lossexpress.com",
xlien-api-payoff-1  | server-0  |         "user-agent": "TwilioProxy/1.1",
xlien-api-payoff-1  | server-0  |         "content-length": "393",
xlien-api-payoff-1  | server-0  |         "accept": "*/*",
xlien-api-payoff-1  | server-0  |         "content-type": "application/x-www-form-urlencoded; charset=UTF-8",
xlien-api-payoff-1  | server-0  |         "i-twilio-idempotency-token": "a8a45194-5f9f-489b-b491-363bab76a9d9",
xlien-api-payoff-1  | server-0  |         "x-forwarded-for": "100.24.29.162",
xlien-api-payoff-1  | server-0  |         "x-forwarded-proto": "http",
xlien-api-payoff-1  | server-0  |         "x-home-region": "us1",
xlien-api-payoff-1  | server-0  |         "x-twilio-signature": "S3uWWWq7lU+6UPd3RKXscD7/jjc=",
xlien-api-payoff-1  | server-0  |         "accept-encoding": "gzip"
xlien-api-payoff-1  | server-0  |       },
xlien-api-payoff-1  | server-0  |       "remoteAddress": "127.0.0.1",
xlien-api-payoff-1  | server-0  |       "remotePort": 41718
xlien-api-payoff-1  | server-0  |     }
xlien-api-payoff-1  | server-0  |     error: {
xlien-api-payoff-1  | server-0  |       "data": null,
xlien-api-payoff-1  | server-0  |       "isBoom": true,
xlien-api-payoff-1  | server-0  |       "isServer": false,
xlien-api-payoff-1  | server-0  |       "output": {
xlien-api-payoff-1  | server-0  |         "statusCode": 401,
xlien-api-payoff-1  | server-0  |         "payload": {
xlien-api-payoff-1  | server-0  |           "statusCode": 401,
xlien-api-payoff-1  | server-0  |           "error": "Unauthorized",
xlien-api-payoff-1  | server-0  |           "message": "Invalid headers supplied"
xlien-api-payoff-1  | server-0  |         },
xlien-api-payoff-1  | server-0  |         "headers": {
xlien-api-payoff-1  | server-0  |           "WWW-Authenticate": "Basic realm=\"LossExpress\""
xlien-api-payoff-1  | server-0  |         }
xlien-api-payoff-1  | server-0  |       }
xlien-api-payoff-1  | server-0  |     }
xlien-api-payoff-1  | server-0  | [1676016598129] ERROR (24 on c7d4f1f85d3a):
xlien-api-payoff-1  | server-0  |     request: "1676016598128:c7d4f1f85d3a:24:ldy8za0l:10024"
xlien-api-payoff-1  | server-0  |     tags: [
xlien-api-payoff-1  | server-0  |       "auth",
xlien-api-payoff-1  | server-0  |       "unauthenticated",
xlien-api-payoff-1  | server-0  |       "error",
xlien-api-payoff-1  | server-0  |       "twilio"
xlien-api-payoff-1  | server-0  |     ]
xlien-api-payoff-1  | server-0  |     channel: "internal"
xlien-api-payoff-1  | server-0  |     req: {
xlien-api-payoff-1  | server-0  |       "id": "1676016598128:c7d4f1f85d3a:24:ldy8za0l:10024",
xlien-api-payoff-1  | server-0  |       "method": "post",
xlien-api-payoff-1  | server-0  |       "url": "/jobs/call/6681f970-ae57-46c8-bd7a-795d833b2c03/join-call",
xlien-api-payoff-1  | server-0  |       "headers": {
xlien-api-payoff-1  | server-0  |         "host": "dev7.ngrok.lossexpress.com",
xlien-api-payoff-1  | server-0  |         "user-agent": "TwilioProxy/1.1",
xlien-api-payoff-1  | server-0  |         "content-length": "542",
xlien-api-payoff-1  | server-0  |         "content-type": "application/x-www-form-urlencoded; charset=UTF-8",
xlien-api-payoff-1  | server-0  |         "i-twilio-idempotency-token": "f3c27731-1013-4dd5-aad1-0d1d021e71f7",
xlien-api-payoff-1  | server-0  |         "x-forwarded-for": "54.159.113.151",
xlien-api-payoff-1  | server-0  |         "x-forwarded-proto": "http",
xlien-api-payoff-1  | server-0  |         "x-home-region": "us1",
xlien-api-payoff-1  | server-0  |         "x-twilio-signature": "nklwgT4qd2plxS6+lJMjEEqWepI=",
xlien-api-payoff-1  | server-0  |         "accept-encoding": "gzip"
xlien-api-payoff-1  | server-0  |       },
xlien-api-payoff-1  | server-0  |       "remoteAddress": "127.0.0.1",
xlien-api-payoff-1  | server-0  |       "remotePort": 38866
xlien-api-payoff-1  | server-0  |     }
xlien-api-payoff-1  | server-0  |     error: {
xlien-api-payoff-1  | server-0  |       "data": null,
xlien-api-payoff-1  | server-0  |       "isBoom": true,
xlien-api-payoff-1  | server-0  |       "isServer": false,
xlien-api-payoff-1  | server-0  |       "output": {
xlien-api-payoff-1  | server-0  |         "statusCode": 401,
xlien-api-payoff-1  | server-0  |         "payload": {
xlien-api-payoff-1  | server-0  |           "statusCode": 401,
xlien-api-payoff-1  | server-0  |           "error": "Unauthorized",
xlien-api-payoff-1  | server-0  |           "message": "Invalid headers supplied"
xlien-api-payoff-1  | server-0  |         },
xlien-api-payoff-1  | server-0  |         "headers": {
xlien-api-payoff-1  | server-0  |           "WWW-Authenticate": "Basic realm=\"LossExpress\""
xlien-api-payoff-1  | server-0  |         }
xlien-api-payoff-1  | server-0  |       }
xlien-api-payoff-1  | server-0  |     }
xlien-api-payoff-1  | server-0  | [1676016598333] ERROR (24 on c7d4f1f85d3a):
xlien-api-payoff-1  | server-0  |     request: "1676016598332:c7d4f1f85d3a:24:ldy8za0l:10026"
xlien-api-payoff-1  | server-0  |     tags: [
xlien-api-payoff-1  | server-0  |       "auth",
xlien-api-payoff-1  | server-0  |       "unauthenticated",
xlien-api-payoff-1  | server-0  |       "error",
xlien-api-payoff-1  | server-0  |       "twilio"
xlien-api-payoff-1  | server-0  |     ]
xlien-api-payoff-1  | server-0  |     channel: "internal"
xlien-api-payoff-1  | server-0  |     req: {
xlien-api-payoff-1  | server-0  |       "id": "1676016598332:c7d4f1f85d3a:24:ldy8za0l:10026",
xlien-api-payoff-1  | server-0  |       "method": "post",
xlien-api-payoff-1  | server-0  |       "url": "/jobs/call/CA73e8de5b0985ea10416c61d588f289e7/status-update/6681f970-ae57-46c8-bd7a-795d833b2c03",
xlien-api-payoff-1  | server-0  |       "headers": {
xlien-api-payoff-1  | server-0  |         "host": "dev7.ngrok.lossexpress.com",
xlien-api-payoff-1  | server-0  |         "user-agent": "TwilioProxy/1.1",
xlien-api-payoff-1  | server-0  |         "content-length": "393",
xlien-api-payoff-1  | server-0  |         "accept": "*/*",
xlien-api-payoff-1  | server-0  |         "content-type": "application/x-www-form-urlencoded; charset=UTF-8",
xlien-api-payoff-1  | server-0  |         "i-twilio-idempotency-token": "802797ee-9edf-41f0-888f-8b6bdf38d6a4",
xlien-api-payoff-1  | server-0  |         "x-forwarded-for": "54.81.218.194",
xlien-api-payoff-1  | server-0  |         "x-forwarded-proto": "http",
xlien-api-payoff-1  | server-0  |         "x-home-region": "us1",
xlien-api-payoff-1  | server-0  |         "x-twilio-signature": "cVY8OzAWq9DHIaKD9QSFbM2y4/8=",
xlien-api-payoff-1  | server-0  |         "accept-encoding": "gzip"
xlien-api-payoff-1  | server-0  |       },
xlien-api-payoff-1  | server-0  |       "remoteAddress": "127.0.0.1",
xlien-api-payoff-1  | server-0  |       "remotePort": 38898
xlien-api-payoff-1  | server-0  |     }
xlien-api-payoff-1  | server-0  |     error: {
xlien-api-payoff-1  | server-0  |       "data": null,
xlien-api-payoff-1  | server-0  |       "isBoom": true,
xlien-api-payoff-1  | server-0  |       "isServer": false,
xlien-api-payoff-1  | server-0  |       "output": {
xlien-api-payoff-1  | server-0  |         "statusCode": 401,
xlien-api-payoff-1  | server-0  |         "payload": {
xlien-api-payoff-1  | server-0  |           "statusCode": 401,
xlien-api-payoff-1  | server-0  |           "error": "Unauthorized",
xlien-api-payoff-1  | server-0  |           "message": "Invalid headers supplied"
xlien-api-payoff-1  | server-0  |         },
xlien-api-payoff-1  | server-0  |         "headers": {
xlien-api-payoff-1  | server-0  |           "WWW-Authenticate": "Basic realm=\"LossExpress\""
xlien-api-payoff-1  | server-0  |         }
xlien-api-payoff-1  | server-0  |       }
xlien-api-payoff-1  | server-0  |     }
xlien-api-payoff-1  | server-0  | [1676016600654] ERROR (24 on c7d4f1f85d3a):
xlien-api-payoff-1  | server-0  |     request: "1676016600653:c7d4f1f85d3a:24:ldy8za0l:10028"
xlien-api-payoff-1  | server-0  |     tags: [
xlien-api-payoff-1  | server-0  |       "auth",
xlien-api-payoff-1  | server-0  |       "unauthenticated",
xlien-api-payoff-1  | server-0  |       "error",
xlien-api-payoff-1  | server-0  |       "twilio"
xlien-api-payoff-1  | server-0  |     ]
xlien-api-payoff-1  | server-0  |     channel: "internal"
xlien-api-payoff-1  | server-0  |     req: {
xlien-api-payoff-1  | server-0  |       "id": "1676016600653:c7d4f1f85d3a:24:ldy8za0l:10028",
xlien-api-payoff-1  | server-0  |       "method": "post",
xlien-api-payoff-1  | server-0  |       "url": "/jobs/call/CA73e8de5b0985ea10416c61d588f289e7/status-update/6681f970-ae57-46c8-bd7a-795d833b2c03",
xlien-api-payoff-1  | server-0  |       "headers": {
xlien-api-payoff-1  | server-0  |         "host": "dev7.ngrok.lossexpress.com",
xlien-api-payoff-1  | server-0  |         "user-agent": "TwilioProxy/1.1",
xlien-api-payoff-1  | server-0  |         "content-length": "394",
xlien-api-payoff-1  | server-0  |         "accept": "*/*",
xlien-api-payoff-1  | server-0  |         "content-type": "application/x-www-form-urlencoded; charset=UTF-8",
xlien-api-payoff-1  | server-0  |         "i-twilio-idempotency-token": "3def80e2-b540-4585-bea4-390192bf95e6",
xlien-api-payoff-1  | server-0  |         "x-forwarded-for": "18.209.27.48",
xlien-api-payoff-1  | server-0  |         "x-forwarded-proto": "http",
xlien-api-payoff-1  | server-0  |         "x-home-region": "us1",
xlien-api-payoff-1  | server-0  |         "x-twilio-signature": "bSnyKsBhrA0g0KeQEab3e/LQ4Q4=",
xlien-api-payoff-1  | server-0  |         "accept-encoding": "gzip"
xlien-api-payoff-1  | server-0  |       },
xlien-api-payoff-1  | server-0  |       "remoteAddress": "127.0.0.1",
xlien-api-payoff-1  | server-0  |       "remotePort": 38910
xlien-api-payoff-1  | server-0  |     }
xlien-api-payoff-1  | server-0  |     error: {
xlien-api-payoff-1  | server-0  |       "data": null,
xlien-api-payoff-1  | server-0  |       "isBoom": true,
xlien-api-payoff-1  | server-0  |       "isServer": false,
xlien-api-payoff-1  | server-0  |       "output": {
xlien-api-payoff-1  | server-0  |         "statusCode": 401,
xlien-api-payoff-1  | server-0  |         "payload": {
xlien-api-payoff-1  | server-0  |           "statusCode": 401,
xlien-api-payoff-1  | server-0  |           "error": "Unauthorized",
xlien-api-payoff-1  | server-0  |           "message": "Invalid headers supplied"
xlien-api-payoff-1  | server-0  |         },
xlien-api-payoff-1  | server-0  |         "headers": {
xlien-api-payoff-1  | server-0  |           "WWW-Authenticate": "Basic realm=\"LossExpress\""
xlien-api-payoff-1  | server-0  |         }
xlien-api-payoff-1  | server-0  |       }
xlien-api-payoff-1  | server-0  |     }
xlien-api-payoff-1  | server-0  | [1676016601107] ERROR (24 on c7d4f1f85d3a):
xlien-api-payoff-1  | server-0  |     request: "1676016601106:c7d4f1f85d3a:24:ldy8za0l:10030"
xlien-api-payoff-1  | server-0  |     tags: [
xlien-api-payoff-1  | server-0  |       "auth",
xlien-api-payoff-1  | server-0  |       "unauthenticated",
xlien-api-payoff-1  | server-0  |       "error",
xlien-api-payoff-1  | server-0  |       "twilio"
xlien-api-payoff-1  | server-0  |     ]
xlien-api-payoff-1  | server-0  |     channel: "internal"
xlien-api-payoff-1  | server-0  |     req: {
xlien-api-payoff-1  | server-0  |       "id": "1676016601106:c7d4f1f85d3a:24:ldy8za0l:10030",
xlien-api-payoff-1  | server-0  |       "method": "post",
xlien-api-payoff-1  | server-0  |       "url": "/jobs/call/CA73e8de5b0985ea10416c61d588f289e7/status-update/6681f970-ae57-46c8-bd7a-795d833b2c03",
xlien-api-payoff-1  | server-0  |       "headers": {
xlien-api-payoff-1  | server-0  |         "host": "dev7.ngrok.lossexpress.com",
xlien-api-payoff-1  | server-0  |         "user-agent": "TwilioProxy/1.1",
xlien-api-payoff-1  | server-0  |         "content-length": "351",
xlien-api-payoff-1  | server-0  |         "accept": "*/*",
xlien-api-payoff-1  | server-0  |         "content-type": "application/x-www-form-urlencoded; charset=UTF-8",
xlien-api-payoff-1  | server-0  |         "i-twilio-idempotency-token": "81fb0297-a6a0-470c-a5f4-a8dc5985da05",
xlien-api-payoff-1  | server-0  |         "x-forwarded-for": "54.162.64.218",
xlien-api-payoff-1  | server-0  |         "x-forwarded-proto": "http",
xlien-api-payoff-1  | server-0  |         "x-home-region": "us1",
xlien-api-payoff-1  | server-0  |         "x-twilio-signature": "eeIe9/xFx3Xyb9iB/nabV65zavc=",
xlien-api-payoff-1  | server-0  |         "accept-encoding": "gzip"
xlien-api-payoff-1  | server-0  |       },
xlien-api-payoff-1  | server-0  |       "remoteAddress": "127.0.0.1",
xlien-api-payoff-1  | server-0  |       "remotePort": 38934
xlien-api-payoff-1  | server-0  |     }
xlien-api-payoff-1  | server-0  |     error: {
xlien-api-payoff-1  | server-0  |       "data": null,
xlien-api-payoff-1  | server-0  |       "isBoom": true,
xlien-api-payoff-1  | server-0  |       "isServer": false,
xlien-api-payoff-1  | server-0  |       "output": {
xlien-api-payoff-1  | server-0  |         "statusCode": 401,
xlien-api-payoff-1  | server-0  |         "payload": {
xlien-api-payoff-1  | server-0  |           "statusCode": 401,
xlien-api-payoff-1  | server-0  |           "error": "Unauthorized",
xlien-api-payoff-1  | server-0  |           "message": "Invalid headers supplied"
xlien-api-payoff-1  | server-0  |         },
xlien-api-payoff-1  | server-0  |         "headers": {
xlien-api-payoff-1  | server-0  |           "WWW-Authenticate": "Basic realm=\"LossExpress\""
xlien-api-payoff-1  | server-0  |         }
xlien-api-payoff-1  | server-0  |       }
xlien-api-payoff-1  | server-0  |     }
xlien-api-payoff-1  | server-0  | [1676016601132] ERROR (24 on c7d4f1f85d3a):
xlien-api-payoff-1  | server-0  |     request: "1676016601131:c7d4f1f85d3a:24:ldy8za0l:10031"
xlien-api-payoff-1  | server-0  |     tags: [
xlien-api-payoff-1  | server-0  |       "auth",
xlien-api-payoff-1  | server-0  |       "unauthenticated",
xlien-api-payoff-1  | server-0  |       "error",
xlien-api-payoff-1  | server-0  |       "twilio"
xlien-api-payoff-1  | server-0  |     ]
xlien-api-payoff-1  | server-0  |     channel: "internal"
xlien-api-payoff-1  | server-0  |     req: {
xlien-api-payoff-1  | server-0  |       "id": "1676016601131:c7d4f1f85d3a:24:ldy8za0l:10031",
xlien-api-payoff-1  | server-0  |       "method": "post",
xlien-api-payoff-1  | server-0  |       "url": "/jobs/call/CA73e8de5b0985ea10416c61d588f289e7/status-update/6681f970-ae57-46c8-bd7a-795d833b2c03",
xlien-api-payoff-1  | server-0  |       "headers": {
xlien-api-payoff-1  | server-0  |         "host": "dev7.ngrok.lossexpress.com",
xlien-api-payoff-1  | server-0  |         "user-agent": "TwilioProxy/1.1",
xlien-api-payoff-1  | server-0  |         "content-length": "394",
xlien-api-payoff-1  | server-0  |         "accept": "*/*",
xlien-api-payoff-1  | server-0  |         "content-type": "application/x-www-form-urlencoded; charset=UTF-8",
xlien-api-payoff-1  | server-0  |         "i-twilio-idempotency-token": "3d1412eb-823d-44eb-a8ca-eef552943993",
xlien-api-payoff-1  | server-0  |         "x-forwarded-for": "23.20.90.71",
xlien-api-payoff-1  | server-0  |         "x-forwarded-proto": "http",
xlien-api-payoff-1  | server-0  |         "x-home-region": "us1",
xlien-api-payoff-1  | server-0  |         "x-twilio-signature": "0omtmgbcsdBNFwiEPDRQNw0wLvM=",
xlien-api-payoff-1  | server-0  |         "accept-encoding": "gzip"
xlien-api-payoff-1  | server-0  |       },
xlien-api-payoff-1  | server-0  |       "remoteAddress": "127.0.0.1",
xlien-api-payoff-1  | server-0  |       "remotePort": 38944
xlien-api-payoff-1  | server-0  |     }
xlien-api-payoff-1  | server-0  |     error: {
xlien-api-payoff-1  | server-0  |       "data": null,
xlien-api-payoff-1  | server-0  |       "isBoom": true,
xlien-api-payoff-1  | server-0  |       "isServer": false,
xlien-api-payoff-1  | server-0  |       "output": {
xlien-api-payoff-1  | server-0  |         "statusCode": 401,
xlien-api-payoff-1  | server-0  |         "payload": {
xlien-api-payoff-1  | server-0  |           "statusCode": 401,
xlien-api-payoff-1  | server-0  |           "error": "Unauthorized",
xlien-api-payoff-1  | server-0  |           "message": "Invalid headers supplied"
xlien-api-payoff-1  | server-0  |         },
xlien-api-payoff-1  | server-0  |         "headers": {
xlien-api-payoff-1  | server-0  |           "WWW-Authenticate": "Basic realm=\"LossExpress\""
xlien-api-payoff-1  | server-0  |         }
xlien-api-payoff-1  | server-0  |       }
xlien-api-payoff-1  | server-0  |     }
xlien-api-payoff-1  | server-0  | [1676016605730] ERROR (24 on c7d4f1f85d3a):
xlien-api-payoff-1  | server-0  |     request: "1676016605727:c7d4f1f85d3a:24:ldy8za0l:10034"
xlien-api-payoff-1  | server-0  |     tags: [
xlien-api-payoff-1  | server-0  |       "auth",
xlien-api-payoff-1  | server-0  |       "unauthenticated",
xlien-api-payoff-1  | server-0  |       "error",
xlien-api-payoff-1  | server-0  |       "twilio"
xlien-api-payoff-1  | server-0  |     ]
xlien-api-payoff-1  | server-0  |     channel: "internal"
xlien-api-payoff-1  | server-0  |     req: {
xlien-api-payoff-1  | server-0  |       "id": "1676016605727:c7d4f1f85d3a:24:ldy8za0l:10034",
xlien-api-payoff-1  | server-0  |       "method": "post",
xlien-api-payoff-1  | server-0  |       "url": "/jobs/call/6681f970-ae57-46c8-bd7a-795d833b2c03/recording-info",
xlien-api-payoff-1  | server-0  |       "headers": {
xlien-api-payoff-1  | server-0  |         "host": "dev7.ngrok.lossexpress.com",
xlien-api-payoff-1  | server-0  |         "user-agent": "TwilioProxy/1.1",
xlien-api-payoff-1  | server-0  |         "content-length": "469",
xlien-api-payoff-1  | server-0  |         "accept": "*/*",
xlien-api-payoff-1  | server-0  |         "content-type": "application/x-www-form-urlencoded; charset=UTF-8",
xlien-api-payoff-1  | server-0  |         "i-twilio-idempotency-token": "5834c681-03e2-48e9-a9df-e7488b261f50",
xlien-api-payoff-1  | server-0  |         "x-forwarded-for": "18.205.113.55",
xlien-api-payoff-1  | server-0  |         "x-forwarded-proto": "http",
xlien-api-payoff-1  | server-0  |         "x-home-region": "us1",
xlien-api-payoff-1  | server-0  |         "x-twilio-signature": "3Jba7fg1R/OgyBiXlnvKbd4s/Uk=",
xlien-api-payoff-1  | server-0  |         "accept-encoding": "gzip"
xlien-api-payoff-1  | server-0  |       },
xlien-api-payoff-1  | server-0  |       "remoteAddress": "127.0.0.1",
xlien-api-payoff-1  | server-0  |       "remotePort": 38952
xlien-api-payoff-1  | server-0  |     }
xlien-api-payoff-1  | server-0  |     error: {
xlien-api-payoff-1  | server-0  |       "data": null,
xlien-api-payoff-1  | server-0  |       "isBoom": true,
xlien-api-payoff-1  | server-0  |       "isServer": false,
xlien-api-payoff-1  | server-0  |       "output": {
xlien-api-payoff-1  | server-0  |         "statusCode": 401,
xlien-api-payoff-1  | server-0  |         "payload": {
xlien-api-payoff-1  | server-0  |           "statusCode": 401,
xlien-api-payoff-1  | server-0  |           "error": "Unauthorized",
xlien-api-payoff-1  | server-0  |           "message": "Invalid headers supplied"
xlien-api-payoff-1  | server-0  |         },
xlien-api-payoff-1  | server-0  |         "headers": {
xlien-api-payoff-1  | server-0  |           "WWW-Authenticate": "Basic realm=\"LossExpress\""
xlien-api-payoff-1  | server-0  |         }
xlien-api-payoff-1  | server-0  |       }
xlien-api-payoff-1  | server-0  |     }

```