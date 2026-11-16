# iFCB

A Mac editor for the Behringer FCB1010 MIDI foot controller. Free.

The successor to iFCB 2.5 by Wabbit Wanch Design.

## Requirements

* macOS 15.7 or later (Apple Silicon or Intel)
* FCB1010 connected through a MIDI interface

## Install

1. Download the latest `iFCB` zip from [Releases](../../releases) and unzip it.
2. Move `iFCB.app` to Applications.
3. Open it. macOS Gatekeeper will refuse to open the app. Click **Done**.
4. Go to **System Settings → Privacy & Security**, scroll down and click **Open Anyway** next to iFCB.

You only need to do this once.

Or, in Terminal:

```
xattr -dr com.apple.quarantine /Applications/iFCB.app
```

## License

Freeware. Free to use and share, not to sell. See [LICENSE.txt](LICENSE.txt).
