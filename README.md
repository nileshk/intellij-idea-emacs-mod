intellij-idea-emacs-mod
=======================

This is what I currently use to modify IntelliJ IDEA Ultimate with patches to make it's Emacs mode behave more like Emacs.  It is derived from the open source intellij-community project.  In this repo I have a patch file for my source code modifications.  I also have the binary class files that were modified, and a bash script that copies them into a copy of IntelliJ Ultimate for OS X.  The script checks that is a known version of IntelliJ Ultimate that I have verified (uses MD5 for check).

I have made the following modifications:

* Incremental search is exited when the enter key is pressed
* Cancelling incremental search returns the cursor back to the original location before search was started; Based on Ken Chatfield's patch from here: https://youtrack.jetbrains.com/issue/IDEA-117967