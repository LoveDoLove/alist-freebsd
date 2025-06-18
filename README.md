<a id="readme-top"></a>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- PROJECT LOGO -->
<div align="center">
  <h1 align="center">Alist for FreeBSD</h1>

  <p align="center">
    Automated builds of Alist for FreeBSD systems
    <br />
    <a href="#about-the-project"><strong>Learn More »</strong></a>
    <br />
    <br />
    <a href="https://github.com/LoveDoLove/alist-freebsd/releases/latest">Download Latest</a>
    ·
    <a href="https://github.com/LoveDoLove/alist-freebsd/issues">Report Bug</a>
    ·
    <a href="https://github.com/LoveDoLove/alist-freebsd/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#automated-builds">Automated Builds</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## About The Project

This project provides automated daily builds of [Alist](https://github.com/alist-org/alist) for FreeBSD systems. Alist is a file list/WebDAV program that supports multiple storage providers, powered by Gin and Solidjs.

While Alist officially supports Linux, Windows, and macOS, this project extends that support to FreeBSD systems by providing ready-to-use binaries compiled specifically for FreeBSD.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Features

These FreeBSD builds include all the features of the original Alist project:

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

<!-- GETTING STARTED -->
## Getting Started

Getting started with Alist on FreeBSD is simple:

### Prerequisites

* FreeBSD 14.x (other versions may work but are not tested)

### Installation

1. Download the latest release from the [Releases page](https://github.com/LoveDoLove/alist-freebsd/releases/latest)
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

<!-- USAGE EXAMPLES -->
## Usage

Once Alist is running, you can:

1. Add storage providers in the admin panel
2. Browse and manage files through the web UI
3. Mount as a WebDAV drive for convenient access
4. Share files and folders with others

For more detailed usage information, please refer to the [Official Alist Documentation](https://alist.nn.ci/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- AUTOMATED BUILDS -->
## Automated Builds

This project uses GitHub Actions to automatically build Alist for FreeBSD every day. The build process:

1. Sets up a FreeBSD environment using the official base system
2. Fetches the latest Alist source code
3. Compiles it specifically for FreeBSD
4. Publishes the binary as a GitHub release

You can always find the latest build in the [Releases section](https://github.com/LoveDoLove/alist-freebsd/releases/latest).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Setup automated daily builds
- [x] Add FreeBSD 14.x support
- [ ] Add CI testing
- [ ] Create FreeBSD port/package
- [ ] Add systemd/rc.d service file

See the [open issues](https://github.com/LoveDoLove/alist-freebsd/issues) for a full list of proposed features and known issues.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.

Note: While this build project is MIT licensed, Alist itself is licensed under AGPL-3.0.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Sponsorship

This project is proudly supported by [ZMTO](https://www.zmto.com) as part of their open-source VPS program. We extend our sincere gratitude to ZMTO for their valuable resources and commitment to empowering open-source innovation.

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Alist Project](https://github.com/alist-org/alist) - The original Alist software
* [FreeBSD](https://www.freebsd.org/) - The operating system this build targets
* [GitHub Actions](https://github.com/features/actions) - For the automated build pipeline

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
