# Book Survey

A survey of beginner programming books and their syllabi.

## Learn Ruby the hard way

From Learn Ruby the Hard Way

Chapter 1 ordering of topics:

* First script: lots of print statements
* Interpolation strings
* Put math in interpolation strings
* Add variables to hold the math
* How about a “x”.repeat() ? (Ruby syntax is cute for this.)
* Escape characters and unicode

All this could be done with alert(), console.log() and document.write().

Functions are introduced after scripts. They start with argv as parameters. They run that, and then, in the next lesson, they introduce functions with params. "Just think of a function as another 'script'"

Idea: first read the query params from the url in to use them in a script. Then make functions. And use the idea of params to think “mini-script”

    const searchParams = new URLSearchParams(window.location.search);
    searchParams.get("q");

Idea: Maybe just start with lots of adding elements and objects? That is what JS is for! Randomly adding or changing things with style or document.write or document.createElement

Just to make everything as practical as possible before diving into JS as a language.
