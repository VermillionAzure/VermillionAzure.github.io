---
layout: essay
type: essay
title: A Vision of Project Management
date: 2017-09-01
labels:
  - Engineering
  - Project Management
---

**Doing a team project without knowing how to manage is a project is a recipe for disaster.**

But that's exactly what I did last semester, inviting a team of 12 other people to work on
the Transpiler Project with me -- my senior project enlargened to support additional
people.

Here are my major takeaways from the experience.

## The vision must be rock-solid

...and I really do mean ***rock-solid***. Last semester (and even before),
I spent a significant amount of time reading about Scheme, what a transpiler
was, how interpreters worked, and how Scheme had unique problems that
do not show up in other languages. Features like `(call/cc)` and macros
told me that I essentially had picked an extremely hard language to 
correctly implement -- which also meant I had fallen into a trap.

Additionally, I was not well-equipped to undersatnding the theory behind
the design of the major components and C++ classes needed for our
evaluator design -- we have 3 major rewrites -- one for choosing the correct
sum type variant to help represent Scheme data, one for rewriting
evaluation to take account that primitive keywords could be shadowed by
new ones, and finally, one for allowing `(call/cc)` and macros to be
implemented -- a rewrite that is still on-going to this day.

## The team structure must be strong

I didn't know how the teams should be put together because I didn't understand
how the work would ultimately be divided up. There were 3 teams:

- Design/Testing
- Core Systems
- Parsing/IO

### Design/Testing, or, Crash/Burn

This team had absolutely no direction. I thought we could possibly
incorporate some algorithm analysis and make this a sort of QA and
code reviewing team. This would've worked if the team had consisted
of well-experienced programmers who were also well-equipped to step in
and code when needed. Instead, the team was setup to consist of entirely
sophomores. This was a clear mistake. The result? The team ended up being
idle for 7 weeks and dismantled. It is no mistake that 6/7 people who were
on this team left the project.

### Core Systems

Core Systems was a really great team -- they meshed well together, and
actively coded at every meeting.

It would've been great if their work wasn't invalidated by every
single rewrite.

As Core Systems was the most important team, I also made sure the strongest
people were on it. The result is that we had a basic REPL working at
the end of the semester. However, I was also shocked to find out that 3/5
people on this team had left. There were indeed deeper problems (the
people/project management side) that probably left people wanting
for more structure.

### Parsing/IO

Parsing/IO was a semi-neglected team -- they were in charge of
implementing the parsing rules for Scheme, but they first had to learn
basic parsing theory, starting with regular expressions and then
building up to context-free languages and recursive descent parsing.

They did well -- when they were actually assigned tasks. Unfortunately,
as project manager, they felt a bit unproductive since there was no
clear path to learning these complex topics on their own, unenforced
by any learning in automata from past classes.

## Accountability is life/death

Guilt/Fear is a powerful motivator. Metrics is a tool that can get
people into tangibly measuring their own performance.

Last semester, we did not use task points or user stories. Our project
management tool of choice was Trello, but we failed to use it in a
Kanban style or integrate it with Scrum. Now that we have, I find that
people are more apt to keep on their toes and there is a sort of
gravity that wasn't there before. Suddenly, work is very real! And
your work is being depended on by other people who need to progress in
the project!

This problem of being **blocked** on a task is a key reason why
it is okay to sort of "drive" people to finish tasks -- accountability
is key for productivity, and not keeping it in line means everyone
falls out of line and starts to not connect the dots.

## So what?

I learned that managing a large project requires a strong vision
and structure, and is, in some ways, an extension of yourself. It's like
junior team members need to be nurtured and watered with the correct
sit-down sessions and resources, and their performance is based on
the way you correctly perform yourself in leading them.

Like how a kendo practicioneer or a fencing practictioneer will consider
the sword as an extension of their arm, a team is an extension of
the team leader's mind. Through either just pure awesomeness or hard
training, a team can be led to more effective paths and greater
heights if they just have the right processes and values in mind.
