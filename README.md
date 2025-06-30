<a id="readme-top"></a>

<!-- DEPRECATION BANNER -->
> **⚠️ DEPRECATED - This project is no longer maintained and will be archived soon.**
>
> **Official FreeBSD Support Available:** Alist now provides official FreeBSD binaries. Please use the official releases from [AlistGo/alist](https://github.com/AlistGo/alist/releases).

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<div align="center">
  <h1 align="center">Alist for FreeBSD <br> <span style="color:red;">[DEPRECATED]</span></h1>
  <p align="center">
    <strong>Automated builds of Alist for FreeBSD systems (historical)</strong><br />
    <br />
    <a href="https://github.com/AlistGo/alist/releases"><strong>Download Official FreeBSD Binaries »</strong></a>
    ·
    <a href="https://github.com/AlistGo/alist">Official Alist Repository</a>
    ·
    <a href="https://github.com/OpenListTeam/OpenList">OpenList Alternative</a>
    ·
    <a href="#deprecation-notice">Read Deprecation Notice</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#deprecation-notice">Deprecation Notice</a></li>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#migration-guide">Migration Guide</a></li>
    <li><a href="#historical-information">Historical Information</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## ⚠️ Deprecation Notice

**This project is deprecated and will be archived soon.**

- Alist now provides official FreeBSD binaries in their releases.
- This repository is kept for historical reference only.
- No new builds or contributions will be accepted.

**Please use the official binaries from [AlistGo/alist/releases](https://github.com/AlistGo/alist/releases).**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## About The Project

This repository provided automated daily builds of [Alist](https://github.com/alist-org/alist) for FreeBSD systems before official support was available. Alist is a file list/WebDAV program supporting multiple storage providers, powered by Gin and Solidjs.

- **Purpose:** Fill the gap for FreeBSD users before official support.
- **Status:** Obsolete, as official FreeBSD binaries are now available.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Migration Guide

If you previously used binaries from this repository, migrate to the official releases as follows:

### 1. Download Official Binary

```sh
# Example for FreeBSD amd64
wget https://github.com/AlistGo/alist/releases/latest/download/alist-freebsd-amd64.tar.gz
tar -xzf alist-freebsd-amd64.tar.gz
chmod +x alist
```

### 2. Use Your Existing Configuration

The official binaries are fully compatible with your existing Alist configuration and data.

### 3. Update Automation Scripts

Update any scripts to use the new official download URLs.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Historical Information

### Features (Historical)
- Multiple storage support (local, cloud, object, network protocols)
- Easy deployment (download and run)
- File previews (PDF, markdown, code, images, video, audio)
- Office document preview
- Protected routes and authentication
- WebDAV support
- File operations (upload, delete, mkdir, rename, move, copy)
- Offline download, multi-thread acceleration

### Automated Builds (Historical)
- Used GitHub Actions to build Alist for FreeBSD daily
- Published binaries as GitHub releases
- **Discontinued:** Use official FreeBSD releases from the main Alist repository

### Contributing (Historical)
- This project is no longer accepting contributions.
- For contributions, visit the [official Alist repository](https://github.com/AlistGo/alist).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

This build project is licensed under the MIT License. See `LICENSE` for details.

Note: Alist itself is licensed under AGPL-3.0.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments

- [Alist Project](https://github.com/alist-org/alist) - The original software and now official FreeBSD support
- [OpenList](https://github.com/OpenListTeam/OpenList) - Community-driven alternative fork
- [FreeBSD](https://www.freebsd.org/) - The OS this project targeted
- [GitHub Actions](https://github.com/features/actions) - For the automated build pipeline
- **Community:** Thanks to everyone who used and supported this project
- **Alist Team:** For adding official FreeBSD support

**🎉 Mission Accomplished:** This project succeeded by encouraging official FreeBSD support in the main Alist project!

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
