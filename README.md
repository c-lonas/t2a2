

# T<sup>2</sup>A<sup>2</sup> Stack Example

The following is an excerpt from a blog post on the subject.

# Introduction

Looking for a shiny new tech stack to try out for your next project? This is a fun one. The name is a play on the [T3 stack](https://create.t3.gg/), from which this stack takes some inspiration. Since the T3 stack is modular by nature (as is T<sup>2</sup>A<sup>2</sup>) and both the "T's" in this stack are also in T3, it might be fair to think of it is a T3 variation. But I think Next.js is pretty integral to T3, and swapping out the engine changes the character of the stack significantly.

In this post I'll give a brief explanation of the 'why', and then walk through setting up a simple project to cover the 'how'.

## The Goal

Lightweight | Efficient | Modular | Elegant | Declarative


# The Stack

## 🔒 [TypeScript](https://www.typescriptlang.org/)

Typesafety. Just do it.
Astro supports TypeScript out of the box, set yourself up for success by using it. Compiler errors are better than runtime errors.

<br>

## 🚀 [Astro](https://astro.build/)

Astro, a modern frontend framework, is the engine of the stack. Specializes in static site generation by default, but supports dynamic client-side interaction on an as-needed basis through an 'islands' model, loading javascript where (and only where) it is needed.

All the pieces of the stack have well-documented integration with Astro, facilitating a smooth developer experience.

<br>

## 🌀 [Tailwind](https://tailwindcss.com/)

[This](https://adamwathan.me/css-utility-classes-and-separation-of-concerns/) is the post that finally convinced me to try it, and I have no intention of going  to traditional CSS.
It's remarkable how many problems Tailwind solves beyond just guiding you towards better styles. Time spent coming up with class names that are rarely re-used was a bigger time sink than I realized. Time spent organizing the stylesheet is something I didn't even realize I was doing until I stopped needing to do it. Tailwind syntax doesn't look pretty, but it makes it easier to create pretty webpages. Tailwind trades aesthetic html files that look tidier at first glance for an elegant, declarative workflow that is as easy to read as it is to write once you get the hang of it. I've come to see the 'clean' html files that I used to write as a type of tech debt that has to get paid in your css files. Tailwind gives you transparency.

<br>

## 🗻 [Alpine](https://alpinejs.dev/)

Putting aside the fact that the Alpine.js website is blindingly-white and with no dark mode of which I'm aware, a clear sign it's a tool built by sociopaths, I think Alpine is criminally underused. You don't need to import Home Depot every time you need to change a lightbulb- Alpine is the Swiss Army Knife you can carry around to get stuff done. Versatile, lightweight, elegant, it complements the stack perfectly. 👨‍🍳 💋

<br>

The whole is more than the sum of the parts. Taken together, this stack encourages a utility-first, declarative workflow that lets you avoid overhead without needing to constantly re-invent the wheel or clutter your codebase with boilerplate. Using Alpine and Tailwind together to add interaction and styles to your Astro components helps you to code and design your elements in the way that you want users to interact with them.

<br>

# ...

If you'd like to read the rest of the blog post, which contains step by step instructions for building the simple web app contained in this repo, follow this link (coming soon).

This is what the project looks like when deployed.
![FinalResultT2A2Example](/AstroTailwindAlpine.gif)