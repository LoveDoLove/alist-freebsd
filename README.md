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
    FreeBSD build scripts and patches for <a href="https://github.com/alist-org/alist">alist</a>.
    <br />
    <a href="#getting-started"><strong>Get Started »</strong></a>
    <br />
    <br />
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

- Focused on FreeBSD compatibility
- Includes build script (`build.sh`) for easy setup
- MIT Licensed

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

To build alist for FreeBSD, ensure you have Go and Clang with FreeBSD target support installed.

### Prerequisites

- Go (latest recommended)
- Clang with FreeBSD cross-compilation support

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

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

After building, the `alist` binary will be available in the project directory. Deploy or use as needed on your FreeBSD system.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Roadmap

- [x] FreeBSD build support
- [x] Automated release workflow
- [x] Additional FreeBSD-specific patches

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

Contributions are welcome! Please fork the repo and submit a pull request. For major changes, open an issue first to discuss what you would like to change.

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
