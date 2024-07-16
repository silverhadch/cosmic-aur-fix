# cosmic-aur-fix
YES I KNOW I HAVE TO DO IT OVER THE AUR BUT MY ARCH ACCOUNT DOESNT WORK FOR SOME REASON!!!
Current AUR packages cosmic-greeter-git and cosmic-session-git are broken. 
Because the cosmic-session expects the User to globaly initialise git-lfs for cosmic-applets and cosmic-greeter. Also more severe git-lfs in makepkg is not possible on Arch Linux without a tool called makepkg-git-lfs-proto and with that cosmic-greeter-git will fail and cosmic-session-git cant finish building.


Instructions to install when the AUR packages are not repaired:
First make sure 'git-lfs' and 'makepkg-git-lfs-proto' are installed. 
Then download/clone 'cosmic-greeter-git' and 'makepkg -si' in its directory. Same for 'cosmic-applets-git'.
And lastly for 'cosmic-session-git'
Log out and Reboot.
