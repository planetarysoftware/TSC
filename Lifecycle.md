# Planetary Software Organization Project and Working Group Lifecycle

## Definitions

The Planetary Software Organization hosts several Top-Level Projects
(TLPs). These projects are autonomous from each other and governed
by their own TC (Technical Committee) and chartered by the Planetary
Software TSC.  Typically, TLPs are software projects (but not always)
and are typically long-lived and open-ended.

The Planetary Software Organization also hosts several Top-Level Working
Groups (TLWGs).  TLWGs are typically formed for a specific purpose,
and when that purpose is achieved, the TLWG will stand down.

TLPs are free to create their own Working Groups which are autonomous groups
collaborating to fulfill a set of responsibilities. Working Groups are
eventually chartered by their project TC.

```
 TSC
  |
  |-- Project A TC (Chartered By TSC)
  |       |-- Working Group (Chartered By Project A TC)
  |
  |-- Project B TC (Chartered By TSC)
  |       |-- Working Group (Chartered By Project B TC)
  |
  |-- Working Group X (Chartered by TSC)
  |-- Working Group Y (Chartered by TSC)
```

Both TLPs and TLWGs may elect a representative to the TSC. TLPs and WGs
with *incubation* status are not granted voting privileges on the TSC.

## Lifecycle Overview

In general, a TLP or TLWG (hereafter TL*) will have the following lifecycle:

	1. Like-minded individuals form a TC in order to establish a TL*
	2. That TC establishes a charter for their proto-TL*
	3. That TC submits an application to the Planetary Software TSC
	4. If the application is accepted by the TSC, the proto-TL* enters Incubation
	5. The TSC works with the TC to get the proto-TL* graduated from Incubation
	6. The proto-TL* is now a fully authorized Planetary Software TL*

For TLWGs, which typically have a limited scope in time, they will
eventually achieve their goal, report to the TSC, and then will
stand down.

The Planetary Software TSC also reserves the right to revoke a TLP
or TLWG charter.


## Establishing a Technical Committee

Those like-minded individuals referenced in Item #1 above are 
referred to as the Technical Committee (TC).  Typically, a TLP will
have a TC and then also (hopefully) many other individuals that
will contribute to the TLP and collaborate with the TC (either at formation
or later).  TLWGs don't typically have a membership more than just
a TC, and so for a TLWG, the TLWG's TC *is* the TLWG itself.

A TC should have at least 3 initial members to write a charter for
the TL* and get the application submitted to the Planetary Software
TSC (but it can be submitted with fewer). It will need 3 members
in order to graduate from Incubation.  These should be individuals
already undertaking the work described in the charter.

For more information (and examples) of how to write a charter for a TL*,
and other important getting-started documents, please see our 
[examples](Bootstrap-Policies/).

## Submitting an Application

The application process to join the Planetary Software Organization
as a TLP or TLWG is as follows.

Copy the [Application Template](Applications/Template.md), fill
it out, add the file to the [Applications](Applications/)
directory, and submit that as a Pull Request.

Applications do not have to be complete to be submitted, the TSC
can work with the authors and their respective communities in each
Pull Request.

The Application is considered 'accepted' when the Pull Request is
accepted and merged by the TSC.

### Admittance
The Planetary Software Organization is quite new and currently has
limited resources available to mentor new projects. As such, projects
are chosen for admission as mentors become available.

You can apply at any time and the TSC and available mentors will
help improve your application while awaiting available resources.

## Incubation

The purpose of incubation is to support and mentor a proto-TL* entering the
organization. The goal is for a TL* to be:

* Participatory
* Transparent
* Effective

While certain processes are strongly recommended because of the
TSC's experience, the goal of incubation is not to enforce a specific
set of processes but to ensure that the processes adopted and
accepted by a project achieve these goals.  The requirements for
graduating from incubation are detailed in the section below.

While a TL* is incubating it is assigned a mentor (or mentors) who
is responsible for working with the project to adopt policies and
gain the health and contributorship it will need in order to graduate
from incubation.  The mentor (an individual or individuals that are
appropriate to the scope of the TL*, but not necessarily members
of the TSC) is nominated, must be willing to serve, and approved
by the Planetary Software TSC.


## Top-Level Project and Working Group Requirements

The requirements for graduating from incubation (and remaining a
Planetary Software TLP or TLWG) are not specific processes, but
instead are broad best-practices that that are likely to succeed
in terms of the Planetary Software Organization's values. 

Note that all of these practices adopted by a TLP or TLWG will be
evaluated by the TSC prior to ratifying the proposed charter for
graduation from Incubation, and the TSC may defer accepting the
charter until corrections are made.

Likewise, if a TLP or TLWG changes their practices after they have
been chartered in a manner that has diverged significantly from
these guidelines, the TSC (or any Collaborator) may request that
further corrections be made by opening an issue or a PR in the TLP's
or TLWG's repository. Should the TLP or TLWG choose not to adopt
the recommended changes, the TSC may choose to revoke their charter.

