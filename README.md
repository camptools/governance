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



