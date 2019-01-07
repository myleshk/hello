## Why Hello?
It's 2018, WebRTC is natively supported in all desktop & mobile browsers but still, most major players (Hangouts, Skype, appear.in, etc.) ask you to download their app to use the service. 

## Hello
Hello is a video chat app that works on most major desktop & mobile browsers. No Signup. No Downloads. Just video chat. 

Hello uses WebRTC for video communication and a socket.io server that serves as a signaling server. It uses WebRTC mesh when more people are added to the call, it means each video stream in a group call uses a separate P2P connection. There is no hard limit on the number of people in the group video call, but the quality of the call will decrease when more than 5 people join the call.

### Screen Sharing
Screen sharing is still not supported by all the browsers. The screen sharing button will be enabled only if the browser supports screen sharing. In Google Chrome *(and in all chromium based browsers)* you can enable screen sharing in `chrome://flags/#enable-experimental-web-platform-features`.

### Credits:
[https://github.com/anoek/webrtc-group-chat-example](https://github.com/anoek/webrtc-group-chat-example)

------------------
If you are here for checking the P2P video call without signaling server, head over to the `gh-pages` branch. And check out the demo here [https://vasanthv.github.io/hello/](https://vasanthv.github.io/hello/).

### License
[WTFPL](http://www.wtfpl.net/)
