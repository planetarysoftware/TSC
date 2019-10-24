# Technical Steering Committee (TSC) Charter

## Section 1. Guiding Principle.

The Planetary Software Organization will operate transparently, openly, inclusively,
collaboratively, and ethically. Project proposals, timelines, and status
must not merely be open, but also easily visible to outsiders.

## Section 2. Evolution of Planetary Software Governance.

Most large, complex open source communities have both a technical
governance model and a business governance model that provide
guidance and leadership in these areas. The Planetary Software’s
governance model provides technical guidance and leadership via the
Technical Steering Committee (“TSC”). Planetary Software does not
(yet) have a business leadership model.

The charter amendment process is the means by which the TSC
proposes changes to this charter, and requires a simple majority 
of the full TSC.

## Section 3. TSC Membership

TSC members are responsible for top-level technical community concerns. The role
is mostly administrative and is primarily responsible for admitting new Top Level
Projects and Top Level Working Groups.

TSC members can nominate new members at any time. Candidates for membership tend
to be people who have a competency for community management and a high tolerance
and patience for process minutiae as the TSC delegates most of its responsibilities
to other projects and working groups.

A [current list of TSC members](Members.md) is maintained in the
main TSC repository.

TSC memberships are not time-limited. There is no maximum size of the TSC.
The size is expected to vary in order to ensure adequate coverage of important
areas of expertise, balanced with the ability to make decisions efficiently.
The TSC must have at least three members.

There is no specific set of requirements or qualifications for TSC
membership beyond these rules. The TSC may add additional members to the
TSC by a standard TSC motion and vote. A TSC member may be removed from the
TSC by voluntary resignation, by a standard TSC motion, or in accordance to the
participation rules described below.

Changes to TSC membership should be posted in the agenda, and will be then discussed
at the next TSC meeting. Any vote to change the TSC membership must remain open
for at least a month.

The TSC may, at its discretion, invite any number of non-voting observers to
participate in the public portion of TSC discussions and meetings.

The TSC shall meet regularly using tools that enable participation by the
community. Responsibility for directing individual meetings falls on those members
present. Minutes, or an
appropriate recording, shall be taken and made available to the community
through accessible public postings.

TSC members are expected to regularly participate in TSC activities.

In the case where an individual TSC member -- within any three-month period --
attends fewer than 25% of the regularly scheduled meetings, does not
participate in TSC discussions, *and* does not participate in TSC votes, the
member shall be automatically removed from the TSC. The member may be invited
to continue attending TSC meetings as an observer.

## Section 5. Responsibilities of the TSC.  

The TSC exercises autonomy in setting up and maintaining procedures and policies,
as well as management and administrative structures as it deems appropriate for the
maintenance and operation of these projects and resources.

The TSC is responsible for all technical development within the
Planetary Software Organization, including:

* Technical direction
* Setting and maintaining governance rules for the conduct and make-up of the
  TSC, Working Groups and other bodies within the TSC's domain
* Creating new repositories and projects under the 
  [_planetarysoftware_ GitHub organization](https://github.com/planetarysoftware)
  as required
* Setting and maintaining appropriate standards for community discourse via the
  various mediums under TSC control
* Maintaining a list of additional Collaborators
* Setting and maintaining standards covering contributions of code,
  documentation and other materials
* Mediating technical conflicts between Collaborators or Planetary Software Organization
projects

The TSC serves as Planetary Software’s primary technical liaison
body with external open source projects, consortiums, and groups.

Many of these responsibilities will be delegated by the TSC to appropriate
bodies such as the Working Groups.


## Section 6. Planetary Software Organization Operations.

The TSC will establish and maintain a development process for the
Planetary Software Organization's Projects. The development process
will establish guidelines for how the developers and community will
operate. It will, for example, establish appropriate timelines for
TSC review (e.g. agenda items must be published at least a certain
number of hours in advance of a TSC meeting).

There will be multiple Top-Level Projects (TLPs) under the Planetary
Software Organization as well as Top-Level Working Groups (TLWGs).
The TSC is responsible for helping these TLPs and TLWGs get organized.
Each must be within such policies as may be set by the TSC, have a
well-defined scope and must work within that scope. The development
process will provide for TLPs to follow the lifecycle process as
described in the [Project Lifecycle](Project-Lifecycle.md) document.
The development process will include a process for the TSC to oversee
and approve changes in the lifecycle of a Project, which will include
consideration of the following criteria:

* Cleanliness of code base
* Ample and diverse Contributors and Collaborators to assure vitality of
the project.
* Stability (e.g. presence of test suites, stable APIs and use of an
  appropriate source-code control system).
* Predictability of releases
* Alignment with Planetary Software’s goals and priorities.

The TSC and the entire technical community will follow any processes
as may be specified relating to the intake and license compliance
review of contributions.

## Section 7. Voting

For internal project decisions, the TSC shall operate under Lazy
Consensus. The TSC shall establish appropriate guidelines for
implementing Lazy Consensus (e.g. expected notification and review time
periods) within the development process.

The TSC follows a [Consensus Seeking][] decision making model. When an agenda
item has appeared to reach a consensus the moderator will ask "Does anyone
object?" as a final call for dissent from the consensus.

If an agenda item cannot reach a consensus a TSC member can call for
either a closing vote or a vote to table the issue to the next meeting.
Such a vote must pass by two-thirds of the TSC or else the discussion will continue.

For all other votes, a simple majority of all TSC members for, or against, the issue
wins. A TSC member may choose to participate in any vote through abstention.


## Section 8. Project Roles

The Planetary Software Organization Git repository is maintained by the TSC and
additional Collaborators who are added by the TSC on an ongoing basis.

Individuals making significant and valuable contributions,
“Contributor(s)”, are made Collaborators and given commit-access to the
project. These individuals are identified by the TSC and their addition
as Collaborators is discussed during the monthly TSC meeting.
Modifications of the contents of the Git repository are made on a
collaborative basis as defined in the development process.

Collaborators may opt to elevate significant or controversial
modifications, or modifications that have not found consensus to the TSC
for discussion by assigning the `tsc-agenda` tag to a pull request or
issue. The TSC should serve as the final arbiter where required. The TSC
will maintain and publish a list of current Collaborators by Project, as
well as a development process guide for Collaborators and Contributors
looking to participate in the development effort.

## Section 9. Definitions

* **Contributors**: contribute code or other artifacts, but do not have
the right to commit to the code base. Contributors work with the
Project’s Collaborators to have code committed to the code base. A
Contributor may be promoted to a Collaborator by the TSC. Contributors should
rarely be encumbered by the TSC.

* **Project**: a technical collaboration effort, e.g. a subsystem, that
is organized through the project creation process and approved by the
TSC.

[Consensus Seeking]: http://en.wikipedia.org/wiki/Consensus-seeking_decision-making
[Condorcet]: http://en.wikipedia.org/wiki/Condorcet_method
[Single Transferable Vote]: http://en.wikipedia.org/wiki/Single_transferable_vote
