# Music

Play managed audio files with a shared library, queue, shuffle, repeat and system media controls.

## Install

Requires a running [Ink OS](https://github.com/siliconjungle/ink-os-platform) instance and its `ink-os` CLI. Use Node.js 24 or later for development.

```sh
git clone https://github.com/siliconjungle/ink-app-music.git
cd ink-app-music
npm test
# Select your Ink instance using its CLI connection profile.
ink-os deploy .
```

The CLI deploys committed source from your checkout. Commit any edits before deploying them. No credentials or personal instance configuration belong in this repository.

## Behaviour and limits

Playback continues across desktops and minimization; closing the app stops it. Browser codec support applies. Removing a library entry preserves the source file.

## License

MIT for app code. Bundled third-party components retain their own licenses and notices.
