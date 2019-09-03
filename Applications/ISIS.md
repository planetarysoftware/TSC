## Introduction
The ISIS software project is a collection of planetary image processing applications for data collected by a wide range of sensors.

## History & Metrics
Originating back in the 1970s, ISIS has a long history that is detailed [here](https://isis.astrogeology.usgs.gov/documents/IsisHistory/IsisHistory.html). Recently, the ISIS project has started transitioning to open source and is seeking greater community involvement.

Currently, ISIS has 34 code contributors on Github. The majority of them are employees or past employees of the Astrogeology Science Center (ASC). In the last year, a small number of non-ASC personnel have contributed to the project.

The ISIS software package has been downloaded from Anaconda cloud over a thousand times in the last year.

## Scope
The ISIS software project encompasses software used for photometric and photogramettric processing of planetary remote sensing data.

The ISIS working group will have sole responsibility and discretion over the Planetary Software
project in the following areas:

* Setting release dates.
* Release quality standards.
* Technical direction.
* Governance process and practices.
* Contribution process and practices.
* Maintaining the list of additional Collaborators.
* Development process and any coding standards.
* Mediating technical conflicts between Collaborators and Working Groups.

## Governance
The ISIS software project is currently governed by the [Astrogeology Science Center Software Management Team](https://github.com/USGS-Astrogeology/softwaremanagement) with Jay Laura(@jlaura) being the technical lead. For large changes, requests for comment are made and posted on the ISIS3 Github Wiki.

## Contributions
Contributions are proposed via pull request on Github and then reviewed by software developers at the ASC. Bug reports are posted as Github issues.

## Tools
The ISIS software project uses a variety of tools:

- The source code is hosted on Github at https://github.com/USGS-Astrogeology/ISIS3
- Releases of the source code are provided via Github https://github.com/USGS-Astrogeology/ISIS3/releases
- Bug reports and enhancements are posted on Github issues https://github.com/USGS-Astrogeology/ISIS3/issues
- Changes to the software are made via Github pull requests https://github.com/USGS-Astrogeology/ISIS3/pulls
- Some developer documentation and governance documents are posted on the Github wiki https://github.com/USGS-Astrogeology/ISIS3/wiki
- Usage questions and general software announcements are posted on a Discourse forum https://astrodiscuss.usgs.gov/
- Documentation and some training/tutorials are hosted on a website https://isis.astrogeology.usgs.gov/
- Data and test data are hosted on an rsync server run by the ASC
- Git LFS is being investigated as a way to distribute the data and test data https://github.com/USGS-Astrogeology/ISIS3/wiki/RFC4---Migration-of-ISIS-Data-to-Git
- Building is done via cmake
- Third party dependencies are managed via Anaconda environments
- Releases are built and distributed via Conda Build and Anaconda Cloud
- Automated tests are written in a combination of GNU Makefiles and GoogleTest
- Tests are run by ctest
- A Jenkins CI server is currently being worked on astroservices.usgs.gov/jenkins

## IP
The ISIS software project is licensed under the UnLicense and committed to the public domain. The one IP concern is the use of the (Kakadu)[https://kakadusoftware.com/] library for JPEG2000 support. We have the ability to exclude it in a build, but it is important for processing images from the HiRISE instrument.

## TC Members
* @jessemapel
* @jlaura
* @rbeyer
* @victoronline
* @michaelaye

## Working Groups
The ISIS software project was previously run by a three person software architecture group.

## Provisional
This project is applying for provisional inclusion and incubation in the ASC Software Organization
