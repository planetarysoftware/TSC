# PlanetaryPy

## Introduction

PlanetaryPy will be a community effort to develop a core package
for planetary science in Python and foster interoperability between
Python planetary science packages.

In order to facilitate that goal, the [PlanetaryPy
TC](https://github.com/planetarypy/TC) is applying to become a
Top-Level Project in the Planetary Software Organization.


## History & Outlook

The concept of PlanetaryPy has existed since at least 2015.  Austin
Godber, and other developers created the planetarypy GitHub
organization in 2015, and began maintaining several repositories
there.  There was no governance model, and no central "planetarypy"
package.  Many of these original developers moved on from planetary
sciences, and active maintenance of these repositories waned.

In 2019, there was renewed interest by a new group of individuals
(now the members of the PlanetaryPy TC) to create something for
planetary sciences that was akin to the Astropy Project for astronomy.

At the Planetary Data Workshop in June, 2019, we found that there
was a real interest in the Planetary Sciences technical community
for an active planetary Python resource. Many people pointed to the
Astropy Project as a possible analog or goal.  The code currently
within the GitHub PlanetaryPy organization is a great starting
point, and the naming is right.

The goal is to take that existing codebase, plus a solid governance
model taken from the Planetary Software Organization, and eventually
work to build something that is as robust as the Astropy Project.
We are just beginning this process, and the intent is to slowly and
methodically build towards a healthy Python ecosystem for planetary
sciences.

Participation in PlanetaryPy activities is completely voluntary.
None of the PlanetaryPy TC members are currently funded to work on
PlanetaryPy.


## Metrics

Since the repos currently under the GitHub planetarypy organization
have always been a loose federation, no consistent or widespread
user metrics are available.  However, we will use the planetarypy/pvl
library as an example case.

The `pvl` project, although prior to its recent commits had none
in more than two years, is widely used by planetary science Python
developers to deal with the pervasive parameter value language (PVL)
standard in Planetary Data System (PDS) archives, and used in image
labels written by the Integrated Software for Imagers and Spectrometers
(ISIS) software.  It is officially listed as 'being used' by more
than 20 other GitHub projects, and is likely used by many more.
Its hosting on the Python Package Index (PyPI) indicates that it
is downloaded 1.2 thousand times per month.

Simple download counts are one metric, but the fact is that planetary 
science software and analysis needs a `pvl` library as much as the
Python standard library needs a `csv` and a `json` library.  And it is 
the goal of the PlanetaryPy Project to provide libraries like `pvl`
and other data processing libraries (like those provided by `astropy`)
to the planetary sciences community.


## Scope

The PlanetaryPy TC will have sole responsibility and
discretion over the Planetary Project in the following areas:

* Setting release dates.
* Release quality standards.
* Technical direction.
* Governance process and practices.
* Contribution process and practices.
* Maintaining the list of additional Collaborators.
* Development process and any coding standards.
* Mediating technical conflicts between Collaborators and Working Groups.


## Governance, Contributions, Code of Conduct

We have adopted the Governance model from the Planetary Software
Organization.  We are using the same Code of Conduct (based on the
Contributor Covenant, version 1.4) that the PSO uses, and a
Contribution model that is also similar (with the exception that
contributors are not *automatically* made Collaborators upon a
'significant' code contribution, but the conversion of a contributor
to a Collaborator is always discussed by the TC).


## Tools

The PlanetaryPy TC currently has ownership (along with the previous
owners) of the planetarypy GitHub organization.


## IP

There is no existing IP policy nor intellectual property concerns.

### Licenses

The existing projects within the planetarypy GitHub organization
are under a BSD-3-Clause license, and we plan to allow the BSD-3-Clause
license (or the Apache 2 or MIT licenses for Affiliated Packages,
if their authors prefer) for the PlanetaryPy project.


## Members

* Michael Aye (@michaelaye)
* Ross Beyer (@rbeyer)
* Andrew Annex (@AndrewAnnex)
* Chase Million (@cmillion)
