---
layout: essay
type: essay
title: A Meteor Once Killed The Dinosaurs -- Will MeteorJS Kill Us?
date: 2017-10-19
labels:
- MeteorJS
- Reflection
- Web Development
---

<center>
<img class="ui large round image"
     src="http://www.discovermeteor.com/images/blog/state-of-meteor.jpg" />
<caption>The humanity killer?</caption>
</center>

## In the beginning...

Someone named Dr. J once proclaimed, in our software engineering class,
that MeteorJS would come down to Earth to strike us and open us up to
the wonderful world of web development!

My first thought was that "He's making it seem better than it is.
It's going to be much harder than it appears."

***"Oh, but web dev is EASY!"*** my young, brash mental child-brain said.
***"There is no flying F why Meteor should give you ANY problems!"***

*"But, web dev is hard..."* my older, more experienced adult-brain ssaid.
*"Networking and web development keep evolving because people keep somehow
finding new innovations..."* And I was inclined to agree with my adult
thoughts.

## 0. "Mama's always right..."

...and there, my adult-brain was also right. MeteorJS is not as polished
as a beginner experience should be for optimal smoothness, and this is
because the introductory experience is not geared towards beginners.

I will give three major reasons below on why MeteorJS is not as easy
as it seems.

## 1. MeteorJS is not easy to install

Meteor can take over an hour to install. That's ridiculous for what is
considered to be a well-developed and ready-to-use-professionally
framework. I expected more polish in the installation process and more
support for Windows. Is this because Meteor is so new or that its
community is small?

Okay, okay -- perhaps I'm just complaining because it gets stuck on
one part of the installation process for 10-15 minutes. But that's just
bad user design.

MeteorJS installation is especially bad on Windows. The fact that MeteorJS's
installation process is affected by what version of `tar` or `7zip` you
have installed, and that it's not installed correctly by default brings up
some red flags for me.  

## 2. MeteorJS is nice, but still hard as a first web dev framework

MeteorJS is touted as simple due to its hiding of implementation details
of server-client communications (namely, the request-response framework).
It relies on a reactive model and opt-in/opt-out publisher/subscriber
system, and is packaged with its own templating system, Blaze.

However, just because it encapsulates complexity doesn't mean that
its beginner material and tutorials are fantastic by virtue of the
framework itself. (Take Nand to Tetris, an acclaimed educational course
that takes a very spartan bottom-up approach.) In fact, MeteorJS's official
tutorials do not try to teach web dev. They are trying to teach **Meteor**.

**Who is the audience for MeteorJS?** Professionals? Novices? Intermediate
developers? Take the programming language Go, for example -- Google
explicitly designed it to be learned quickly due to the nature of turnover
at Google. New software developered were expected to pick up the C-lite
language and go far with it.

Certainly, the audience for MeteorJS is not beginners. They expect you to
use Meteor as an "easy-to-use, incremental innovation" on top of the
traditional web dev approach knowledge, a sort of "shortcut" ecosystem
to get rid of the repetitive parts (an embodient of the Don't Repeat
Yourself principle). But I would've liked to have seen MeteorJS be
geared towards complete beginners. The official material is lacking on
this.

## 3. MeteorJS is embedded in the fragmented NodeJS ecosystem

Node is the largest pacakge ecosystem ever. This is not neccessarily
a good thing. `leftpad` is the perfect example of a package that should've
never been written.

Meteor also suffers from this -- the fact it needs packages that don't
seem to be under a `meteor-official` username means that the "highly-used"
packages will continue to be offered by randoms and not signal to new
users what are the most important packages. Aggregation of common knowledge
and aggregation for educational clarity is very important for adoption.

## MeteorJS will not kill us...

...but it's not going to save us as well. The first step towards
heavenly stature for Meteor is to improve its documentation and friendliness
to beginners.
