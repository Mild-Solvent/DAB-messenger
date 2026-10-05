# DAB Messenger

**[Download the latest APK →](https://github.com/Mild-Solvent/DAB-messenger/releases/latest/download/DAB-Messenger.apk)**

Encrypted chat and calls with a close circle of friends: no account, no phone
number, no server of ours. It is [DAB](https://github.com/Mild-Solvent/DAB)
without the map, and it talks to DAB users.

- **Chat** with photos, files, voice messages, replies, reactions and edits.
  Delivered and read ticks, and a typing indicator; both can be switched off.
- **Voice and video calls**, one to one, peer to peer.
- **No location at all.** The app does not ask for location permission and
  keeps no standing connection to your friends, so a friend learns your IP
  address only while the two of you are in a call.
- **Messages travel encrypted** through public Nostr relays and dab-nodes,
  mailbox servers anyone can run that hold only ciphertext and delete it on
  delivery. Run your own and add it in Settings → Network; your friends' apps
  then deliver to it too.

## Install

1. Open [the latest release](https://github.com/Mild-Solvent/DAB-messenger/releases/latest)
   on the phone and download `DAB-Messenger.apk`.
2. Allow your browser to install unknown apps (Settings → Apps → your browser →
   *Install unknown apps*).
3. Open the file and install. It installs next to DAB, not over it.

After that the app checks this repository for a new release at most once a day
and offers the download itself (Settings → Updates switches that off).

Android 7+.

## Honest limits

Alpha software for a handful of friends. Not audited. No forward secrecy yet,
no group chats, and relays and nodes see your IP address (a VPN or Orbot hides
it). Signed with a development key, so Android warns about an unknown
developer. [How it compares](https://mild-solvent.github.io/DAB/compare.html).
