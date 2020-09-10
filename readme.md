# Twitch Chat Downloader Enhanced

Built on the original tcd, the enhanced version (planned) will add more fine-tuned search-vector returns, add video downloads, add error-catching-and-retires-later functionality, add parallel processing, add multiple-auth-and-routing, and potentially add other features as well.

As a pseudo amazon web evangelist, I find it funny watching twitch attempt to deal with open source wrappers of their existing systems.

As a deisgn philosphy, in order to fulfill legal and trolling requirements, you must design something that is reasonable in nature itself but easy for anyone to parallel by another factor of N.

### Requirements

* [Python 3.8 or newer](https://www.python.org/downloads/)
* [A Twitch client ID](https://dev.twitch.tv/console/apps)

### Usage

```bash
tcd
```

```bash
# Download chat from VODs by video id
tcd --video 789654123,987456321 --format irc --output ~/Downloads
```

```bash
# Download chat from the first 10 VODs from multiple streamers
tcd --channel sodapoppin,nymn,lirik --first=10
```

### Features
- Create your own [custom formats](https://github.com/PetterKraabol/Twitch-Chat-Downloader/wiki/Custom-formats)
- IRC format with badges
- SRT and SSA [subtitle formats](https://github.com/PetterKraabol/Twitch-Chat-Downloader/wiki/Formats)
- Raw JSON data from the Twitch API
- Timezone conversion

---

[Documentation](https://github.com/PetterKraabol/Twitch-Chat-Downloader/wiki)
 • [Twitch Python](https://github.com/PetterKraabol/Twitch-Python)
