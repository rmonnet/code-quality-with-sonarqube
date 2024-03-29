# Java 8 New Features

This repository includes a presentation on sonarqube features.

## license

The presentation is released under the [Creative Commons Attribution 4.0 Int. License](http://creativecommons.org/licenses/by/4.0/)

Tools listed below are released under their own license.

## How to build

The slides are built using markdown and a minimalist toolset:

Slides content is in `code-quality-with-sonarqube.md`.

The perl script `remark.pl` will convert the markdown file to an html file using [remarkjs](https://remarkjs.com) as the presentation engine. The result is a single `code-quality-with-somarqube.html` file. That is all you need to present (as long as you have an internet connection).

If you want to generate PDF from the remark slides, my recommendation is to use [decktape](https://github.com/astefanutti/decktape). You will need to have `node.js` and a `C++` compiler installed to use it. The PDF included in the repository was generated this way.

## Need something more sophisticated

If you are unhappy with the minimalist approach, you can try something like [backslide](https://github.com/sinedied/backslide). `Backslide` can generate html and PDF out of the markdown file but you will first need to install nodejs and have access to a C++ compiler.

The only difference is that you will get `backslide` custom style instead of `remarkjs` default one.

Before you do, I'll encourage you to read about Doug McIlroy's programming philosophy ("The real hero of programming is the one who writes negative code"). A summary of its challenge to Knuth can be found [here](http://www.leancrew.com/all-this/2011/12/more-shell-less-egg/)
.
