#Project Proposal
For my 4th year project I intend to develop a Peer-to-peer (P2P) video streaming/chat program for 2 people
developed in node.
The project will be developed over an eight month period between September and April inclusive.

#Usage
The flow of how the user would use the program is as follows:

  * The user would open the program which would exist as a dedicated app on their machine, as
    opposed to a web service.

  * The program window would open.

  * The user would be prompted to enter an id for the user they want to connect with.
    They would also be shown their own id.

  * When a connection is requested the user is prompted to accept or deny the request.
    If denied, then the requestor is informed that their request was denied.
    Otherwise a connection is made and the chat window now becomes functional.

  * The person who accepts becomes the host.

  * The host decides what video on their local file system is to be shown.

  * Both host and guest have access to video control functions, pause/play, fast-forward, rewind.

  * Audio slider settings are host/guest independent.

  * The host also has a 'LOCK' button which prevents the other party from using the video control buttons.The guest will be made aware when they are locked.

  * Messages sent through the chat window will be sent to the other party and appear in the chat log for both parties.

#Design
 [image](image)

#Tools
The tools I intend to use for the development of this project are as follows:

  * Electron: Electron will be the app the program lives in and will allow it to exist as a standalone program.

  * WebRTC: Webrtc will be used for connecting the two instances and transmitting data between them.
  
  * VideoJS: VideoJs will be used for video playback in the electron window.

 [image] : ./images/Untitled.png
