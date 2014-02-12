UNTV Music Player
=================

This is a music player extension for [UNTV](gordonwritescode.github.io/untv). Browse and play music from you local library.

## Setup

End users will want to use UNTV's built in extension manager to install the Music Player.

Developers may like to install via Git and symlink to the extensions directory:

```bash
cd path/to/projects
git clone https://github.com/gordonwritescode/untv-music-player.git
cd ~/.untv/extensions
ln -s path/to/projects/untv-music-player ./
```

Make sure your UNTV `config.json` has `load_third_party_extensions` set to `true` (it should by default).
