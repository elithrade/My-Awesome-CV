<h1 align="center">
  <a href="https://github.com/posquit0/Awesome-CV" title="AwesomeCV Documentation">
    <img alt="AwesomeCV" src="https://github.com/posquit0/Awesome-CV/raw/master/icon.png" width="200px" height="200px" />
  </a>
  <br />
  Awesome CV
</h1>

<p align="center">
  LaTeX template for your outstanding job application
</p>

<div align="center">
  <a href="https://www.paypal.me/posquit0">
    <img alt="Donate" src="https://img.shields.io/badge/Donate-PayPal-blue.svg" />
  </a>
  <a href="https://github.com/posquit0/Awesome-CV/actions/workflows/main.yml">
    <img alt="GitHub Actions" src="https://github.com/posquit0/Awesome-CV/actions/workflows/main.yml/badge.svg" />
  </a>
  <a href="https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/resume.pdf">
    <img alt="Example Resume" src="https://img.shields.io/badge/resume-pdf-green.svg" />
  </a>
  <a href="https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/cv.pdf">
    <img alt="Example CV" src="https://img.shields.io/badge/cv-pdf-green.svg" />
  </a>
  <a href="https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/coverletter.pdf">
    <img alt="Example Coverletter" src="https://img.shields.io/badge/coverletter-pdf-green.svg" />
  </a>
</div>

<br />

## What is Awesome CV?

**Awesome CV** is LaTeX template for a **CV(Curriculum Vitae)**, **Résumé** or **Cover Letter** inspired by [Fancy CV](https://www.sharelatex.com/templates/cv-or-resume/fancy-cv). It is easy to customize your own template, especially since it is really written by a clean, semantic markup.

## Donate

Please help keep this project alive! Donations are welcome and will go towards further development of this project.

    PayPal: paypal.me/posquit0

_Thank you for your support!_

## Preview

#### Résumé

You can see [PDF](https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/resume.pdf)

|                                                                                      Page. 1                                                                                      |                                                                                      Page. 2                                                                                      |
| :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| [![Résumé](https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/resume-0.png)](https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/resume.pdf) | [![Résumé](https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/resume-1.png)](https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/resume.pdf) |

#### Cover Letter

You can see [PDF](https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/coverletter.pdf)

|                                                                                                Without Sections                                                                                                |                                                                                               With Sections                                                                                                |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| [![Cover Letter(Traditional)](https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/coverletter-0.png)](https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/coverletter.pdf) | [![Cover Letter(Awesome)](https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/coverletter-1.png)](https://raw.githubusercontent.com/posquit0/Awesome-CV/master/examples/coverletter.pdf) |

## Quick Start

- [**Edit Résumé on OverLeaf.com**](https://www.overleaf.com/latex/templates/awesome-cv/tvmzpvdjfqxp)
- [**Edit Cover Letter on OverLeaf.com**](https://www.overleaf.com/latex/templates/awesome-cv-cover-letter/pfzzjspkthbk)

**_Note:_ Above services do not guarantee up-to-date source code of Awesome CV**

## How to Use

#### Requirements

A full TeX distribution is assumed. [Various distributions for different operating systems (Windows, Mac, \*nix) are available](http://tex.stackexchange.com/q/55437) but TeX Live is recommended.
You can [install TeX from upstream](https://tex.stackexchange.com/q/1092) (recommended; most up-to-date) or use `sudo apt-get install texlive-full` if you really want that. (It's generally a few years behind.)

If you don't want to install the dependencies on your system, this can also be obtained via [Docker](https://docker.com).

#### Usage

At a command prompt, run

```bash
xelatex {your-cv}.tex
```

Or using docker:

```bash
docker run --rm -i -w "/doc" -v "$PWD":/doc ghcr.io/xu-cheng/texlive-full make
```

In either case, this should result in the creation of `{your-cv}.pdf`

## Credit

[**LaTeX**](https://www.latex-project.org) is a fantastic typesetting program that a lot of people use these days, especially the math and computer science people in academia.

[**FontAwesome6 LaTeX Package**](https://github.com/braniii/fontawesome) is a LaTeX package that provides access to the [Font Awesome 6](https://fontawesome.com/v6/icons) icon set.

[**Roboto**](https://github.com/google/roboto) is the default font on Android and ChromeOS, and the recommended font for Google’s visual language, Material Design.

[**Source Sans Pro**](https://github.com/adobe-fonts/source-sans-pro) is a set of OpenType fonts that have been designed to work well in user interface (UI) environments.

## Contact

You are free to take my `.tex` file and modify it to create your own resume. Please don't use my resume for anything else without my permission, though!

If you have any questions, feel free to join me at [`#posquit0` on Freenode](irc://irc.freenode.net/posquit0) and ask away. Click [here](https://kiwiirc.com/client/irc.freenode.net/posquit0) to connect.

Good luck!

## Maintainers

- [posquit0](https://github.com/posquit0)
- [OJFord](https://github.com/OJFord)

## See Also

- [Awesome Identity](https://github.com/posquit0/hugo-awesome-identity) - A single-page Hugo theme to introduce yourself.
