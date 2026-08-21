---
title: The ART Book...Online!
subtitle: Online posts and exercises for the ART Book
layout: single
toc: true
toc_icon: question
toc_sticky: true

# Date
date: 2025-12-1
# Date updated
lastmod: 2025-12-1

categories: ["papers"]
tags: ["books", "ML", "ART"]
# summary: Presentation for the SIAM 2025 conference on dynamical systems.
featured: true

excerpt: "A place for hosting material on the book on Adaptive Resonance Theory (ART) algorithms and their applications."

header:
    teaser: "/assets/posts/book.png"
    caption: "ART Book"
---

## TLDR; Here's the Link!

Don't want to read the context?
Neither do I, and I wrote the dang post!
Anyway, here is the [link to The ART Book Website](https://art-book-online.github.io)

## Some Background

I have been working on a draft of a book concerning Adaptive Resonance Theory (ART) algorithms and how to get hands-on with using them, which in the meantime has been codenamed:

{: .notice--info}
**The ART Book**

Really innovative stuff, right?
Well, the name will probably be workshopped up until the last minute of submission of the manuscript, so in the meantime, codename *The ART Book* remains for now!

One of the things that I have aimed to do while writing the book is to have hands-on exercises as one of the main vehicles of teaching the material, especially since the subject matter is a heavy mix of algorithms and mathematics.
One ubiquitous method of providing such interactive examples in a pedagogical manner in the field of machine learning is through notebooks (e.g., Jupyter, IPython, marimo, Pluto.jl, etc.).
As I was developing these notebooks bothin within and externally to *The ART Book*, I thought to myself, "wouldn't it be convenient to host these on a website?"
Lots of great books provide exercises and addendums to the material in the form of a website hosting notebooks and documentation, such as the great [Neuronal Dynamics](https://neuronaldynamics.epfl.ch) by Gurstner et al.

Adding this material to my personal website seemed silly, since this is a place mainly for self-indulgent blog posts and resume-building material, so I came to the conclusion that I should build a new website from scratch for the book!

## The ART Book...Online!

And there you have it, a [website for posts and notebooks relevant to getting hands-on with the material of The ART Book](https://art-book-online.github.io)!

Right now, the site is bare bones; I've used a similar Jekyll theme for the website as on my own personal page, and I've organized posts and notebooks into a set of card links with images and previews.
As the site grows alongside the writing of the ART book itself, I'll tinker with better ways of presenting the information (e.g., sorting notebooks by relevant chapters, etc.).

In the meantime, feel free to explore the notebooks on the website!
I've written several that go through basic programmatic implementations and derivations of key functionalities of `FuzzyART` and its use in benchmark unsupervised (clustering) and supervised (classification) learning scenarios.
