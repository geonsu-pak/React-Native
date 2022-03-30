# you want to develop for iOS you must have a Mac
## Must installations
* Xcode
* Node.js
* Watchman
* React Native command-line interface

## Follow these steps:
* Install Homebrew, go to http://brew.sh
* Node & Watchman 
<pre>brew install node</pre>
<pre>brew install watchman</pre>
* Xcode, go to Mac App Store
* Command Line Tools
  * Open Xcode, then choose "Preferences..." from the Xcode menu.
  * Go to the Locations panel and install the tools by selecting the most recent version in the Command Line Tools dropdown.
* Installing an iOS Simulator in Xcode
  * open Xcode > Preferences... and select the Components tab. 
  * Select a simulator with the corresponding version of iOS you wish to use.
* CocoaPods
<pre>sudo gem install cocoapods</pre>
* react-native-cli
<pre>sudo npm install –g react-native-cli</pre>

 ## Testing the installation on iOS
<pre>react-native init MyProjectName</pre>
<pre>cd MyProjectName</pre>
<pre>npx react-native run-ios</pre>
