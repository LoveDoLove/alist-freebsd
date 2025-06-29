<a id="readme-top"></a>

> **⚠️ DEPRECATED - This project is no longer needed and will be archived soon.**
>
> **📢 Official FreeBSD Support Available**: Alist now officially provides FreeBSD binaries in their releases. Please use the official binaries from https://github.com/AlistGo/alist/releases instead.

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<div align="center">
  <h1 align="center">~~Alist for FreeBSD~~ [DEPRECATED]</h1>

  <p align="center">
    ~~Automated builds of Alist for FreeBSD systems~~
    <br />
    <strong>⚠️ This project is deprecated. Use official Alist releases instead.</strong>
    <br />
    <br />
    <a href="https://github.com/AlistGo/alist/releases">📥 Download Official FreeBSD Binaries</a>
    ·
    <a href="https://github.com/AlistGo/alist">🏠 Official Alist Repository</a>
    ·
    <a href="https://github.com/OpenListTeam/OpenList">🔄 OpenList Alternative</a>
    ·
    <a href="#deprecation-notice">📄 Read Deprecation Notice</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#deprecation-notice">⚠️ Deprecation Notice</a></li>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#migration-guide">Migration Guide</a></li>
    <li><a href="#historical-information">Historical Information</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- DEPRECATION NOTICE -->
## ⚠️ Deprecation Notice

**This project has been deprecated and will be archived soon.**

### Why is this project deprecated?

As of June 2025, **Alist now officially provides FreeBSD binaries** in their releases. This makes this community project redundant, as users can now directly download FreeBSD binaries from the official repository.

### What should you do?

1. **Download official binaries**: Get FreeBSD binaries directly from https://github.com/AlistGo/alist/releases
2. **Available architectures**: The official releases include:
   - `alist-freebsd-amd64.tar.gz`
   - `alist-freebsd-arm64.tar.gz` 
   - `alist-freebsd-i386.tar.gz`
