<div id="top"></div>

<div align="center">

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/MidasTouch-MT/MidasTouch-MT.github.io">
    <img src="/siteicon.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Midas Touch - GitDoc</h3>

  <p align="center">
    Midas Touch - GitDoc is an open-source documentation website hosted on GitHub Pages or potentially [gitdoc.org](https://www.gitdoc.org). 
    It's distributed under the MIT license in `/License.txt`. 
    We pride ourrselves for a FOSS intiative by only using open-sourced libraries or code.
    <br />
    <a href="https://github.com/MidasTouch-MT/MidasTouch-MT.github.io"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/MidasTouch-MT/MidasTouch-MT.github.io">View Demo</a>
    ·
    <a href="https://github.com/MidasTouch-MT/MidasTouch-MT.github.io/issues">Report Bug</a>
    ·
    <a href="https://github.com/MidasTouch-MT/MidasTouch-MT.github.io/issues">Request Feature</a>
  </p>
</div>


<div align="left">

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
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![GitDoc][product-screenshot]](https://midastouch-mt.github.io)

<p align="right">(<a href="#top">Back to Top</a>)</p>



### Built With

* [Jekyll](https://jekyllrb.com/)
* [Jekyll Feed](https://github.com/jekyll/jekyll-feed)
* [Jekyll SEO Tag](https://github.com/jekyll/jekyll-seo-tag)
* [Jekyll Sitemap](https://github.com/jekyll/jekyll-sitemap)
* [Jekyll Watch](https://github.com/jekyll/jekyll-watch)
* [Jekyll SASS Converter](https://github.com/jekyll/jekyll-sass-converter)
* [SASS](https://sass-lang.com/)

<p align="right">(<a href="#top">Back to Top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

Use the following instructions to setup the project locally. 
Linux, Windows, or macOS are the preferred operating systems for these instructions.

### Prerequisites

The software required to install the respository are: 
A terminal, Ruby, and Jekyll. You may also optionally install the SASS compiler if CSS is preferred.

<br>

* Terminal install for Linux, Windows, or macOS:
~~~https
https://git-scm.com/downloads
~~~

<br>

* Ruby installation for Linux, Windows, or macOS

Check for any existing Ruby versions
~~~sh
ruby -v
~~~
If there are none follow these instructions:
~~~https
https://www.ruby-lang.org/en/documentation/installation
~~~

<br>

Jekyll installation for Linux, Windows, or macOS
(Ruby, Gems, GCC, and MAKE are required)

Install Jekyll via Bundler Gems with Linux, Windows or macOS
~~~sh
gem install jekyll bundler
~~~

<br>

* SASS installation for Linux, Windows, or macOS

Node.js installation for SASS on any operating system
~~~sh
npm install npm@latest -g
~~~

Chocolatey installation for SASS with Windows
~~~sh
choco install sass
~~~

Homebrew installation for SASS with Linux or macOS
~~~sh
brew install sass/sass/sass
~~~

#### Troubleshooting

* Visit [jekyllrb.com](https://jekyllrb.com/docs) for how to install Jekyll and its dependencies.
* Visit [ruby-lang.org](https://www.ruby-lang.org/en/documentation/installation) for how to install Ruby via command line.
* Visit [sass-lang.com](https://sass-lang.com/install) for how to install via differing applications.

### Installation

1. Follow the Prerequisites
2. Clone the repo via SSH
   ~~~sh
   git clone git@github.com:MidasTouch-MT/MidasTouch-MT.github.io.git
   ~~~

   Clone the repo via HTTPS
   ~~~sh
   git clone https://github.com/MidasTouch-MT/MidasTouch-MT.github.io.git
   ~~~

3. Add your site and author details in `_config.yml`.

4. Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

5. Midas Touch - GitDoc is already optimised for adding, updating and removing documentation pages in CloudCannon.
Add, update or remove a documentation page in the *Documentation* collection.

* Change the category of a documentation page to move it to another section in the navigation.
* Documentation pages are organised in the navigation by category, with URLs based on the path inside the `_docs` folder.

6. Edit the Changelog

* Add, update or remove change log entries from your posts.
* Tag entries as minor or major in the front matter.

7. Edit the Search box

* Add `excluded_in_search: true` to any documentation page's front matter to exclude that page in the search results.

8. Edit the Navigation bar

* Change `site.show_full_navigation` to control all or only the current navigation group being open.

<p align="right">(<a href="#top">Back to Top</a>)</p>


<!-- USAGE EXAMPLES -->
## Usage

GitDoc is an automated documentation builder that uses Jekyll to help developers efficiently write documentation for maximum compatability across devices and operating systems.
We use embeds, subdomains, and paths to tailor and build documentation configured for each developer's needs.
Our team proudly stands with the open-source community to build serious documentation.
GitDoc has been tailored for Android, ChromeOS, Linux, iOS, iPadOS, Windows, and macOS.

<p align="right">(<a href="#top">Back to Top</a>)</p>



<!-- ROADMAP -->
## Roadmap

The following are estimates of our timetable:
- [9/1/2022] Automatic Building with UpTimeRobot for Jekyll
- [1/1/2023] Operating System Wide Compatability
- [12/1/2023] Non-profit recognition for our page building system
    - [6/1/2023] Break even point for our project

See the [open issues](https://github.com/MidasTouch-MT/MidasTouch-MT.github.io/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">Back to Top</a>)</p>



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

<p align="right">(<a href="#top">Back to Top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.
`README.md` is also published under the MIT license, however under a different copyright in `/README-LICENSE.txt`.

<p align="right">(<a href="#top">Back to Top</a>)</p>



<!-- CONTACT -->
## Contact

MidasTouch-MT - midastouch@duck.com

Project Link: [https://github.com/MidasTouch-MT/MidasTouch-MT.github.io](https://github.com/MidasTouch-MT/MidasTouch-MT.github.io)

<p align="right">(<a href="#top">Back to Top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Othneil Drew for the Best README Template](https://github.com/othneildrew/Best-README-Template)
* [CloudCannon for the Edition Jekyll Template](https://github.com/CloudCannon/edition-jekyll-template)
* [Shields.io for the README.md headers](https://shields.io)
* [MidasTouch-MT for curating this project with ❤️](https://github.com/MidasTouch-MT)

<p align="right">(<a href="#top">Back to Top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/MidasTouch-MT/MidasTouch-MT.github.io.svg?style=for-the-badge
[contributors-url]: https://github.com/MidasTouch-MT/MidasTouch-MT.github.io/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/MidasTouch-MT/MidasTouch-MT.github.io.svg?style=for-the-badge
[forks-url]: https://github.com/MidasTouch-MT/MidasTouch-MT.github.io/network/members
[stars-shield]: https://img.shields.io/github/stars/MidasTouch-MT/MidasTouch-MT.github.io.svg?style=for-the-badge
[stars-url]: https://github.com/MidasTouch-MT/MidasTouch-MT.github.io/stargazers
[issues-shield]: https://img.shields.io/github/issues/MidasTouch-MT/MidasTouch-MT.github.io.svg?style=for-the-badge
[issues-url]: https://github.com/MidasTouch-MT/MidasTouch-MT.github.io/issues
[license-shield]: https://img.shields.io/github/license/MidasTouch-MT/MidasTouch-MT.github.io.svg?style=for-the-badge
[license-url]: https://github.com/MidasTouch-MT/MidasTouch-MT.github.io/blob/master/LICENSE.txt
[product-screenshot]: images/_screenshot.png
