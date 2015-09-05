# Captains-Log

An experiment in building an application for recording daily video logs using Electron and Polymer.

I'm not sure yet how much of this I am going to do in the open because I do intend for this to be a paid product. I'm thinking I'll try to open source as many of the individual elements as possible, while keeping the composition and logic that actually makes the app work private so I can choose to sell it in various App Stores.

Here are some elements I'm thinking of generalizing for open sourcing:

* `z-video-recorder` An element for recording audio and video from the user's webcam/microphone.
* `z-file-saver` An element for saving a stream from `z-video-recorder` to disk. I plan to use Electron for the app, which can access the file system more directly than a browser. This will take some research.
* `z-video-player` An element for playing back recorded video. Possibly extraneous. We'll see.
