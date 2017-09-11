---
layout: essay
type: essay
title: Reflection on JavaScript
date: 2017-09-10
labels:
  - JavaScript
  - Programming Langauges
  - Opinion
---

<center>
<h2><a href="https://www.destroyallsoftware.com/talks/wat" style="color:red;">Wat.</a></h2>
</center>

*Okay, now we've got that out of the way...*

JavaScript gets a lot of bad rep.

- [Medium - JavaScript is a Dysfunctional Programming Language](https://medium.com/javascript-non-grata/javascript-is-a-dysfunctional-programming-language-a1f4866e186f)
- [JavaScript: The World's Most Misunderstood Programming Language](http://www.crockford.com/javascript/javascript.html)
- [The Top 10 Things Wrong with JavaScript](https://medium.com/javascript-non-grata/the-top-10-things-wrong-with-javascript-58f440d6b3d8)

And I do agree with some things, out of beginner's ignorance:

- It can be challenging to choose what frameworks/parts you want to tackle (backbone? Angular? React? Meteor? Angular 2?)
- The ecosystem can be kind of unstable sometimes (see: [NPM's `leftpad`](https://www.theregister.co.uk/2016/03/23/npm_left_pad_chaos/))
- Smaller things like `==` and `===` are inconvenient and create mental noise

But on the other hand,

- JavaScript inherits parts of Lisp and Smalltalk in its genes
    - Closures, part homoiconity, first-class functions from Lisp
    - OOP, "everything is an object," dynamic typing and on-the-fly reflection from Smalltalk
- JavaScript is easy to get started with
    - NPM makes it easy to get things setup on the back-end
    - The deployment cycle can be short with the infrastructure
      already there on many hosting sites
    - The development and testing cycle can be short with
      JavaScript built into browsers for JavaScript front-end work

I think that the OOP modeling in JavaScript is a bit strange -- it
seems like an afterthought to the language that was later formalized
by later standards in ECMAScript. The fact that OOP is supported
by just convention and closures makes "object types" easy to create
but hard to formalize and verify without more work.

One thing I'd like to say is that I wouldn't want to directly create a
large-application in JavaScript because it lacks statis typing. I like
static typing because it essentially does "proofs" of certain parts of
the program for you, or it sort of automatically checks parts of your
program for you (e.g. + is being performed on two numeric types). Instead,
I would go for a statically-checked version of JavaScript, like TypeScript.

Overall, JavaScript is sort of refreshing. Once you look past the
trivially confusing and bad stuff, it is a light language that is easy
to jump into and develop with.





