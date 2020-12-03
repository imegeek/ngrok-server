# ngrok-server
ngrok-server allow you to access ngrok without Hotspot with background usage.

![preview](https://user-images.githubusercontent.com/63346676/100966671-7962ae00-3553-11eb-95e7-c9e704478415.jpg)

> Basic Installation :

| Method    | Command
|:----------|:--------------------------------------------------------------------------------------------------|
|  **curl** |`curl --progress-bar -L --fail --retry 4 -O https://github.com/abhackerofficial/ngrok-server/raw/master/ngrok.server.deb ;apt install ./ngrok.server.deb` |

> Manual Installation :
```bash
git clone https://github.com/abhackerofficial/ngrok-server
cd ngrok-server
apt install ./ngrok.server.deb
```

> Usage
```bash
ngrok -http <port> ...
ngrok -tcp <port> ...
```

> Example
```
$ ngrok -tcp 8080

[!] Connection Type: TCP...
[+] Starting ngrok server (tcp 8080)...
[+] Share TCP link: tcp://0.tcp.ngrok.io:14154
```
