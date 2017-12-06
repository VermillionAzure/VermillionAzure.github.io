---
layout: essay
type: essay
title: Elegance and Decadence
date: 2017-12-05
labels:
- Design Patterns
- Software Development
- Reflection
---

<center>
<img class="ui large round image"
     src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/98/Marie-Antoinette%2C_1775_-_Mus%C3%A9e_Antoine_L%C3%A9cuyer.jpg/800px-Marie-Antoinette%2C_1775_-_Mus%C3%A9e_Antoine_L%C3%A9cuyer.jpg" />
<caption>"Let them eat cake." Can proponents of design patterns (not just GoF) 
sometimes be ignoring their inherent complexity? </caption>
</center>

## What is the proper place for design patterns?

**["Design patterns are a 
language,"](https://softwareengineering.stackexchange.com/questions/9219/are-design-patterns-generally-a-force-for-good-or-bad),** 
so says Stack Overflow. But in reality, what really is the *proper* place
for design patterns? I've heard bits and pieces on the side that design
patterns are, indeed, important, but should not form the basis for a
curriculum that wants to pride itself on teaching true fundamentals. And,
yet, design and understanding how to design products are very important to,
well, the *design* of software products in industry.

We come to an impass: how should design patterns be framed?

## Welcome to the jungle...

When I interned at Amazon over the past summer, I was able to vaguely
attach myself onto the code I worked on over the summer, and I was also
able to get somewhat closer to the Amazon Web Services (AWS) Java APIs.

Patterns like `DynamoDBTypeConverterFactory.Builder` appear to be very
clearly influenced by the Gang of Four OOP design patterns, with factories
and builders and decorators being used here and there, and perhaps,
everywhere within the Java API. Clearly, the power of design patterns here
is not to improve the implementation -- for all users care about, an API
is meant to be used and abused, not to be meticulously optimized by its
users (that's the job of the Amazonians). Design patterns are used to serve
as a *touchstone*, and as a language guide to how to create a unified and
clean API for one of the currently most profitable pieces of software on
Earth.

## Unlimited complexity

Meanwhile, newer trends with functional programming seem to be in a similar
vein to how people treat design patterns -- often times, functional
programming is treated as some sort of panacea that will make *all*
programs safer and easier to maintain... at least for those that understand
the patterns being used in more type opaque languages that demand a more
rigorous conceptualization of a program through type system gymnastics.

Should people be learning the very tip-top of modern language features to
optimize their software engineering experience? Should everyone be exposed
to how mathematical monads have inspired algebraic-applied code bases or
how dependent typing can stop bugs like Heartbleed? Or should we lower the
bar, considering the amount of time and sophistication (and resources!)
that students have in their four (or so) years of undergraduate college?

**When is it all too much?**

## We begin on common ground.

**Common ground** is the concept that social interaction and a means of
transaction of information in a fidelitous manner requires a common
understanding between the at-least two parties involved in communication,
and it is very applicable here -- when we write programs in software
engineering, we must ask ourselves -- do we write primarily for the human,
or for the machine? Yes, indeed, we write programs that must ultimately be
understood by the machine, but we, as humans, impose abstractions and
patterns on our languge to reduce the mental load of having to memorize
thousands of sequences of machine code instructions by abstracting them
into function calls, objects, automata, and systems. We use encapsulation
and information hiding to simplify the design of a system, and to make it
usable at a higher level. 

## The Message

I want to assert one thing -- **design patterns are valuable primarily as
a means of establishing a common ground for design.** Surely, the gurus
and "ninjas" of software design today have already discarded the classic
design patterns in lieu of their own sophistications and personal likings,
but the students of today and the newcomers to tomorrow will surely
appreciate the value of knowledge being simplified and abstracted away to
become a design pattern. For me, as a student, and a developer going
forward, although I may not fully understand the exact processes that
determine when a design pattern is optimal, it is surely good to recognize
the wisdom of retrospective analysis that has resulted in these design
patterns being reified and made known to the masses.



