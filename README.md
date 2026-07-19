# scoop-nihitdev

Official Scoop bucket for software published by **Nihit**.

This bucket provides easy installation and updates for my open-source projects on Windows using **Scoop**.

## Installation

Add the bucket:

```powershell
scoop bucket add nihitdev https://github.com/nihitdev/scoop-nihitdev
```

Install a package:

```powershell
scoop install yoo
```
```powershell
 scoop install nihitdev/youtube-downloader
```


## Available Packages

| Package | Description                                            |
| ------- | ------------------------------------------------------ |
| **yoo** | A tiny developer companion for better coding sessions. |
|**youtube-downloader**| A simple Windows desktop application for downloading YouTube videos, playlists, and MP3 audio, powered by yt-dlp.|

## Updating

Update Scoop:

```powershell
scoop update
```

Update installed packages:

```powershell
scoop update yoo
```

```powershell
scoop update youtube-downloader
```
Every manifest installs the latest stable release directly from GitHub Releases.

Manifest versions and SHA-256 hashes are checked automatically every six hours.
You can also run the **Autoupdate manifests** workflow manually from GitHub Actions.

 ## Contributing

  Found an issue with a manifest?

 Feel free to open an issue or submit a pull request.

## Related Projects

- [yoo-cli](https://github.com/nihitdev/yo-cli) — A tiny developer companion for better coding sessions.
- [Oxide Terminal](https://github.com/nihitdev/rust_terminal) — A terminal application built with Rust.

## License

This repository is licensed under the [MIT License](Licence.md).

Individual packages retain the licenses of their respective upstream projects.
