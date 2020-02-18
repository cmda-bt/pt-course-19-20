<!--lint disable no-html-->

# Week 4: Configs & Requirements

## Table of Contents

*   [Comic](#comic)
*   [Slides](#slides)
*   [Assignments](#assignments)
*   [Homework](#homework)

## Comic

[![][comic-cover]][comic-link]

> GeoIP by [**@xkcd**][comic-author].

## Slides

*   [**Slides**][slides-lab]

## Assignments

### Linting (research)

*   **Research**
*   **Time**: 45m

Take about 45 minutes to investigate what 'linting' is: What is it used for? Why is it useful? And try to look for examples.

* Linting is commonly used to enforce a consistent 'code style', what do we mean by that?
* What are common tools for 'linting'?
* How can you integrate these tools in your own project?
* What are the difference between syntax and stylistic errors?
* Investigate [EditorConfig](https://editorconfig.org/). What could be the advantage of using it alongside a linter in your project?

## Homework

### Linting (setup)

*   **Homework**
*   **Time**: 3h
*   **Due**: before lab 5

Based on the research you conducted, set up (multiple) linter(s) in your own project. Ask yourself which tools are useful for your own project. If you're not sure which one to pick, the ones below are solid choices:

* [`editorconfig`](https://editorconfig.org/) - helps developers define and maintain consistent coding styles between different editors and IDEs
* [`eslint`](https://eslint.org/) - pluggable and configurable linting utility for JavaScript
* [`stylelint`](https://stylelint.io/) - modern linter that helps you avoid errors and enforce conventions in your styles
* [`prettier`](https://prettier.io/) - opinionated code formatter
* And so much [more](https://github.com/caramelomartins/awesome-linters#)

Think about what rules you are going to enforce. Most linters offer a recommended rule set which you can easily enable, but it is advisable to configure additional rules that fit your own personal preference. You can use most linters as a script (_npm_ command) in your `package.json`, as an `extension` in your editor or both.

> If you've configured a linter and want to use it in your editor, make sure you also install the corresponding extension!

### Extensions

*   **Homework**
*   **Time**: 2h
*   **Due**: before lab 5

Previously, you've customized the look and feel of your command line. We are going to do the same thing with your code editor. Since you spend quite some time in there it's good to customize it to your own liking. If you are still using Brackets, this might be a good assignment to broaden your horizon or even switch to another code editor such as [`Atom`](https://atom.io/) or [`VS Code`](https://code.visualstudio.com/).

* Try a different color theme! Each editor come with some default options but you can also [browse through](http://color-themes.com/?view=index) lots of other community made ones.
    * In VS Code these are called [color themes](https://code.visualstudio.com/docs/getstarted/themes).
    * [Here](https://atom.io/themes) is a list for Atom, they are usually split between UI and syntax themes.
* Install some extensions to enhance functionality of your editor.
    * [VS Code marketplace](https://marketplace.visualstudio.com/vscode) and Atom [Packages](https://atom.io/packages) are the corresponding pages for extensions for both editors.
* Get the most out of your editor by tweaking your settings and getting to know the shorcuts. Take some time to tweak some settings and learn some keyboard shortcuts. You can read the [Flight Manual](https://flight-manual.atom.io/) for Atom or read the [docs](https://code.visualstudio.com/docs) for VS Code

> Wes and Scott (you might have taken one of their courses) have a good podcast called Syntax where they detail their setups. You can listen to [these episodes](https://syntax.fm/show/012/why-is-everyone-switching-to-vs-code) or look in the show notes for inspiration.

### Requirements List

*   **Homework**
*   **Time**: 1h
*   **Due**: before lab 5

Narrow down your Job Story in specific small functionalities and make a [list of requirements]() your feature should have. You can then apply the [MoSCoW method](https://en.wikipedia.org/wiki/MoSCoW_method) on your list to see which functionalities are must-haves and which ones are enhancements.

#### Methods
*   [Requirements List](http://cmdmethods.nl/cards/stepping-stones/requirement-list)
*   [MoSCoW method](https://en.wikipedia.org/wiki/MoSCoW_method)

### Hand in

1. **Pages:**
Create a [page](https://guides.github.com/features/wikis/#adding-pages) for this week or section of your research on your [GitHub Wiki](https://guides.github.com/features/wikis/#creating-your-wiki).

1. **Push your changes:**
Hand in your research in your repository on GitHub under your username.

## Advanced Matters

As hopefully has become clear from following this weeks lecture; coding standards and code quality encompasses a lot. There are many useful tools available that can aid you in learning how to write good quality code and help maintaining a healthy code base. We've only covered the basics. For those that are interested; here's an overview of some more advanced topics an resources:

* [TypeScript](https://www.typescriptlang.org/) - adds optional static typing to the JavaScript language
* [Software testing](https://en.wikipedia.org/wiki/Software_testing) - an essential aspect of modern software development
* [Design patterns](https://en.wikipedia.org/wiki/Software_design_pattern) -  design patterns are formalized best practices that a software developer can use to solve common problems when designing an application or system

> Don't worry if the above resources do not make much sense to you at this point. They are merely listed for the sake of completeness and as suggestions for those of you who want to learn more about good coding practices. But if you decide to choose for a career in web / software development, it is likely that you will come across these sooner or later.

[bugs]: readme.md#bugs

[comic-cover]: https://imgs.xkcd.com/comics/geoip.png

[comic-link]: https://xkcd.com/713/

[comic-author]: https://xkcd.com

[slides-lab]: https://docs.google.com/presentation/d/1Jaq86Wo5qQkVzeJX2ZY1JoL8T5Lvfq4A7hC01sLNjUM/edit?usp=sharing
