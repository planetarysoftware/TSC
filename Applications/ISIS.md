## Introduction
The ISIS software project is a collection of planetary image processing applications for data collected by a wide range of sensors. The source code and issue tracker are hosted on [GitHub](https://github.com/USGS-Astrogeology/ISIS3) and it's documentation is hosted on a separate [website](https://isis.astrogeology.usgs.gov/).

## History & Outlook
Originating in the 1970s, ISIS has a long history that is detailed [here](https://isis.astrogeology.usgs.gov/documents/IsisHistory/IsisHistory.html).

The USGS Astrogeology Science Center (ASC) has been the owner and maintainer of ISIS. Recently, the ASC has started transitioning the ISIS software project to open source and is seeking greater community involvement. A [technical committee](https://github.com/USGS-Astrogeology/ISIS_TC) has been stood up and governance of the project is being gradually transferred from the ASC to the ISIS technical committee (ISIS TC).

## Metrics

Currently, the majority of code contributors are employees or past employees of the Astrogeology Science Center (ASC). In the last year, a small number of non-ASC personnel have contributed to the project. Issues and documentation have been contributed by the broader user community.

## Scope
The ISIS software project encompasses software used for photometric and photogramettric processing of planetary remote sensing data.

The ISIS technical committee will have sole responsibility and discretion over the Planetary Software
project in the following areas:

* Release processes (including setting release cadence and release quality standards).
* Project governance and process (including this policy).
* Location of the official software repository.
* Conduct guidelines.
* Maintaining the list of contributors.
* Contribution guidelines (including coding and testing standards).
* Mediating technical conflicts between Collaborators.

## Governance
The governance of the ISIS Software project is described in the [ISIS TC Charter](https://github.com/USGS-Astrogeology/ISIS_TC/blob/master/TC-Charter.md).

## Contributions, Code of Conduct
Contributions are proposed via pull request on GitHub and then reviewed by contributors with commit permissions. Bug reports are posted as GitHub issues. For large changes, requests for comment are posted on the GitHub wiki.

The contributing guidelines are in the repo's [CONTRIBUTING.MD](https://github.com/USGS-Astrogeology/ISIS3/blob/dev/CONTRIBUTING.md).

The project uses the Planetary Software TSC code of conduct.

## Tools
The ISIS software project uses a variety of tools:

- The source code is hosted on GitHub at https://github.com/USGS-Astrogeology/ISIS3
- Releases of the source code are provided via GitHub https://github.com/USGS-Astrogeology/ISIS3/releases
- Bug reports and enhancements are posted on GitHub issues https://github.com/USGS-Astrogeology/ISIS3/issues
- Changes to the software are made via GitHub pull requests https://github.com/USGS-Astrogeology/ISIS3/pulls
- Developer documentation and some user documentation are posted on the GitHub wiki https://github.com/USGS-Astrogeology/ISIS3/wiki
- Usage questions and general software announcements are posted on a Discourse forum https://astrodiscuss.usgs.gov/
- The full API and app documentation is hosted on a website https://isis.astrogeology.usgs.gov/
- Data and test data are hosted on an rsync server run by the ASC
- Building is done via cmake
- Third party dependencies are managed via Anaconda environments
- Releases are built and distributed via Conda Build and Anaconda Cloud
- Automated tests are written in a combination of GNU Makefiles and GoogleTest
- Tests are run by ctest
- CI is run on a Jenkins server hosted by the ASC and can be viewed at https://astroservices.usgs.gov/jenkins/

## IP
The ISIS software project is currently licensed under the Creative Commons 0 license. The one IP concern is the use of the [Kakadu](https://kakadusoftware.com/) library for JPEG2000 support. It can be excluded from the build, but it is important for processing images from the HiRISE instrument. The ASC purchases a license to distribute the compiled library so that it is available with all releases, but other developers will need their own license to compile the software themselves with Kakadu.

## TC Members
- [Andrew Annex](https://github.com/AndrewAnnex)
- [Michael Aye](https://github.com/michaelaye)
- [Kris Becker](https://github.com/KrisBecker)
- [Kristin Berry](https://github.com/kberryUSGS)
- [Ross Beyer](https://github.com/rbeyer)
- [Mario D'Amore](https://github.com/kidpixo)
- [Audrie Fennema](https://github.com/audiefen)
- [Robin Fergason](https://github.com/rfergason)
- [Jay Laura](https://github.com/jlaura)
- [Jesse Mapel](https://github.com/jessemapel)
- [Stuart Robbins](https://github.com/astrostu)
- [Stuart Sides](https://github.com/scsides)
- [Victor Silva](https://github.com/victoronline)

## Working Groups
The ISIS software project was previously run by a three person software architecture group. Currently there are no formal working groups.
