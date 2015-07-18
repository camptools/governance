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
