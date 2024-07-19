# Media Server Connection Instructions

## Prerequisites
- Install Tailscale on device you will be watching on: https://tailscale.com/download
- Jellyfin account (I will set this up for you and share the username and password)
- _(Optional)_ Install a media client for playback:
    - [Infuse](https://firecore.com/infuse) **(My favorite)**
    - [Swiftfin](https://apps.apple.com/us/app/swiftfin/id1604098728)
    - You can also watch in your browser using the server URL


## Setup Instructions
1. Text me your email and I will send you an invite to join my VPN network
2. After receiving the invite, set up a Tailscale account
3. Sign in to the Tailscale app on **whichever device you installed the app on**.
4. Connect to the Tailscale VPN
5. Sign in to the media server **on the same device connected to Tailscale VPN**
    1. Infuse: Files --> Add Files --> Saved Shares Add... --> Other Jellyfin --> Enter server address (jellyfin.tailxxxxxx.ts.net), username, & password
    2. Swiftfin: Connect -->  Server URL (jellyfin.tailxxxxxx.ts.net) --> Enter username & password
    3. Browser: jellyfin.tailxxxxxx.ts.net --> Enter username & password
