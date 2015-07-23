Branding
========
One of the main problems with the external perception of the conference is the
lack of a strong consistent message and brand. Over the past year we have
changed the site several times along with the logo and, briefly, the color
scheme. This all occurred with little to no change to the copy or the strategy
behind it.

Additionally, the email campaigns were usually packed with data and information
that had a flow based on the day of the events not necessarily the events
themselves.

In general we have a problem communicating a clear message to our audience
_what_ it is we are and _why_ we are doing it. Some people still see us as a
Drupal conference, while others view us as a new kid on the block Open Source
conference.

##Apartments versus Hotels
Part of the problem stems for an unnecessary one-size-fits-all approach to
content. We have __one__ website. We have __one__ type of mini-camp page. We
have __one__ type of summit page. Even if these things are different, we still
only have one type for all of them. This restriction led to multiple mini-camps
creating their own static sites. These sites had different branding and feel
from the main NYC Camp site and redundancy of shared components led to
miscommunication to attendees and general confusion.

Part of the DevOps movement has focused on moving from treating infrastructure
as pets to treating it as livestock. While this is certainly useful for servers
and the like it does not work well for content. The current state of the website
treats content as livestock: Everyone gets the same branding and feel, no matter
how much they differ from each other. In general though, thinking of content as
pets or livestock is a gross inaccuracy, but the model of thinking is valid.

A much more apt comparison is that of apartments and hotel rooms. An apartment
is a blank canvas on which the leaser of the space crafts their own vision,
placing furniture where they think is best and represents their story best. Two
apartments with the same layout might have extremely different looks and
represent very different stories, however, they are still recognizable as the
same model. In contrast a hotel room has the same furniture and furnishings. The
leaser doesn't get much leeway to change things around and rooms of the same
model do look the same. There is an expectation with hotel rooms that certain
things will be available, e.g. a bed, alarm clock, bathroom, desk, television,
whereas an apartment comes with few of these expectations, e.g. a bare bathroom
and kitchen.

When it comes to content management systems, hotel content is the easiest type
of content to manage within them. One sets up the basic template with fields and
everyone gets to fill out those fields and those fields only. There isn't a ton
of flexibility to move things around. One could shove apartment style content
and "manage" it via the content management system. This method isn't nearly as
useful though because of the wide degree of variance between the different
components of apartment content. Eventually apartment content inside of a
content management system becomes a couple of garbage bag fields in which HTML
is shoved. This is not management of content, just the illusion of such. It
becomes even worse when apartment content really wishes to deviate from the
given environment with things like custom javascript and css. When one wishes to
include such things they start having to fight the very system meant to manage
them.

A better solution for apartment content is to manage it by hand. Usually one
does not have too many pieces of apartment content and each usually has an owner
or two of their own anyway. This method makes it much easier to allow apartment
content to grow. Of course it doesn't work well for hotel content, wherein
the user is perfectly happy to not manage any javascript or css.

A hybrid approach is best for these situations, wherein the content management
system sits behind a proxy that also contains the apartment content. This does
add extra overhead to those who wish to manage the apartment content, however
one can argue that there should be a stronger workflow for apartment content as
it should have a lower churn rate. After all, one doesn't redecorate their
apartment every day or week. Such thrashing can be confusing to users of a site
where thrashing of hotel content is less so since strictly updating the copy
does not change the view of user experience as greatly.

##Logo
The logo of the organization is just as important as the overall site design,
color scheme, copy, and marketing. The logo should communicate what the
conference is about and the layout, color scheme, copy, diagrams, and images on
the site should convey these things as well. It is important that simplicity be
a running theme throughout the branding, especially when it comes to logo
design, copy, and marketing. Everything is connected, so a complex logo can
easily derail the entire experience of the site if the team is not careful.

##Vision
The vision and mission of the conference is of extreme importance. There should
a simple focus on a collection of related items. Attempts to bring other things
into the fold should be met with resistance and thorough discussion. A high
barrier of entry for adopting new components of the vision and mission will
ensure the scope of the conference does no creep in unnecessary ways. For
instance, if the conference is meant to mainly support the open source community
in New York City, things like childcare are not of high importance since most of
the attendees aren't bringing their families to the city. If the goal of the
conference is to bring the open source community together it should not have a
heavy focus on a single particular technology, e.g. Drupal or Angular, but
instead focus on how to bring different open source and free technologies
together to create a more collaborative environment. For instance, preference
should be given to sessions that give an overview of technologies that are
framework specific over ones that focus on a specific technology. This gives the
conference a feeling of not being another "open source conference" that's a grab
bag of technologies, but a conference with a specific goal that sets itself
apartment from others.

##Communication & Marketing
In addition to the copy on web properties, the copy and design of marketing
materials should be consistent with the overall branding of the conference. The
voice between the website copy, social media communications, and other marketing
material should be consistent. Developing a strong voice for the camp will help
to lessen the perception of chaos internal to the conference. For this reason,
there should be a group of members who copywrite and approve copy no matter what
the destination is.

##Websites, Web properties, and simplicity
In prior years the conference has had a single monolith website and
conversations in regards to the website were told from the point of view of this
single monolith. Moving forward individual parts of the website should be talked
about as web properties. This small change can help ensure that sections of the
website have a clear purpose and it can help to clarify the underlying data
model and content strategy.

This past year's website consisted of pages that looked identical, no matter the
content or the purpose for that content. Some pages only had a paragraph while
others sprawled down the page. The same template with a large image at the top
was used almost universally, even where completely inappropriate. This should
not happen again. Each property needs to be treated as a distinct part,
especially the camps and summits. Special care should also be taken in areas
such as directions and maps. They should be clear, concise, and straight
forward.

As mentioned before, it is important to not become too attached to using a
content management system just because one has "content" that needs to be
"managed". It is much more important to establish workflows that reinforce the
brand and ensure there are proper checks and balances. For instance, things like
sessions should be easily editable by the submitter. On the other hand things
like the main Front End Camp property should require a more thorough workflow
that includes code reviews and ensures that the overall message being
communicated is consistent. This is the same for other properties, like the maps
and directions. Special care should be taken to ensure any visual maps match the
written directions to the venue. Internal venue maps should also require some
sanity checks to ensure changes are consistent and communicated to all necessary
parties properly.

The main point is that the content on the site is not just copy, and we
shouldn't give preference to use a content management system simply because it
makes it easier to edit copy. The web properties are part of a larger ecosystem
that includes marketing and social media communications. Effort should be made
to ensure these things are all consistent. We also should overload a system and
shoehorn it into something it's not to satisfy the impulse to use a content
management system because we have content to manage.
