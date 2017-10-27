---
layout: essay
type: essay
title: Is Meteor's Model Weird?
date: 2017-10-26
labels:
- Meteor
- JavaScript
- Reflection
- Web Development
---

<center>
<img class="ui large round image"
     src="http://www.discovermeteor.com/images/blog/state-of-meteor.jpg" />
<caption>But is it actually the humanity killer? Part 2.</caption>
</center>

---

## "What do you mean by weird?"

Meteor's project structure is setup strangely. Unlike most programs, Meteor is
intrinsically split into 2 parts even though it claims to be a "full stack
framework." There is always a main.js` under the `server/` directory and a
`main.js` under the `client/` directory. This means that Meteor is intended to
be an all-in-one system. So, Meteor's goal is to be a "kitchen sink" that's
easy to develop with and use for web development.

However,

  - Meteor is attached to the NPM ecosystem, and further fragmented their
    ecosystem in the past with Atmosphere packages.

  - Meteor prefers Meteor-specific methodologies with its framework.

Thus, Meteor is relatively rigid and uncompromising to the rest of the web
development world. This is not good for Meteor's future, as it stands on its own
strength alone. Due to Meteor's relatively narrow domain as a web framework
compared to libraries and programming languages, this means that knowledge gains
with Meteor may not be easily as applied to other domains, even across to other
frameworks. This makes Meteor a more inherently niche technology instead of an
attractive technology suited towards a wider audience.

## The Juggernaut?

<center>
<img class="ui large round image"
     src="https://static.comicvine.com/uploads/scale_small/7/78617/3063703-juggernaut_full_artwork.png" />
<caption>No, *naut* this Juggernaut...</caption>
</center>


Meteor itself is not a juggernaut in its domain -- it is not dominating to begin
with. Meteor's competitors are libraries like Ember.js, Angular, and React. They
are all quite large.  Meteor's backers are not as well-established as the other
frameworks' sponsors. With Google supporting Angular and Facebook reporting
React, this means that Meteor may struggle with long-term support since it
has not reached critical mass (and, its backer has not reached a sustainable,
profitable state of business yet).

- Meteor's ecosystem is not necessarily conducive to learning.
  - Meteor does not stress minimalism.
  - Meteor is incremental on the NPM and Node ecosystem.
  - Meteor does not stress unity and coherence in "standard offerings."
  - Meteor's package providers are fractured, and thus, the quality of
    each package may be variable.
  - Meteor's model is relatively high-level and sufficiently complex with
    reactive programming and its own DDP protocol.
  - Meteor's community and audience is not as wide and welcoming as
    other's, such as Rust or Python.

## So What?

Meteor suffers from a focus problem -- if it can manage to streamline its
experience, it may find its way to domination in the full-stack web development
space.
