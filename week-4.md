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

### EditorConfig (research)

* **Research**
* **Time**: 20m

Take 15 minutes to read the [home page](https://editorconfig.org/) of _EditorConfig_ and try to answer the following questions for yourself:

* What is the purpose of the `.editorconfig` file?
* What do I need to do / configure before I can use _EditorConfig_ in my project? (e.g. Does my code editor support _EditorConfig_ out of the box or do I need to install a specific package?)
* What rules in particular are important to ensure that me and my team mates maintain a consistent coding style throughout the project? (hint: Unix vs. Windows line endings, tabs vs. spaces)

### Linting (research)

*   **Research**
*   **Time**: 0:45h
*   **Goals**: subgoal 5

Take about 0:45h to investigate what 'linting' is: what is it used for, why is it useful and try to look for examples.

* Linting is commonly used to enforce consistent 'code quality', what do we mean by that?
* What are common tools for 'linting'?
* How can you implement these tools in your own project?
* What are the difference between syntax and stylistic errors?

## Homework

### EditorConfig

* **Homework**
* **Time**: 1h
* **Due**: before lab 5

In class you have already researched the purpose of _EditorConfig_. Now it is time to integrate it into your project. Add an `.editorconfig` in the root of your project and define rules that are relevant to your project. A decent basic `.editorconfig`, which doesn't need much (if any) editing can be found [here](https://raw.githubusercontent.com/laravel/laravel/master/.editorconfig).

> **_NOTE:_** There is some overlap between rules that _EditorConfig_ offers and rules that a linter like _ESLint_ offers, which potentially can lead to direct and / or indirect confusion if specified simultaneously. Hence, it is recommended to only configure _EditorConfig_ rules that handle file formatting (e.g. line endings, inserting or not inserting a final newline, setting the indent style and size).

### Linting (implementation)

*   **Homework**
*   **Time**: 3h
*   **Goals**: subgoal 5

Based on the research you conducted setup a (or multiple) linters in your own project. Ask yourself which tools are useful for your own project. If you're not sure which one to pick, the ones below are solid choices:

* [`eslint`](https://eslint.org/) - pluggable linting utility for JavaScript
* [`stylelint`](https://stylelint.io/) - modern linter that helps you avoid errors and enforce conventions in your styles
* [`prettier`](https://prettier.io/) - opinionated code formatter
* And so much [more](https://github.com/caramelomartins/awesome-linters#)

Think about what rules you are going to enforce. Most linters requires you to configure those on your own. You can use linters most linters as script in your `package.json` or as an `extension` in your editor.

> If you've configured a linter and want to use it in your editor, make sure you also install the corresponding extension!

### Extensions

*   **Homework**
*   **Time**: 2h
*   **Goals**: subgoal 5

Previously you've customized the look and feel of your command line. We are going to do the same thing with your code editor. Since you spend quite some time in there it's good to customize it to your own liking. If you are still using Brackets, this might be a good assignment to broaden your horizon or even switch to another code editor such as [`Atom`](https://atom.io/) or [`VS Code`](https://code.visualstudio.com/).

* Try a different color theme! Each editor come with some default options but you can also [browse through](http://color-themes.com/?view=index) lots of other community made ones.
    * In VS Code these are called [color themes](https://code.visualstudio.com/docs/getstarted/themes).
    * [Here](https://atom.io/themes) is a list for Atom, they are usually split between UI and syntax themes.
* Install some extensions to enhance functionality of your editor.
    * [VS Code marketplace](https://marketplace.visualstudio.com/vscode) and Atom [Packages](https://atom.io/packages) are the corresponding pages for extensions for both editors.
* Get the most out of your edidtor by tweaking your settings and getting to know the shorcuts. Take some time to tweak some settings and learn some keyboard shortcuts. You can read the [Flight Manual](https://flight-manual.atom.io/) for Atom or read the [docs](https://code.visualstudio.com/docs) for VS Code

> Wes and Scott (you might have taken one of their courses) have a good podcast called Syntax where they detail their setups. You can listen to [these episodes](https://syntax.fm/show/012/why-is-everyone-switching-to-vs-code) or look in the show notes for inspiration.

### Usability Test

*   **Homework**
*   **Time**: 1h
*   **Goals**: subgoal 5

You already started working on your interface. You might already have some sketches or written some views, partials or components with a templating engine. Collect feedback on your interface and Static HTML. Let other students test your interface and give you feedback.

#### Methods
*   [Usability Test](http://cmdmethods.nl/cards/lab/usability-testing)

### Requirements List

*   **Homework**
*   **Time**: 1h
*   **Goals**: subgoal 5

Narrow down your Job Story in specific small functionalities and make a [list of requirements]() your feature should have. You can then apply the [MoSCoW method](https://en.wikipedia.org/wiki/MoSCoW_method) on your list to see which functionalities are must-haves and which ones are enhancements.

#### Methods
*   [Requirements List](http://cmdmethods.nl/cards/stepping-stones/requirement-list)
*   [MoSCoW method](https://en.wikipedia.org/wiki/MoSCoW_method)

### Hand in

1. **Pages:**
Create a [page](https://guides.github.com/features/wikis/#adding-pages) for this week or section of your research on your [GitHub Wiki](https://guides.github.com/features/wikis/#creating-your-wiki).

1. **Push your changes:**
Hand in your research in your repository on GitHub under your username.

[bugs]: readme.md#bugs

[comic-cover]: https://imgs.xkcd.com/comics/geoip.png

[comic-link]: https://xkcd.com/713/

[comic-author]: https://xkcd.com

[slides-lab]: https://docs.google.com/presentation/d/1Jaq86Wo5qQkVzeJX2ZY1JoL8T5Lvfq4A7hC01sLNjUM/edit?usp=sharing
