# Ralph Chat Mobile


The PhoneGap app powering [Ralph](https://github.com/marbemac/ralph/commits?author=marbemac).


## Requirements

- Xcode
- iOS SDK >= 7.0
- Cordova/PhoneGap >= 3.5
- A working version of the Ralph Chat Meteor app, linked above.


## Setup

- Clone the repository, and change into the new directory.
- Open www/index.html, and replace line 30 with the URL to your Ralph Chat server. Normally it will be running on your local machine, in which case you need to use your private IP. Your private IP can be found in the Network pane of OSX.
- Save the file, and run "cordova build" in the command line.
- Double click the platforms/ios/Ralph.xcodeproj file to open the project in Xcode.
- Run the app!


There are some extra config variables located in config.xml (in the root). Set those if you want. 

Create an issue or hit me up on Twitter @marbemac if you have questions.
