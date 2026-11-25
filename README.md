# Pulse IPTV for iPhone and iPad

Builds of Pulse IPTV, published automatically, for installing with **SideStore** (no computer needed after the first setup).

**Source link to add in SideStore:**

```
https://raw.githubusercontent.com/mxxxx4x-wq/pulse-iptv-ios-builds/main/apps.json
```

## First setup (once per iPhone, needs a computer)

1. On the iPhone, set a passcode, then install **LocalDevVPN** from the App Store.
2. On the computer, install iTunes (Windows) and **iloader** from https://github.com/nab138/iloader/releases.
3. Connect the iPhone with a cable, unlock it and tap **Trust**.
4. Open iloader, sign in with your Apple ID and choose **Install SideStore**. It also installs the pairing file.
5. On the iPhone: Settings › Privacy & Security › **Developer Mode** › on, restart, confirm.
6. Settings › General › VPN & Device Management › trust your Apple ID.
7. Open LocalDevVPN and connect, then open SideStore and sign in with the same Apple ID.

## Install Pulse IPTV

1. SideStore › **Sources** › **+** › paste the source link above.
2. Open the Pulse IPTV source and tap **Get** / **Free**.
3. Updates appear in SideStore › My Apps when a new build is published.

## Keep it working

- Apps signed with a free Apple ID last **7 days**. SideStore renews them by itself in the background; keep LocalDevVPN installed and open SideStore now and then (with LocalDevVPN on) if it says a refresh is due.
- A free Apple ID can have **3 apps** at a time from SideStore, SideStore itself included.
- If you had Pulse installed with Sideloadly, delete that copy after installing from SideStore. Your accounts come back with Pulse Sync, or by signing in again.

The Apple TV app (`PulseIPTV-tvOS.ipa` in each release) cannot use SideStore; install it with Sideloadly from a computer.

Pulse IPTV is a player only and does not include any channels or content.
