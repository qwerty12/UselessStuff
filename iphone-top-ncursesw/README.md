Top for iOS built against libncursesw
===========================================================================

For some reason, under iOS 7, attempting to run any ncurses program linked against the "normal", non-Unicode version results in a "Error opening terminal" message. I found linking the same program to the Unicode version, ncursesw, works for some reason.

Since `top` is the only such program I use, here it is...

The patches apply against the top-39.tar.gz file found [here](http://www.opensource.apple.com/tarballs/top/). The patches with saurik in the file name were created by Jay Freeman and taken from [here](http://svn.saurik.com/repos/telesphoreo/trunk/data/top/).

NOTE: This has been cross-compiled from a computer running Arch Linux targeting the iOS 6.0 SDK. No idea how to do it from OS X. I have also used 
