# bittorrent
A BitTorrent and WebTorrent Integration and Components for can be used with @componenent-manager 

# Goals
Connect to the bittorrent,webtorrent network via 
```ts
const { readable, writeable } = await import('@componenet-manager/networking/tcp-ip.js?ip=x&port=x&protocol=bittorrent'); // tTP
const { readable, writeable } = await import('@componenet-manager/networking/udp-ip.js?ip=x&port=x&protocol=bittorrent'); // uTP
const { readable, writeable } = await import('@componenet-manager/networking/webrtc.js?ice=[}&protocol=webtorrent');// wTP
```
