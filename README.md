# ios-bluetooth-demo
Bluetooth IOS Control Demo (HTML Side)

# Instructions 
Download binary from [repo releases section](https://github.com/farhanahmedml/ios-bluetooth-demo/releases)

```
Start imirror 
cd into binary folder
example: ./imirror stream -d <UDID> -p <PORT> -s <SIZE ie 360x775>

Start deviceremotecontrol 

example:
cd into binary folder
./deviceremotecontrol -p 0.0.0.0:<PORT> -a default.sh -c defaultConnect.sh -t 3000000

Start Node MJPEG Server 
example: node server.js <PORT>

Modify html and set your streaming url and device udid (bluetooth address)

open page in browser
```
