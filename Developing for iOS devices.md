# you want to develop for iOS you must have a Mac
## Must installations
* Xcode
* Node.js
* Watchman
* React Native command-line interface

## Follow these steps:
* Install Xcode, which is available through the App Store.
* The React Native docs and I recommend installing Node and Watchman via
Homebrew. If you don’t already have Homebrew installed, go to http://brew.sh
and install it on your machine.
* Open a command line, and install Node and Watchman using Homebrew:
  * brew install node
  * brew install watchman
* Once Node.js is installed, install the React Native command-line tools by running
the following from the command line:
  * npm install –g react-native-cli
* If you get a permission error, try again with sudo:
  * sudo npm install -g react-native-cli
 
 ## Testing the installation on iOS
* react-native init MyProjectName
* cd MyProjectName
* react-native run-ios
