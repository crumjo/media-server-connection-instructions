# Media Server Connection Instructions

## Prerequisites
- Install Tailscale VPN on the device that you will be watching on: https://tailscale.com/download
- Jellyfin account - I will set this up for you and share the username and password
- _(Optional)_ Install a media client for playback:
    - [Infuse](https://firecore.com/infuse) **(My favorite - Apple only)**
    - [Swiftfin iOS / Mac](https://apps.apple.com/us/app/swiftfin/id1604098728)
    - [Swiftfin Windows](https://github.com/jellyfin/jellyfin-media-player/releases/download/v1.11.1/JellyfinMediaPlayer-1.11.1-windows-x64.exe) (My choice when watching on PC)
    - You can also watch in your browser with the Jellyfin server URL


## Setup Instructions
1. Text me the email address that you would like to use for Tailscale and I will send you an invite to join.
2. After receiving the invite, set up a Tailscale account.
3. Sign in to the Tailscale app that you downloaded earlier.
4. Connect to the Tailscale VPN. There will be a popup asking if you want to allow Tailscale to add VPN configurations. Click allow.
5. Sign in to the media server **on the same device connected to Tailscale VPN:**
    1. Infuse: _Files_ --> _Add Files_ --> Saved Shares _Add..._ --> _Other Jellyfin_ --> _Enter server address (jellyfin.tailxxxxxx.ts.net), username, & password_
    2. Swiftfin: _Connect_ -->  _Server URL (jellyfin.tailxxxxxx.ts.net)_ --> _Enter username & password_
    3. Browser: _jellyfin.tailxxxxxx.ts.net_ --> _Enter username & password_


## Important Notes

* **The server checks for updates every morning from 5:00-5:30. If Jellyfin has an update, there could be a temporary maintenance outage.**
* **Jellyfin and Tailscale are two completely separate accounts. Tailscale is a VPN that allows you to reach the server and Jellyfin is the actual login that gets you into the server.**
* **Please do not share logins, I can only have so many people on the Tailscale free tier.**
* **Enjoy my media server to the fullest extent but be mindful that streaming uses my hardware and internet bandwidth, I would appreciate not letting it run when you aren't using it.**


## FAQ

**Q:** How to reduce Swiftfin buffering?  
**A:** Try switching the video player to "Native" under "Video Player Type".

**Q:** How to reduce Infuse buffreing?  
**A.** Try setting the cache to "Memory Only" under _Settings_ --> _Playback_ --> _Streaming Cache_

**Q:** Can I install this on multiple devices?  
**A:** Yes, simply install and log in to Tailscale on your other device. There is a two login limit on all Jellyfin accounts by default, let me know if you need more and I can change it.

**Q.** Can you download _<insert show / movie here>_ for me?  
**A.** Probably, but I am running low on space so there isn't room for everything. I will try my best though.


## Wrapping Up

Unfortunately you need to be connected to the VPN when streaming content. Removing the need for a VPN would open up my home server to the world and I do not want to manage the security needed to allow that.

This should work with any device that allows the use of a VPN, I usually watch on my phone or PC. I am going to keep looking into ways to get it working on an Apple TV, but this is how it is going to be for a while.

I am also working on setting up Ombi, which will allow you to request new shows and movies.

Don't hesitate to reach out with questions or to provide feedback!