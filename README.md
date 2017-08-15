# This is a PoC repo to show the remote command execution vulnerability of git versions prior to 2.14.1.

Get your git version by 
#git --version
if it is older than 2.14.1, please go get it updated to the latest version 2.14.1

Or please try the following command to git clone this repo:
git clone --recurse-submodules git://github.com/superirishdonkey/hello.git

You may find the gnome-calculator application pop up, which being executed by your git command according to the malformed .gitmodules file.

SuperIrishDonkey.
