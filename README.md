# Quick Shell
Spawn a shell by creating a tunnel to the container running GitHub Actions workflow

## Usage
- Fork this repo
- Click on `Actions` tab
- Select `Spawn a shell` workflow
- Click on `Run workflow` button
- Choose Runner
- Choose Authenticated Access
  - Checked: Tunnel can be accessed only from the device having SSH access to your GitHub account.
  - Unchecked: Tunnel can be accessed from any device and also from the browser.
- Click on `Run workflow` button
- Check logs for access url

NOTE: If you see a blank shell, press `q` key.

# Runners
- Source: [GitHub Docs](https://docs.github.com/en/actions/using-github-hosted-runners/using-github-hosted-runners/about-github-hosted-runners#standard-github-hosted-runners-for-public-repositories)
- Updated: Nov 2024 by [Jameel Kaisar](https://github.com/jameelkaisar)

| Runner | Operating System | Architecture | Processor (CPU) | Memory (RAM) | Storage (SSD) |
| - | - | - | - | - | - |
| [ubuntu-24.04](https://github.com/actions/runner-images/blob/main/images/ubuntu/Ubuntu2404-Readme.md) | Ubuntu | x86_64 | 4 | 16 GB | 14 GB |
| [ubuntu-22.04](https://github.com/actions/runner-images/blob/main/images/ubuntu/Ubuntu2204-Readme.md) | Ubuntu | x86_64 | 4 | 16 GB | 14 GB |
| [ubuntu-20.04](https://github.com/actions/runner-images/blob/main/images/ubuntu/Ubuntu2004-Readme.md) | Ubuntu | x86_64 | 4 | 16 GB | 14 GB |
| [macos-15](https://github.com/actions/runner-images/blob/main/images/macos/macos-15-Readme.md) | MacOS | arm64 | 3 | 7 GB | 14 GB |
| [macos-14](https://github.com/actions/runner-images/blob/main/images/macos/macos-14-Readme.md) | MacOS | arm64 | 3 | 7 GB | 14 GB |
| [macos-13](https://github.com/actions/runner-images/blob/main/images/macos/macos-13-Readme.md) | MacOS | x86_64 | 4 | 14 GB | 14 GB |
| [macos-12](https://github.com/actions/runner-images/blob/main/images/macos/macos-12-Readme.md) | MacOS | x86_64 | 3 | 14 GB | 14 GB |
| [windows-2022](https://github.com/actions/runner-images/blob/main/images/windows/Windows2022-Readme.md) | Windows | x86_64 | 4 | 16 GB | 14 GB |
| [windows-2019](https://github.com/actions/runner-images/blob/main/images/windows/Windows2019-Readme.md) | Windows | x86_64 | 4 | 16 GB | 14 GB |