These requirements are as follows:

### TC Membership of at Least Three

Membership of the TC must be at least 3 members.

Each TLP TC or TLWG must elect a representative to the Planetary
Software Organization TSC or vote to abstain from representation
on the TSC.


### Transparency

The decision making and release process must be documented and
publicly accessible.

All TLPs and TLWGs are expected to operate in a transparent manner.
Decisions must be made publicly through a documented public process
managed by each TLP TC or TLWG.


### Charter

Every TLP or TLWG must have a charter that describes their statement
of purpose, scope of their responsibilities, and members.   It should
be documented in a `Charter` file located in the root of any repository
under their stewardship and referenced by their `README`.

All TLPs and TLWGs must use a participatory decision making process,
and are responsible for documenting and keeping up to date their
current processes and practices.

The TSC suggests a [Consensus
Seeking](https://en.wikipedia.org/wiki/Consensus-seeking_decision-making)
process.

All TLP TCs must ensure they are accurately representing the WGs
in their TLP.


### Code of Conduct

Every TLP or TLWG must have a Code of Conduct, and what that code
is should be documented in a `Code-Of-Conduct` file located in the
root of any repository under their stewardship.

The easy default is just to indicate that a TLP or TLWG simply
follows the [Planetary Software Code of Conduct][CoC].

However, TLPs or TLWGs can choose to define their own alternative
policy.

Note that the Code of Conduct adopted by a TLP or TLWG will be
evaluated by the TSC prior to ratifying the proposed charter for
graduation from incubation. If that Code of Conduct is considered
to be weaker than, or diverges too significantly from, the [Planetary
Software Code of Conduct][CoC], the TSC may defer accepting the
charter until corrections are made.

Likewise, if a TLP or TLWG Code of Conduct changes after it has
been chartered and the TSC determines that the updated Code of
Conduct is weaker than, or diverges too significantly from, the
[Planetary Software Code of Conduct][CoC], the TSC (or any Collaborator)
may request that further corrections be made by opening an issue
or a PR in the TLP's or TLWG's repository. Should the TLP or TLWG
choose not to adopt the recommended changes, the TSC may choose to
revoke their charter.

### Contributing Guidelines

Every TLP or TLWG must have Contributing Guidelines, and they should
be documented in a `Contributing` file located in the root of any
repository under their stewardship.

This document should describe a very simple process suitable for most 
TLPs and TLWGs in the Planetary Software Organization ecosystem.

## Approved Licenses

At this time the Planetary Software Organization is only accepting
projects which use an MIT, BSD, ISC, Apache2, or UnLicense license.
If you think another license would be appropriate, please submit 
an Issue.


## Graduating from Incubation

A proto-TL* in incubation may graduate at any time by passing a TSC review,
and then passing a majority vote of the TSC.

### TSC review

A review is initiated by someone requesting a review via an Issue
on the TSC repo.  This someone could be a member of the proto-TL*'s
TC, one of the proto-TL*'s mentors, or someone from the TSC.

Two TSC members who are not conflicted with the proto-TL* (not
members of its TC, nor its mentors) will review the state of the
proto-TL* against the above requirements, documenting their findings
in the Issue thread.

If these two TSC members find that the proto-TL* does not pass the
criteria, advice will be given for how the TC can rectify the
shortcomings.

The TC can then make changes and request another review.

If the two TSC members both find that the proto-TL* does meet the
criteria to graduate from incubation, then the TSC can hold a
graduation vote.

### Graduation Vote

If the proto-TL* has passed a review by two TSC members (see above), it can
be put to a TSC vote to graduate.

This process can happen either via an agenda item in a regular TSC
meeting, or directly via a PR to modify the main TSC [README](README.md)
to add the new TLP or TLWG to the lists in that document.  The vote
or the PR must gain approval by a majority vote of the TSC.  If
this vote is held at an in-person meeting and passes, the following
PR to modify the README only needs to satisfy the 'regular' PR
requirements (since majority requirement was satisfied at the
meeting).

The TLP or TLWG is considered to be chartered once that PR lands.

### Badges

Once admitted, please update the relevant readme files for the
project to include the appropriate Planetary Software Organization
badge.

| Type       | Badge | Raw Markdown |
|------------|-------------------|------------------------|
| Affiliate  | [![Affiliate](https://img.shields.io/badge/Planetary_Software-Affiliate-645394.svg)](https://github.com/planetarysoftware/TSC) | ```[![Affiliate](https://img.shields.io/badge/Planetary_Software-Affiliate-645394.svg)](https://github.com/planetarysoftware/TSC)``` |
| Project    | [![Project](https://img.shields.io/badge/Planetary_Software-Project-645394.svg)](https://github.com/planetarysoftware/TSC) | ```[![Project](https://img.shields.io/badge/Planetary_Software-Project-645394.svg)](https://github.com/planetarysoftware/TSC)``` |


[CoC]: Code-Of-Conduct.md
