<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<br />
<div align="center">
  <h3 align="center">alist-freebsd</h3>
  <p align="center">
    FreeBSD build scripts and patches for <a href="https://github.com/alist-org/alist">alist</a>.<br />
    <a href="#getting-started"><strong>Get Started »</strong></a>
    <br /><br />
    <a href="#usage">Usage</a>
    &middot;
    <a href="#contributing">Contributing</a>
    &middot;
    <a href="#license">License</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project

This project provides scripts and configuration to build the [alist](https://github.com/alist-org/alist) file listing and sharing service for FreeBSD, including cross-compilation support and environment setup.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Features

- FreeBSD cross-compilation support for alist
- Automated build script (`build.sh`) for easy setup
- GitHub Actions workflows for CI and release automation
- MIT Licensed
- FreeBSD-specific patches and integration

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Built With

- [Go](https://golang.org/) (latest recommended)
- [Clang](https://clang.llvm.org/) (with FreeBSD cross-compilation support)
- [alist](https://github.com/alist-org/alist)
- [GitHub Actions](https://github.com/features/actions)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

To build alist for FreeBSD, ensure you have Go and Clang with FreeBSD target support installed.

### Prerequisites

- Go (latest recommended)
- Clang with FreeBSD cross-compilation support
- wget, git, bash

### Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/LoveDoLove/alist-freebsd.git
   cd alist-freebsd
   ```
2. Run the build script:
   ```sh
   ./build.sh
   ```

The script will download the latest alist source and web assets, then build a FreeBSD-compatible binary in the project directory.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

After building, the `alist` binary will be available in the project directory. Deploy or use as needed on your FreeBSD system.

- For configuration and advanced usage, refer to the upstream [alist documentation](https://github.com/alist-org/alist#readme).
- FreeBSD-specific patches and scripts are included for seamless integration.
- Example: Copy the binary to your FreeBSD server and follow upstream setup instructions.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Roadmap

- [x] FreeBSD build support
- [x] Automated release workflow
- [x] Additional FreeBSD-specific patches
- [ ] Continuous integration for FreeBSD
- [ ] More detailed usage guides

See the [open issues](https://github.com/LoveDoLove/alist-freebsd/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

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

## License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

LoveDoLove - [GitHub](https://github.com/LoveDoLove)

Project Link: [https://github.com/LoveDoLove/alist-freebsd](https://github.com/LoveDoLove/alist-freebsd)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments

- [alist](https://github.com/alist-org/alist)
- [Choose an Open Source License](https://choosealicense.com)
- [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
- [Img Shields](https://shields.io)
- <!-- ZMTO Acknowledgment -->
  > **Note:** This project is supported by [ZMTO](https://www.zmto.com) as part of their open-source VPS program. Special thanks to ZMTO for empowering open-source innovation!

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
