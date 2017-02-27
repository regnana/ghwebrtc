# ghwebrtc
A WebRTC application by Fred and I to help medical personnel provide remote services to rural areas in Ghana

This application will enable a nurse/MA in a remote place to contact a specialist in Accra for help with a patient. The nurse/MA would first have to register on the application's website to get a username and password. Upon accessing the webrtc portal s/he would have to log in with username and password, then enter an authentication code sent to his/er phone by SMS to prove his/her identity(Two Factor Authentication). 
After a successful login he/she would be have acess to a list of specialists currently available and would be able to call any of them by clicking a link/button. During a call, the following functionalities would be supported: text chat, video call (of course with audio), file sending, and media sharing. The whole session would be automatically recorded for review purposes.

The program will be built with expressjs using socket.io. 
As we go along we will perform a proper system analysis and add up the pieces one by one.
