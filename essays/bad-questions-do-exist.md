---
layout: essay
type: essay
title: Bad Questions Do Exist
date: 2017-09-07
labels:
  - Questions
  - Stack Overflow
  - Software Engineering
  - Other
---

<center><figure>
    <img
        src="https://c2.staticflickr.com/4/3091/2711755476_8975dd43ea.jpg"
        alt="Warning! If the help desk thinks your question is stupid, we will set you on fire!">
    <figcaption>"Sometimes, questions are just bad."</figcaption>
</figure> </center>


Most software engineering errors and problems have very specific and exact
conditions -- perhaps the user made a typo, or the user is missing a line from
a configuration file, or the user is using a wrong version of a library.
Information is easy to get due to the low barrier of effort required when
searching for it on the Internet. Questions that leave out critical diagnostic
information/context or show a lack of effort trying to get the solution alone
bring people to a single reaction:

# The Ugly

If information is so easy to get and the user is not getting it -- then the
most probable options are:

 - They’re incompetent
 - They’re lazy

And both of these piss people off.

In “[How to ask questions the Smart 
Way](http://www.catb.org/esr/faqs/smart-questions.html),” Eric Raymond tries to
show people (with a no-nonsense attitude) what “smart” and “stupid” questions
are in order to equip people to ask questions that have a higher chance of
getting good answers.

Raymond basically says that good questions are clear, compact, well-composed,
detailed, and relevant. Good questions are asked respectfully, demonstrate clear
effort on the asker’s part to solve it beforehand, and make it easy for people
to diagnose the problem and answer in a clear, concise, and precise manner. Good
questions also do not suggest that the asker already knows the answer (and are,
therefore, not just uselessly testing people and wasting people’s time).

Essentially, Raymond says, “Yes, bad questions do exist, and this is how you
don’t write one.”

Here, I’ve highlighted two questions: a good one and a bad one.

# The Good

[This smart 
question](https://stackoverflow.com/questions/11227809/why-is-it-faster-to-process-a-sorted-array-than-an-unsorted-array)
is currently the highest voted question on Stack Overflow.  And, in my opinion,
it is an extremely interesting, well-written question that has
one of the best answers on Stack Overflow.

The question:
- Keeps it clear, compact, and yet, detailed
- Creates a [small, self-contained,
correct example program](http://sscce.org/)
- Benchmarks the program with metrics
to clearly show the problem
- Replicates the program in Java to show that the asker tried
investigating the problem; and, it also shows that the problem is possibly
language-agnostic in cause
- Finishes with a short discussion and more pointed questions
without assuming its own guesses are the right answers. (In fact, he makes
a guess but then discredits it by saying it was “silly” given the
circumstances.)

To me, the question asker comes across as smart and hard-working -- exactly what
Raymond wants.

The accepted answer there is extremely well-written as well (and even includes
pictures!)

It:
- Weaves a clear and relevant intro narrative for the answer to prepare
understanding
- Uses the narrative as an analogy for branch prediction (with
parallel structure -- a recommended technique for clarity in writing!)
- Explains branch prediction since it is necessary to understand how it
affects the problem (and, it builds the bridge of prerequisite knowledge to 
come to the final answer)
- Includes a visualization to illustrate reasoning
- Shows a way to eliminate the issue by removing the branch
- Includes metrics to show that the issue is truly removed
- Was updated continuously to show how different
compilers try to also mitigate the problem

Clearly, a lot of finesse and effort went into this answer;
that’s why it’s the most upvoted answer on this question.

One interesting thing is that the there is a shorter, more concise answer that
simply says “branch prediction” and a few more phrases -- but, it’s not as
well-rated. I think that, although it is not a stupid answer, it doesn’t have
the same amount of detail and effort put into it as the accepted one.

# The Bad

Now then -- [this
question](https://stackoverflow.com/questions/21864038/c-wxwidgets-tdm-gcc-compiler-undefined-reference-to-winmain-in-drive-h)
is clearly a doozy. It’s bad.

First of all:

> undefined reference to WinMain in drive H:\?

“Undefined reference” is one of the most basic compilation errors in C++ (it
means that you forgot to define or include something). So, we can already tell
that the question asker is very, very new to the language (and perhaps,
programming, in general).

Second of all:

> “Is this an error about H:\ being a non-compiled version of C:\ or so?”

The question asker assumes that they already know the solution -- it is very
direct in implying, “oh, *this* is the answer” (although it clearly wasn’t).

The real solution? The fix was to add a single line that -- if the user went
through the [wxWidgets
tutorial](http://docs.wxwidgets.org/3.1/overview_helloworld.html), they would
quickly find out that wxWidgets implements the `main()` function in a special
defined macro, and thus -- all normal wxWidgets programs must include to work.

In other words, the question asker failed to
“read the f\*\*\*\*\*\* manual” (RTFM).

# Getting Personal

This is a very important topic for me because it’s a personal one -- the “bad”
question supplied here is actually mine. It was one of the questions that
resulted in that account getting question banned from Stack Overflow (and is also
one of the reasons why I now go by VermillionAzure on there).

Over the few years I’ve been part of the Stack Overflow community, I’ve
learned out how to ask better questions and have learned to provide more effort
when trying to meet the standards for Stack Overflow’s questions. Raymond’s
words really resonate with my personal experience; so, although I may not like
the bluntness of his writing style, Raymond is really saying the right things
on how to write the right questions -- and on how to avoid writing the wrong ones.


