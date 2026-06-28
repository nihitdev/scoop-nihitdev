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

## Available Packages

| Package | Description                                            |
| ------- | ------------------------------------------------------ |
| **yoo** | A tiny developer companion for better coding sessions. |

## Updating

Update Scoop:

```powershell
scoop update
```

Update installed packages:

```powershell
scoop update yoo
```

## Repository Structure

```text
bucket/
└── yoo.json
```

Every manifest installs the latest stable release directly from GitHub Releases.

## Contributing

Found an issue with a manifest?

Feel free to open an issue or submit a pull request.

## Related Projects

* **yoo-cli** — https://github.com/nihitdev/yo-cli
* **Oxide Terminal** — https://github.com/nihitdev/rust_terminal

## License

This repository is licensed under the MIT License.

Individual packages retain the licenses of their respective upstream projects.
