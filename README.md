---
title: My Project
language_tabs:
  - shell: Shell
  - http: HTTP
  - javascript: JavaScript
  - ruby: Ruby
  - python: Python
  - php: PHP
  - java: Java
  - go: Go
toc_footers: []
includes: []
search: true
code_clipboard: true
highlight_theme: darkula
headingLevel: 2
generator: "@tarslib/widdershins v4.0.23"

---

# My Project

Base URLs:

* <a href="https://prod.your-api-server.com">Prod Env: https://prod.your-api-server.com</a>

# Authentication

# Nextdns 

## GET Nextdns 

GET /profiles/85d564/logs

> Body Parameters

```yaml
{}

```

### Params

|Name|Location|Type|Required|Description|
|---|---|---|---|---|
|x-api-key|header|string| yes |none|
|body|body|object| no |none|

> Response Examples

```json
{
  "data": [
    {
      "timestamp": "2024-12-01T01:20:07.920Z",
      "domain": "az1-api-txpro.kwai-pro.com",
      "root": "kwai-pro.com",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "2804:678c:c176:d500:4929:a1fd:ee4:3693",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:16:38.036Z",
      "domain": "web.diagnostic.networking.aws.dev",
      "root": "aws.dev",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:16:11.711Z",
      "domain": "ap.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:15:23.500Z",
      "domain": "arcus-uswest.amazon.com",
      "root": "amazon.com",
      "tracker": "amazon",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:15:14.717Z",
      "domain": "ap-guc3.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:12:54.778Z",
      "domain": "ap-gue1.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:11:35.201Z",
      "domain": "web.diagnostic.networking.aws.dev",
      "root": "aws.dev",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:07:48.953Z",
      "domain": "ap-guc3.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:06:34.259Z",
      "domain": "web.diagnostic.networking.aws.dev",
      "root": "aws.dev",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:06:07.056Z",
      "domain": "api.amazonalexa.com",
      "root": "amazonalexa.com",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:05:57.537Z",
      "domain": "ap-gue1.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:05:57.353Z",
      "domain": "apresolve.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:04:15.024Z",
      "domain": "ap.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:03:38.490Z",
      "domain": "ap-gew4.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:03:38.118Z",
      "domain": "ap-gae2.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:02:42.975Z",
      "domain": "ap-guc3.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:01:31.238Z",
      "domain": "web.diagnostic.networking.aws.dev",
      "root": "aws.dev",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:00:51.846Z",
      "domain": "ap-gue1.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:00:51.621Z",
      "domain": "apresolve.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:00:21.578Z",
      "domain": "ipv6.msftconnecttest.com",
      "root": "msftconnecttest.com",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "2804:678c:c176:d500:21e4:8ee6:26f2:6800",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:00:21.578Z",
      "domain": "www.msftconnecttest.com",
      "root": "msftconnecttest.com",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "2804:678c:c176:d500:21e4:8ee6:26f2:6800",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:00:21.565Z",
      "domain": "xflight.xboxlive.com",
      "root": "xboxlive.com",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "2804:678c:c176:d500:21e4:8ee6:26f2:6800",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T01:00:21.564Z",
      "domain": "xsts.auth.xboxlive.com",
      "root": "xboxlive.com",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "2804:678c:c176:d500:21e4:8ee6:26f2:6800",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:58:22.014Z",
      "domain": "a1rabvci4qcikc.us-east-1.prod.service.minerva.devices.a2z.com",
      "root": "a2z.com",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:56:58.471Z",
      "domain": "ap.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:56:30.425Z",
      "domain": "web.diagnostic.networking.aws.dev",
      "root": "aws.dev",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:56:12.657Z",
      "domain": "ap-gew4.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:56:12.413Z",
      "domain": "ap-gew1.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:55:15.197Z",
      "domain": "ap-gae2.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:53:24.318Z",
      "domain": "ap-gue1.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:53:24.126Z",
      "domain": "apresolve.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:51:27.075Z",
      "domain": "web.diagnostic.networking.aws.dev",
      "root": "aws.dev",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:47:58.792Z",
      "domain": "ap.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:47:22.779Z",
      "domain": "ap-guc3.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:46:26.447Z",
      "domain": "web.diagnostic.networking.aws.dev",
      "root": "aws.dev",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:45:39.865Z",
      "domain": "ap-gue1.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:45:39.644Z",
      "domain": "apresolve.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:45:15.966Z",
      "domain": "az1-api-txpro.kwai-pro.com",
      "root": "kwai-pro.com",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "2804:678c:c176:d500:4929:a1fd:ee4:3693",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:45:05.958Z",
      "domain": "clients4.google.com",
      "root": "google.com",
      "tracker": "google",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "2804:678c:c176:d500:4929:a1fd:ee4:3693",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:44:59.456Z",
      "domain": "optimizationguide-pa.googleapis.com",
      "root": "optimizationguide-pa.googleapis.com",
      "tracker": "googleapis.com",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "2804:678c:c176:d500:4929:a1fd:ee4:3693",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:44:56.765Z",
      "domain": "accounts.google.com",
      "root": "google.com",
      "tracker": "google",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "2804:678c:c176:d500:4929:a1fd:ee4:3693",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:44:34.749Z",
      "domain": "encrypted-tbn0.gstatic.com",
      "root": "gstatic.com",
      "tracker": "gstatic",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "2804:678c:c176:d500:4929:a1fd:ee4:3693",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:44:32.636Z",
      "domain": "discover-pa.googleapis.com",
      "root": "discover-pa.googleapis.com",
      "tracker": "googleapis.com",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "2804:678c:c176:d500:4929:a1fd:ee4:3693",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:44:29.077Z",
      "domain": "api.amazonalexa.com",
      "root": "amazonalexa.com",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:41:22.662Z",
      "domain": "web.diagnostic.networking.aws.dev",
      "root": "aws.dev",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:40:23.824Z",
      "domain": "ap.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:40:05.211Z",
      "domain": "api.amazonalexa.com",
      "root": "amazonalexa.com",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:39:18.400Z",
      "domain": "ap-guc3.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:37:27.228Z",
      "domain": "ap-gue1.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:37:27.052Z",
      "domain": "apresolve.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:36:22.192Z",
      "domain": "d3p8zr0ffa9t17.cloudfront.net",
      "root": "d3p8zr0ffa9t17.cloudfront.net",
      "tracker": "amazon_cloudfront",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:36:07.100Z",
      "domain": "web.diagnostic.networking.aws.dev",
      "root": "aws.dev",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:34:49.977Z",
      "domain": "api.amazonalexa.com",
      "root": "amazonalexa.com",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:31:24.616Z",
      "domain": "ap.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:31:06.298Z",
      "domain": "web.diagnostic.networking.aws.dev",
      "root": "aws.dev",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:30:19.422Z",
      "domain": "ap-guc3.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:28:49.184Z",
      "domain": "apresolve.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:28:29.532Z",
      "domain": "api.amazonalexa.com",
      "root": "amazonalexa.com",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:28:19.019Z",
      "domain": "a1rabvci4qcikc.us-east-1.prod.service.minerva.devices.a2z.com",
      "root": "a2z.com",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:28:19.019Z",
      "domain": "arcus-uswest.amazon.com",
      "root": "amazon.com",
      "tracker": "amazon",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:27:51.585Z",
      "domain": "ap.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:27:14.587Z",
      "domain": "api.amazon.com",
      "root": "amazon.com",
      "tracker": "amazon",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:26:02.440Z",
      "domain": "web.diagnostic.networking.aws.dev",
      "root": "aws.dev",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:25:58.552Z",
      "domain": "ap-gue1.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:23:12.703Z",
      "domain": "ap.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:22:15.695Z",
      "domain": "ap-guc3.spotify.com",
      "root": "spotify.com",
      "tracker": "spotify",
      "encrypted": false,
      "protocol": "UDP",
      "clientIp": "45.190.211.150",
      "status": "default",
      "reasons": []
    },
    {
      "timestamp": "2024-12-01T00:21:40.247Z",
      "domain": "api.amazonalexa.com",
      "root": "amazonalexa.com",
      "encrypted": false,
      "protocol": "UDP",
      "client
