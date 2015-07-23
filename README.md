# governance
Tools for Governing

Rough Thoughts
==============
This section is mainly rough ideas that need to be flushed out more.

Volunteer based organizations require some level of structure. Having no
structure is a form of structure which requires the members of the organization
to be of similar mindset and for no one member to have a severely different
mindset than the others. These individuals are not toxic to the organization,
but it does mean that a more formal structure is required.

In addition to the above problem having no structure makes it hard to determine
what decisions were made when. Again, it is not impossible but requires a high
level of discipline to maintain the system. It also requires having individuals
on the same level and for disagreements to be solved by the group with no hard
rules to reference. Verbally agreed rules also do not work because the human
memory is fallible and malleable so verbal rules often morph as time goes on.

Strong willed individuals are often beneficial to organizations, especially
those who oppose each other. It allows ideas to be fully flushed out and
discussed, with opposing sides have representation.

###How?
Structure usually comes in the form of written documents that are agreed upon by
the organizers of the organization. These documents do not have to have a
specific form but they should include at least:

- a procedure for submitting items to be discussed and voted on
- a procedure for discussing said items
- a procedure for voting on said items
- a repository to collect the results of said votes and items that have been
  approved.

As engineers working in a distributed manner we already have tools that help
cover many of the needs for these written documents. An obvious solution is to
use Word or Google Docs to create these documents and collaborate on them.
However, additional structure must be set up to pass the items along the chain
and then later combine them together. Usually these processes are manual since
there aren't many, if any, auto merging tools for Word of Google Docs and even
so it because difficult to have multiple people submit said requests for
merging.

However, we already have a tool that allows for many people to collaborate in a
distributed manner, submit their changes to be merged, and auto merge those
changes after a vote. This tool is git. While we don't have the tool to take the
vote and accept the merge request, both GitHub and Slack have facilities to have
a bot hooked up to them that can easily handle this functionality. Also, due to
the nature of git, even failed items can still be kept in the repository with
the master document. Git also has conventions for signing off on items, which
allows authorship and sponsorship of items to be easily added.

###But what are these "items"?
Above we laid out the documents minimally required content, however the term
"item" has been left undefined. While the documents should define different
types of items all which should follow a similar process, there are two specific
types of items that would be help to define and use. These are _decisions_ and
_tasks_.

These items are similar in content, but they are used for two different
purposes. _Decisions_ are used to make a declaration or assert something that
__is already done__. This can include formally approving a plan (such as a
logistics plan) or forming a new committee. _Tasks_ are used to to declare or
assert work that needs __to be done__. These includes things like writing a plan
(such as a logistics plan) or building a web property or application.

Both of these types of items should include at a minimum the who, what, where,
when, why, and how. These six items will have different amounts of content
depending on the size of the task or decision. Decisions more likely than not
will have more formal entries for the who, where, when, and how sections. The
important parts of decisions lie in the what and why areas.

Both types should declare explicitly the six required parts of content, however
a decision should also include a combined written component that can be easily
merged into a living document. A tool should be created to pull this written
component out of the document and properly merge it into place in the living
document.

###The importance of the 6 elements
Answering who, what, where, when, why, and how for every decision and tasks has
several benefits. Tasks that answer these 6 elements are more easily
transferable between members of the volunteer teams. They also benefit from a
great development process. Having to understand the task at hand from several
angles flushes out more details of a task as well, which can greatly help cut
down on the redundant and repetitive work.

Answering the six elements is even more necessary for decisions as it provides
for not only a detailed item to be added to a plan but it also helps inform the
intent of the decision. Intent should not be included in actual plans as it
can make things unclear. Intent is important though, especially after several
months: being able to look back at a decision that was made and easy bring the
context to the forefront removes redundant efforts and more importantly
redundant conversations.

##Redundancy
Being a volunteer based organization having redundancy is of high importance.
Every major role played in the organization should have a redundant counter
part. This requires additional volunteers, but also focuses the necessary roles
down to a smaller number. Having redundant roles becomes problematic quickly
if every role requires redundancy and inefficiencies are more easily
identifiable.

Redundancy can also help emphasize the need for tasks that can be easily traded
off between members of the volunteer teams. The more descriptive and focused the
tasks to be executed are, the easier it is for team members to trade them off
with one another.

##Team Size
The organization will not function well as a single monolithic entity. While
many camps and conferences can function in this manner, their scope is severely
limited. Since it is apparent that scope limitation is not practically within
the grasp of this organization a different approach should be taken. Instead of
operating a single monolith, the core team of organizers should be chiefly
responsible for managing the tasks to be done, but not executing the tasks
themselves. Tasks should be farmed out to small core teams that exist related
to, but outside of, the direct NYC Camp organizers.

##Structure
There are two different levels of organizing that are required to organize a
large conference of conferences. The top level are the __organizers__. While
they can participate in actually doing work, their job is chiefly to manage
work.

