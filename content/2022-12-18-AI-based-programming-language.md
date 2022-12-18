+++
title = "AI based natural programming language"
date = 2022-12-18

[taxonomies]
tags = ["AI", "language"]
+++

<br />

## Esoteric programming languages
For the past year or so, I've been looking at language development, and growing
as a member of the programming language development and design community
([see here](http://proglangdesign.net/)).

I've learned a lot of things in this time period, but the thing that was
probably the most fascinating and interesting was the concept of 'esoteric
languages'. I looked through a lot of different concepts
([lolcode](https://esolangs.org/wiki/LOLCODE), [brainfuck](https://esolangs.org/wiki/Brainfuck),
[velato](https://esolangs.org/wiki/Velato), [piet](https://esolangs.org/wiki/Piet),
and more...), all of whom use different mediums (textual programming languages, .png file programming languages, and even midi file programming languages).

But they also defer in paradigm, you have the classic [procedural programming language](https://en.wikipedia.org/wiki/Procedural_programming), ofcourse you also have [OOP languages](https://en.wikipedia.org/wiki/Object-oriented_programming), and [functional programming languages](https://en.wikipedia.org/wiki/Functional_programming).

<br />

## AI code generation
But what will be the future of software development? What will future programs be written in? How will they defer from programs nowadays? afterall, programs from 1970 (assembly languages and other low-level languages) looked radically different from what we know and love today.

One of the major recent development that is casting a dark shadow over the realm
of software development is AI assisted code generation. You give it a text, often
in the form of a comment, and the system will analyze the text, and return you with
the fitting code that you can then accept, or deny.

One such systems is 'Github Copilot' (which [I personally use](/copilot-thoughts/), the 100 euro a year is very much worth it).
Github Copilot is Github's code generation product that runs on Open-Ai's GPT-3 and is trained on millions of lines of open source github-hosted code.

Combining the idea of `AI code generation` and `Esoteric programming languages`,
I came up with an idea of a textual esoteric programming language that uses AI code
generation to come up with the entire program, and then run it.

An example of a script written in such language might look like this:

```
ask what the users name is.
greet the user by saying 'well hello there {insert name}'
```

If I input the name `james`, the program would then respond with `well hello there james`.

This way, you could write an entire program using just natural speaking language.
It sounds like a very esoteric idea right now, but who knows, it might be a popular
scripting paradigm in the (near) future.

<br />

## Positives
This idea might be a very good idea for a few different reasons. First off, programs
that are written using this technique are extremely easy to understand when looking at
isolated lines of code. The code itself is essential, and quite literally 'self documenting'.

This aspect of the language brings us to the second point, which is that it is very
easy to be used by non programmers to, for example: automate some task, or do something
that would take a human ages like sorting/editing thousands of files.

The language would essentially be a scripting language on steroids.

<br />

## Negatives
On the negative side, this idea has a lot of major flaws: the code would quickly become
unmaintainable in large codebases, as the code would be very hard to read and understand
when looking at the entire program.

One line might be easy to understand for even non-programmers, but when looking at the
entire codebase including million of lines of natural language, it would be practically
impossible to find that one bug that is causing some logic error.

Another major flaw is that (for now) these text-to-code AI are non-deterministic, meaning
that the same text input will not always result in the same code output. Combining this with
the fact that AI might (for now) make mistakes occasionally, often caused by unclear explaining
in the natural language.

This would mean that a program might change it's behavior from one run/build to another, introducing a horrible amount of near-impossible to fix inconsistencies

```
find the file named something.txt in the current directory
write 'hello world' to the file
```

This code might sometimes replace the contents of the file with 'hello world', and sometimes
it might append it instead, it would be impossible to know which one it will do.

<br />

## Conclusion
Even tho we might see technology like this in the future, I don't think it will catch on
into mainstream production level programming. Big companies with complex software products
simply cant handle the huge scalability-handycap that this idea has, and the codebase would
quickly become an un-understandable mess.

However, for individuals that are not into programming and/or want to quickly create some
script to automize some task, this might be a very good idea, for example, a program like this:

```
open the downloads folder and look what files are in it.

for each file, categorize what type of file it is by looking
at the file extension. for example:
    - .jpg, .jpeg, .gif, .png will all become 'images'
    - .mp4, .avi, .mkv, .mov will all become 'videos'

look at the extension of the file in it,
and copy it to C://organized_downloads/{category}/
delete the original file in the downloads folder
```

<br />

> Artificial intelligence is a great tool to be used as a compensation for our natural stupidity