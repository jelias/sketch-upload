# Introduction

This [Sketch](http://bohemiancoding.com/sketch) plugin allows designers to upload the selected artboard or slice to
[Cloud App](http://www.getcloudapp.com/) with a simple shortcut `⇧⌘U`.
The plugin works by exporting the selected artboard to Sketch's cache
directory and uploading that file via Cloud App.


# Installation

1. Just [download the most recent release](https://github.com/jelias/sketch-upload/releases/latest).

2. Double-click the file `Upload.sketchplugin` Sketch should open automatically and tell you that a new plugin was installed.


# Usage

1. Select the artboard you would like to upload.

2. Then run the plugin via `Plugins > Upload` or the simple shortcut `⇧⌘U`.

3. Sketch will prompt you to name your file, ~~`BE SURE TO KEEP THE .PNG` whatever you name it~~ (as of v.2 this problem has been fixed).

4. That's it! Enjoy, and please share this plugin with everyone you know!


> ###Note: 

>	If you want to upload your designs via another service (i.e. Droplr) just change

> `var PREVIEW_APPLICATION = "Cloud";`
	
>	to what ever app you use.

>	BUT BE SURE TO PUT THE APP NAME!


# Compatibility

This plugin was developed with the App Store version of Sketch 3.0.1 and Cloud App 2.0

> ###Note:
> Have not tested v.3 on Sketch 2. If there are problems revert to v.2 and let me know! 

# Troubleshooting

If there are any problems with this plugin try debuging the problem first. Simply edit the plugin and set `DEBUG` to `true`  and check the console for errors.

If you are still having problems, create an issue and explain the problem in full detail. For example, provide steps to reproduce the problem and if you are willing, the .sketch file. Logs would aslo be helpful ;) 

# Author

[Jacob Elias](jelias.me)

Follow me & ask questions [@jelias](https://twitter.com/_jelias_)

and feel free to contribute, I don't bite ;)

#Thanks

Huge thanks to 
[Marc Schwieterman](https://github.com/marcisme) ([@mschwieterman](https://twitter.com/mschwieterman) / [@mbs](https://app.net/mbs)) for making all this possible!

This plugin is largely based on his [sketch-preview plugin](https://github.com/marcisme/sketch-preview), with a few tweeks from [David Klawitter](https://github.com/davidklaw) and his fork of [sketch-preview](https://github.com/davidklaw/sketch-preview). Seriously, Marc's plugin is a huge part of Sketch-Upload.

# License

MIT License
