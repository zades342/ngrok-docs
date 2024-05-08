---
title: How to Share Local Files Securely
description: How to Share Local Files Securely.
tags:
  - guides
  - tunnels
  - authentication
  - oauth
  - authorization
---

<!-- prettier-ignore -->
<!-- Imports -->

import Tabs from "@theme/Tabs";
import TabItem from "@theme/TabItem";

<!-- Guide -->

While ngrok can be used to serve websites and applications, it also can be used to share local files and directories with a simple CLI command. Pair this alongside ngrok's OAuth functionality, you can protect sensitive files and only make them available to people you want to have access.

In this guide, we will introduce you to the [File Serving](/http/#file-serving) functionality of HTTP endpoints, as well as leverage the [OAuth](/http/oauth/) module to protect our files and make them accessible to a few users.

### Serving files with ngrok

First, you must have the ngrok agent installed, and you must create an ngrok account. For more information on preparing your computer and account, please read the [Getting Started guide](/getting-started/).

After your account is created, and your agent is configured with your authtoken, you now are ready to serve local files on to the internet with a simple CLI command.

```bash
ngrok http file:///<directory>
```

In an example environment, let's execute this command and see what happens.

```bash
 $ tree fakedir
fakedir
├── fakedir
│   └── fakefile2
├── fakefile1
└── fakefile2

 $ ngrok http file:///home/user/fakedir/

ngrok   (Ctrl+C to quit)

Session Status                online
Account                       user@ngrok.com (Plan: Free)
Version                       3.9.0
Region                        United States (us)
Latency                       10ms 
Web Interface                 http://127.0.0.1:4040
Forwarding                    https://randomendpoint.ngrok.app -> file:///home/user/fakedir/

Connections                   ttl     opn     rt1     rt5     p50     p90
                              0       0       0.00    0.00    0.00    0.00

```

This makes a basic website available on the internet, backed by HTTPS, with a list of files and directories available to be viewed and downloaded.

![](/img/howto/share-local-files/img1.png)