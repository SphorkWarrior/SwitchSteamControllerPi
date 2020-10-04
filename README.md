# SwitchSteamControllerPi
Steam Controller connection to Nintendo Switch via Raspberry Pi

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/SphorkWarrior/SwitchSteamControllerPi">
    <img src="images/logo.jpg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">SwitchSteamControllerPi</h3>

  <p align="center">
    Controling the switch with a Steam Controller via a Raspberry Pi 0
    <br />
    <a href="https://github.com/SphorkWarrior/SwitchSteamControllerPi"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/SphorkWarrior/SwitchSteamControllerPi">View Demo</a>
    ·
    <a href="https://github.com/SphorkWarrior/SwitchSteamControllerPi/issues">Report Bug</a>
    ·
    <a href="https://github.com/SphorkWarrior/SwitchSteamControllerPi/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Usage](#usage)
* [Roadmap](#roadmap)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

[![Switch Steam Controller Pi Shot][product-screenshot]](https://example.com)

This is my attempt at connecint a Steam Controller to the Nintendo Switch. This has been done before a few times, and you can find the examples if "you google good". But the only well documented attempt replaces the Steam conroller's firmware. The [Open Steam Controller](https://github.com/greggersaurus/OpenSteamController) is cool and all, but requires firmware updating. So switching back and forth from Steam Link to Switch can get tedious. SO, My plan is to use the Raspberry Pi as a middleman to "translate" the Steam Controller input, to output to a Nintendo Switch.
I am a genius, but i did not write all the code myself. In fact I did not write most of it. I simply combined a few projects and added some connections. The projects used by this are:
* [Joy Control - Bluetooth Switch Controller](https://github.com/mart1nro/joycontrol)
* [Joy Control w/Macros](https://github.com/marcus-stevenson/joycontrol-ms)
* [Steam Controller Standalone Driver](https://github.com/ynsta/steamcontroller)



### Built With

* [Python]()
* [Raspberry Pi Zero W]()
* [Steam Controller]()
* [Nintendo Swith]()
* [Eclipse]()



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

The physical prereqs are:
* Nintendo Switch
* Steam Controller
* Raspberry Pi 
   (Alternately: any other Bluetooth capable computer that can run Python should work)
   
Sofware prereqs:
* Python

<!-- * npm
```sh
npm install npm@latest -g
```
-->

### Installation

I will let you know once I get this far, but basic steps should be:
1. Clone the repo to the Raspberry Pi
```sh
git clone https://github.com/SphorkWarrior/SwitchSteamControllerPi.git
```
2. (Optional) Add startup script to run on startup
3. Connect Steam Controller to Raspberry Pi (Direct USB or Wireless Dongle)
4. Connect to Nintendo switch
<!--
2. Install NPM packages
```sh
npm install
```
-->


<!-- USAGE EXAMPLES -->
<!--
## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://example.com)_
-->


<!-- ROADMAP -->
## Roadmap

See the [open issues](https://github.com/SphorkWarrior/SwitchSteamControllerPi/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the GNU License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Marty - [@SphorkWarrior](https://twitter.com/SphorkWarrior) - SphorkWarrior@gmail.com 

Project Link: [https://github.com/SphorkWarrior/SwitchSteamControllerPi](https://github.com/SphorkWarrior/SwitchSteamControllerPi)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Joy Control - Bluetooth Switch Controller](https://github.com/mart1nro/joycontrol)
* [Steam Controller Standalone Driver](https://github.com/ynsta/steamcontroller)
* [Readme Template](https://github.com/othneildrew/Best-README-Template/blob/master/BLANK_README.md)
* [Headless Pi](https://www.tomshardware.com/reviews/raspberry-pi-headless-setup-how-to,6028.html)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/SphorkWarrior/repo.svg?style=flat-square
[contributors-url]: https://github.com/SphorkWarrior/repo/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/SphorkWarrior/repo.svg?style=flat-square
[forks-url]: https://github.com/SphorkWarrior/repo/network/members
[stars-shield]: https://img.shields.io/github/stars/SphorkWarrior/repo.svg?style=flat-square
[stars-url]: https://github.com/SphorkWarrior/repo/stargazers
[issues-shield]: https://img.shields.io/github/issues/SphorkWarrior/repo.svg?style=flat-square
[issues-url]: https://github.com/SphorkWarrior/repo/issues
[license-shield]: https://img.shields.io/github/license/SphorkWarrior/repo.svg?style=flat-square
[license-url]: https://github.com/SphorkWarrior/repo/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/SphorkWarrior
[product-screenshot]: images/screenshot.png
[joy-control]: https://github.com/mart1nro/joycontrol
[steam-controller-driver]: https://github.com/ynsta/steamcontroller