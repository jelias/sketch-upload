# Introduction

This [Sketch](http://bohemiancoding.com/sketch) plugin allows designers to upload the selected artboard or slice to
[Cloud App](http://www.getcloudapp.com/) with a simple shortcut `⇧⌘U`.
The plugin works by exporting the first slice named `Preview` to Sketch's cache
directory and uploading that file via Cloud App.


# Installation

1. Just [download](https://github.com/jelias/sketch-plugins/archive/master.zip) the master.

2. Double-click the file `Upload.sketchplugin` inside sketch-upload/. Sketch should open automatically and tell you that a new plugin was installed.


# Usage

1. Select the layer inside the artboard you would like to upload (don't worry it will upload the whole artboard).

2. Then run the plugin via `Plugins > Upload` or the simple shortcut `⇧⌘U`.

3. Sketch will prompt you to name your file, `BE SURE TO KEEP THE .PNG` whatever you name it.

4. That's it! Enjoy, and please share with everyone you know.


> ###Note: 

>	If you want to upload your designs via another service (i.e. Droplr) just change

> `var PREVIEW_APPLICATION = "Cloud";`
	
>	to what ever app you use.

>	BE SURE TO PUT THE APP NAME!


# Compatibility

This plugin was developed with the App Store version of Sketch 2.4.3 and Cloud App 2.0

# Author

[Jacob Elias](https://github.com/jelias)

Follow me & ask questions [@jelias](https://twitter.com/_jelias_)

Feel free to contribute: fork, make pull requests, and issues as this is 100% still under development!

#Thanks

Huge thanks to 
[Marc Schwieterman](https://github.com/marcisme) ([@mschwieterman](https://twitter.com/mschwieterman) / [@mbs](https://app.net/mbs)) for making all this possible!

This plugin is largely based on his [sketch-preview plugin](https://github.com/marcisme/sketch-preview), with a few tweeks from [David Klawitter](https://github.com/davidklaw) and his fork of [sketch-preview](https://github.com/davidklaw/sketch-preview).

# License

MIT License
