<div id="top"></div>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center">ubuntu-desktop-infra</h3>

  <p align="center">
    IaC to automate my Ubuntu 22.04 Dekstop environment setup.
    <br />
    <a href="https://github.com/jalexm8/ubuntu-desktop-infra/README.md"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/jalexm8/ubuntu-desktop-infra/README.md#installation">Installation</a>
    ·
    <a href="https://github.com/jalexm8/ubuntu-desktop-infra/issues">Report Bug</a>
    ·
    <a href="https://github.com/jalexm8/ubuntu-desktop-infra/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

This is a where I host my Ubuntu 22.04 Desktop environment setup IaC.  

Why setup Ubuntu server with IaC?:
* To quickly and safely get a new Ubuntu server device exactly how I want it set up, with minimal clicking of the mouse.
* I don't need to remember every thing I have done.

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With
* [Ansible](https://www.ansible.com/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Installation
1. Clone or download this repository to your local drive.
2. Copy `vars/example.main.yml` to `vars/main.yml` and edit.
3. Copy `example.inventory.yml` to `inventory.yml` and edit.
4. Download requirements: `ansible-galaxy install -r requirements.yaml`
5. Run `ansible-playbook playbook.yaml --ask-become-pass`.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

For now, please raise an issue.

Project Link: [https://github.com/jalexm8/ubuntu-desktop-infra](https://github.com/jalexm8/ubuntu-desktop-infra)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/jalexm8/ubuntu-desktop-infra.svg?style=for-the-badge
[contributors-url]: https://github.com/jalexm8/ubuntu-desktop-infra/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/jalexm8/ubuntu-desktop-infra.svg?style=for-the-badge
[forks-url]: https://github.com/jalexm8/ubuntu-desktop-infra/network/members
[stars-shield]: https://img.shields.io/github/stars/jalexm8/ubuntu-desktop-infra.svg?style=for-the-badge
[stars-url]: https://github.com/jalexm8/ubuntu-desktop-infra/stargazers
[issues-shield]: https://img.shields.io/github/issues/jalexm8/ubuntu-desktop-infra?color=yellow&style=for-the-badge
[issues-url]: https://github.com/jalexm8/ubuntu-desktop-infra/issues
[license-shield]: https://img.shields.io/github/license/jalexm8/ubuntu-desktop-infra.svg?style=for-the-badge
[license-url]: https://github.com/jalexm8/ubuntu-desktop-infra/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/jackalexander1008/
