# Planetary Software Organization Project Mentor Guide

This document provides general guidance for a TLP or TLWG Mentor.

First off, thank you for volunteering to mentor a new project or
working group within the Planetary Science Organization.  Providing
this kind of 1 to 1 guidance is a key part of our organization's 
activities.  We know that the mentee projects will appreciate your
help.

Second, please read and be aware of the concepts in the [Lifecycle
document](Lifecycle).


## Dealing with the Application

The first thing a nascent TL* will do is submit an application as
a PR to the Application/ directory, following the
[template](Applications/Template.md).  Your first job is to put a comment
on that PR as soon as you can, something like:

	Thank you for applying to be a [TLP|TLWG] with the Planetary
	Software Organization.  I will be your mentor for this
	application process.  If you have any questions, please
	enter them here, or contact me directly.  Our next task is
	to review your application.  So please be watching this PR,
	in case we have questions.
	

Your next job as mentor will be to review their application against
the template.  If you find it satisfactory, approve it and wait for
(or solicit from the TSC) an additional approval.  Once there is a
second approval, you can merge it (see below).

If there are issues with the application, add comments to the PR, and
work with the PR authors to make the application acceptable.


## Application Satisfactory: Incubation Issue

Once there are two reviews on the application, it can be merged.  Before
you do so, you need to set up an Incubation Issue to track this 
TL* through the Incubation process.  Use the [Incubation Issue
template](https://github.com/planetarysoftware/TSC/issues/new/choose)
to create a new Incubation Issue for this TL*.


## Application Satisfactory: Merge Application PR

Now you're ready to merge their application PR, use the Incubation Issue
number you just created above in the comment you leave on the merge:

	The Planetary Software Organization has accepted your application!
	
	Your [project|working group] is now under Incubation with
	the Planetary Software Organization.  We'll use Issue #00
	to track your status through Incubation.  Please make sure 
	you are subscribed to that Issue, so you can respond to items
	that come up there.


## Mentoring Incubation

This is the most ill-defined part of the job.  Some TL* will need
a lot of interaction from you to satisfy the conditions to graduate
from Incubation, some will be almost ready to do so as soon as their
application is accepted.

During this period you should work with the proto-TL*'s TC via the
Incubation Issue to work towards the criteria detailed in the
[Lifecycle document](Lifecycle).


## Ready for Review

Once you feel that the TL* has satisfied the criteria to graduate
from Incubation, you can file a Review Issue (as specified in the
[Lifecycle document](Lifecycle), referencing the Incubation Issue
to get external review from TSC members.

## Ready to Graduate

Once the Review has sucessfully completed, follow the instructions 
in the [Lifecycle document](Lifecycle) document and either bring the
TL* up for a vote at a TSC meeting, or file a PR.


## Graduated!

Once the PR lands on the main README, this TL* is now chartered, and
you should leave a final comment in the Incubation Issue, and close it:

	Congratulations!  [Project Name] is now a fully chartered Planetary
	Software Organization Top Level [Project|Working Group].
	
	If a member of your TC is not already a member of the PSO TSC, please
	consider joining.


## All done!

Thank you for serving as the mentor for a PSO project or working group
during their application and incubation process.


[Lifecycle]: Lifecycle.md