3. **Same functionality**: The official binaries provide the same features and are maintained by the core Alist team
4. **Alternative option**: If you prefer an open-source fork, consider [OpenList](https://github.com/OpenListTeam/OpenList) - a community-driven alternative to Alist

### Timeline

- **Current**: This repository is deprecated but remains accessible
- **Soon**: This repository will be archived and made read-only
- **No new releases**: No further builds will be made from this repository

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MIGRATION GUIDE -->
## Migration Guide

If you're currently using binaries from this repository, here's how to migrate to the official releases:

### 1. Download Official Binary

```bash
# Example for FreeBSD amd64
wget https://github.com/AlistGo/alist/releases/latest/download/alist-freebsd-amd64.tar.gz
tar -xzf alist-freebsd-amd64.tar.gz
chmod +x alist
```

### 2. Your existing configuration and data will work as-is

The official binaries are fully compatible with your existing Alist installation. No migration of data or configuration is needed.

### 3. Update your automation

If you have scripts that download from this repository, update them to use the official releases:

```bash
# Old (this repository)
wget https://github.com/LoveDoLove/alist-freebsd/releases/latest/download/alist

# New (official repository)
wget https://github.com/AlistGo/alist/releases/latest/download/alist-freebsd-amd64.tar.gz

# Alternative (OpenList - community fork)
# Check https://github.com/OpenListTeam/OpenList for FreeBSD releases
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- HISTORICAL INFORMATION -->
## Historical Information

*The following sections are preserved for historical reference only.*

### About The Project (Historical)

This project provided automated daily builds of [Alist](https://github.com/alist-org/alist) for FreeBSD systems. Alist is a file list/WebDAV program that supports multiple storage providers, powered by Gin and Solidjs.

~~While Alist officially supports Linux, Windows, and macOS, this project extends that support to FreeBSD systems by providing ready-to-use binaries compiled specifically for FreeBSD.~~ 

**Update**: Alist now officially supports FreeBSD in their releases.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Features (Historical)

~~These FreeBSD builds include all the features of the original Alist project:~~

The official FreeBSD builds include all the features of Alist:

* **Multiple storage support**:
  * Local storage
  * Cloud providers (OneDrive, Google Drive, Dropbox, etc.)
  * Object storage (S3, Azure Blob Storage, etc.)
  * Network protocols (FTP, SFTP, SMB, WebDAV)
  * And [many more](https://alist.nn.ci/guide/drivers/)

* **Easy deployment** - Download and run the binary
* **File previews** - PDF, markdown, code, plain text, images, video, audio, and more
* **Office document preview** - docx, pptx, xlsx, and more
* **Protected routes** - Password protection and authentication
* **WebDAV support** - Mount as a network drive
* **Dark mode and i18n**
* **File operations** - Upload, delete, mkdir, rename, move, and copy
* **Offline download**
* **Multi-thread downloading acceleration**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Getting Started (Historical - Use Official Releases Instead)

~~Getting started with Alist on FreeBSD is simple:~~

**Please use the official releases from https://github.com/AlistGo/alist/releases instead.**

#### Prerequisites

* FreeBSD 14.x (other versions may work but are not tested)

#### Installation (Historical - Deprecated)

~~1. Download the latest release from the [Releases page](https://github.com/LoveDoLove/alist-freebsd/releases/latest)~~

**Use official releases instead:**

1. Download from the official repository:
   ```sh
   wget https://github.com/AlistGo/alist/releases/latest/download/alist-freebsd-amd64.tar.gz
   tar -xzf alist-freebsd-amd64.tar.gz
   ```
2. Make the binary executable:
   ```sh
   chmod +x alist
   ```
3. Run Alist:
   ```sh
   ./alist server
   ```
4. Access the web UI at http://localhost:5244 and use the default credentials:
   * Username: `admin`
   * Password: Check the console output for the random password

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Usage (Historical)

Once Alist is running, you can:

1. Add storage providers in the admin panel
2. Browse and manage files through the web UI
3. Mount as a WebDAV drive for convenient access
4. Share files and folders with others

For more detailed usage information, please refer to the [Official Alist Documentation](https://alist.nn.ci/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Automated Builds (Historical - Discontinued)

~~This project uses GitHub Actions to automatically build Alist for FreeBSD every day. The build process:

1. Sets up a FreeBSD environment using the official base system
2. Fetches the latest Alist source code
3. Compiles it specifically for FreeBSD
4. Publishes the binary as a GitHub release

You can always find the latest build in the [Releases section](https://github.com/LoveDoLove/alist-freebsd/releases/latest).~~

**This build process has been discontinued. Use official FreeBSD releases from the main Alist repository.**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Roadmap (Historical - Discontinued)

- [x] ~~Setup automated daily builds~~
- [x] ~~Add FreeBSD 14.x support~~
- [ ] ~~Add CI testing~~ (No longer relevant)
- [ ] ~~Create FreeBSD port/package~~ (May be created by FreeBSD community)
- [ ] ~~Add systemd/rc.d service file~~ (No longer relevant for this project)

**This roadmap is discontinued. Feature requests should be directed to the official Alist repository.**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Contributing (Historical - No Longer Accepting Contributions)

~~Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.~~

**This project is deprecated and no longer accepting contributions.**

For contributing to Alist itself, please visit the [official Alist repository](https://github.com/AlistGo/alist).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### License (Historical)

This build project was distributed under the MIT License. See `LICENSE` for more information.

Note: Alist itself is licensed under AGPL-3.0.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Sponsorship (Historical)

This project was proudly supported by [ZMTO](https://www.zmto.com) as part of their open-source VPS program. We extend our sincere gratitude to ZMTO for their valuable resources and commitment to empowering open-source innovation.

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Alist Project](https://github.com/alist-org/alist) - The original Alist software and now official FreeBSD support
* [OpenList](https://github.com/OpenListTeam/OpenList) - Community-driven alternative fork of Alist
* [FreeBSD](https://www.freebsd.org/) - The operating system this project historically targeted
* [GitHub Actions](https://github.com/features/actions) - For the automated build pipeline that was used
* **Community**: Thanks to everyone who used and supported this project during its active period
* **Alist Team**: For eventually adding official FreeBSD support, making this project obsolete in the best possible way

**🎉 Mission Accomplished**: This project succeeded in its goal by encouraging official FreeBSD support in the main Alist project!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/LoveDoLove/alist-freebsd.svg?style=for-the-badge
[contributors-url]: https://github.com/LoveDoLove/alist-freebsd/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/LoveDoLove/alist-freebsd.svg?style=for-the-badge
[forks-url]: https://github.com/LoveDoLove/alist-freebsd/network/members
[stars-shield]: https://img.shields.io/github/stars/LoveDoLove/alist-freebsd.svg?style=for-the-badge
[stars-url]: https://github.com/LoveDoLove/alist-freebsd/stargazers
[issues-shield]: https://img.shields.io/github/issues/LoveDoLove/alist-freebsd.svg?style=for-the-badge
[issues-url]: https://github.com/LoveDoLove/alist-freebsd/issues
[license-shield]: https://img.shields.io/github/license/LoveDoLove/alist-freebsd.svg?style=for-the-badge
[license-url]: https://github.com/LoveDoLove/alist-freebsd/blob/main/LICENSE