This is mainly done by being the final approval for high level tasks and
decisions. They are directly in control of any official plan and maintain the
master plan, called the "conference code". This document should largely work as
a reference manual that can be used year over year, that is, it a specific
conference agnostic document. This document is mainly formed from the high level
decisions approved by the organizers. The tasks for a specific year are
organized into the "conference plan", which expires every year after the
conference. This document is formed from the high level tasks approved by the
organizers.

Both of the conference code and conference plan should be fairly coarse grained
and allow for smaller more specific plans and codes to be created and
authorized.

The second level are the __vounteers__. This level performs much of the work in
bring the conference together. This level is broken out into committees. Each
committee should be focused on a specific set of well defined task areas. A
large amount of effort should be placed into ensuring that there is not much
overlap between committees. This ensures that there is not ambiguity between the
authority of committees. Ambiguity can lead to discussion and decisions that
should take place in the volunteer level to take place in the organizer level.
This means more energy is required from the organizers which breaks down the
barriers between managing and work.

Each of the committees in the volunteer level should have a committee code and
committee plan, which are handled mostly by the committee themselves. Tasks and
decisions within the respective codes and plans must have an authorized decision
or task in the conference code and plan that they relate to. When ambiguity or
disagreement arises on a decision or tasks' relation to an authoritative
decision or task, the organizers are responsible for clarifying if said decision
or task is in within the purview of the authoritative decision or task. This
decision should be a yes or no and should not change the authoritative decision
or task. That should be brought up and addressed at a later time.

##Officers
The organizers are made up of the chairman, secretary, treasurer, and the chairs
of the various committees in the volunteer level. In addition to these various
representatives of the community may also be an organizer, however the number of
these organizers should be kept to a minimum. When possible, it is favorable to
have representatives from the community participate in the various committees in
the volunteer level as they perform a majority of the work for the conference.
The organizers should be kept as small as possible without sacrificing
redundancy and without placing too much responsibility on any single individual.

Each of the committees in the volunteer level should consist of at least a
chair and a co-chair. Aside from that each various committees should choose its
officers and positions for itself. These position must be documented in the
committees code and changes to the number and title of officers must be approved
by the organizers.

##Documentation over Technology, manual over automated
Currently the conference has little documentation, and the documentation that
does exist contradicts itself in many places. This documentation needs to be
codified and condensed into a few areas. This should be done prior to making
technology decisions. That is, it is more important to have a simpler
technology system and through documentation than automated systems with poor
documentation.

There should also be an emphasis on well defined manual processes over weakly
defined automated processes. For instance, if given the choice between a well
documented workflow for scheduling and displaying schedules, but it is manual
using spreadsheets, and a undocumented workflow for scheduling and display
schedules which is automated, the former should be chosen.

##Decision and Task tracking
Decisions and tasks should be tracked in git as it allows for keeping of
history, easy distribution, easy review, and has more advanced tooling for the
type of workflow needed for these items. Google Docs could work as an
alternative but they suffer from being highly centralized and require
permissions. Even when they are open, a link is still necessary. Using git in
combination with Github, Bitbucket, or a similar system will enable a more open
expression of decision and task tracking. The organizers and each committee
should have their own repos. Both the code and the plan should be kept in the
repository along with all of the approved and failed tasks and decisions.

Keeping this historical information is important for review and onboarding new
members. A pull request method may be used for proposing tasks and decisions.
Failed tasks and decisions should either be kept as branches or placed in a
special directory of failed tasks and decisions with proper diffs. The second
method is more maintainable and less verbose, due to the fewer number of
branches. It also allows tools to be run which can parse information more easily
since branch switching will not be necessary.

A special document format should be designed that can handle not only the six
elements plus a code-version summary, but also a diff and additional information
such as approved or failed, sign-offs, and potentially a voting record.

##Delegation of work
Work should be delegated away from the organizers to the committee teams. This
ensures that there is always work to be done and will help to drive strong
teams. This also allows the organizers to focus on the overall conference and
not focus on the small details. This separation is of great importance and
should not be infringed.

The organizing team is responsible for ensuring the tasks of each committee are
related to the generalized tasks laid out by the organizers plan. The tasks must
also abide by the rules laid out in the organizers code.

Members of the organizers may participate in the volunteer level committees, but
their priority should be executing work for the organizers. This excludes the
members of the organizers who chair the committees. Their responsibility is to
ensure their team is running smoothly first and foremost. For this reason, there
should be several members of the organizers who do not chair committees.

Certain areas are under the purview of the organizers as passing the
responsibility onto any singular committee would be difficult, such as branding.
A branding subcommittee should exist inside the organizers, since branding
touches almost every part of the conference. Branding is also a high level
matter, as it has a direct influence on the conference's public perception.
Other areas, such as drayage, communication, logistics, and web property
development should remain separate committees.
