# Media Server Connection Instructions

## Prerequisites
- Install Tailscale on the device you will be watching on: https://tailscale.com/download
- Jellyfin account (I will set this up for you and share the username and password)
- _(Optional)_ Install a media client for playback:
    - [Infuse](https://firecore.com/infuse) **(My favorite - Apple only)**
    - [Swiftfin iOS / Mac](https://apps.apple.com/us/app/swiftfin/id1604098728)
    - [Swiftfin Windows](https://github.com/jellyfin/jellyfin-media-player/releases/download/v1.11.1/JellyfinMediaPlayer-1.11.1-windows-x64.exe) (My choice when watching on my PC)
    - You can also watch in your browser using the server URL


## Setup Instructions
1. Text me your email and I will send you an invite to join my VPN network
2. After receiving the invite, set up a Tailscale account
3. Sign in to the Tailscale app on **whichever device you installed the app on**.
4. Connect to the Tailscale VPN
5. Sign in to the media server **on the same device connected to Tailscale VPN**
    1. Infuse: Files --> Add Files --> Saved Shares Add... --> Other Jellyfin --> Enter server address (jellyfin.tailxxxxxx.ts.net), username, & password
    2. Swiftfin: Connect -->  Server URL (jellyfin.tailxxxxxx.ts.net) --> Enter username & password
        **NOTE:** If you have buffering issues with Swiftfin, go to settings and try switching the video player to "Native" under "Video Player Type".
    3. Browser: jellyfin.tailxxxxxx.ts.net --> Enter username & password


## Important Notes

* **Jellyfin and Tailscale are two completely separate accounts. Tailscale is a VPN that allows you to reach the server and Jellyfin is the actual login that gets you into the server**
* **Please do not share logins, I can only have so many people on the tailscale free tier**
* **Enjoy my media server to the fullest extent but be mindful that streaming uses my hardware and internet bandwidth, I would appreciate not letting it run when you aren't using it**


## Wrapping Up

Unfortunately you need to be connected to the VPN when streaming content. Removing the need for a VPN would open up my home server to the world and I do not want to manage the security needed to allow that.

This should work with any device that allows the use of a VPN, I usually watch on my phone or PC. I am going to keep looking into ways to get it working on an Apple TV, but this is how it is going to be for a while.

I am also working on setting up Ombi, which will allow you to request new shows and movies.

Don't hesitate to reach out with questions or to provide feedback!