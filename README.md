# Functional Programming Exercises

Introductory exercises on functional programming concepts using JavaScript.

Base repository for the [Functional Programming: Concepts and Exercises](https://github.com/GuildCrafts/web-development-js/issues/110) goal.

## Getting Started

The exercises are organized into subdirectories. Peek around the file structure to get a sense for how things are laid out.

Then, when you're ready to start:

1. Fork this repo
2. Clone your fork
3. Install npm packages with `npm install`
4. Run your tests with `npm test`
5. Work on an exercise
6. Make the tests pass
7. Repeat steps 4-6 for big fun

## Description

This goal provides an introduction to functional programming concepts using JavaScript.

You'll practice these concepts with a series of reinforcement exercises from the [Mostly Adequate Guide to Functional Programming][mostly-adequate-guide] and a handful of automated challenges on [CodeWars][codewars-chals].

Fork the [fp-exercises][fp-exercises] repo, and use the fork as your artifact.

This repo has the exercises and tests for the Mostly Adequate Guide already there so you can get started right away. When you work on the CodeWars katas, just copy your solution into the `code-wars` folder of the repo so that your code can be reviewed and so that you can reference it in the future.

If this goal is too advanced for you, a good pre-requisite goal is @Jusdev89's [Common JS Utility Functions - Lodash](./37-Common_JS_Utility_Functions-Lodash.md).

## Context

Functional programming patterns are becoming increasingly popular in the web development community. Using these patterns results in code that is more adaptable and flexible, less buggy, and more scalable.

The article [The Two Pillars of JavaScript — Pt 2: Functional Programming](https://medium.com/javascript-scene/the-two-pillars-of-javascript-pt-2-functional-programming-a63aa53a41a4#.p9gfmzfel) goes into many of the reasons why you might want to consider learning how to write JavaScript as a functional programmer would.

## Specifications

- [X] Read the [Mostly Adequate Guide to Functional Programming][mostly-adequate-guide] through Chapter 8: Tupperware
- [X] Exercises from the Mostly Adequate Guide are completed and included in the artifact repo
  - [X] [Chapter 4 Exercises](https://drboolean.gitbooks.io/mostly-adequate-guide/content/ch4.html#exercises) completed and all tests are passing
  - [X] [Chapter 5 Exercises](https://drboolean.gitbooks.io/mostly-adequate-guide/content/ch5.html#exercises) completed and all tests are passing
  - [X] [Chapter 8 Exercises](https://drboolean.gitbooks.io/mostly-adequate-guide/content/ch8.html#exercises) completed and all tests are passing
- [X] [5 Functional Programming katas][codewars-chals] from CodeWars are completed and added to the `code-wars` folder of your artifact repo
- [X] The artifact produced is properly licensed, preferably with the [MIT license][mit-license].

A just a heads up on CodeWars: you're required to answer a couple of super basic JS questions to sign up for CodeWars, and you need to be signed up for the links to work.

### Stretch

- [ ] Additional 5 katas from [CodeWars][codewars-chals] are completed and added to your artifact repo
- [ ] Refactor a previous project to use functional programming patterns (strongly recommended to review the Mostly Adequate Guide before starting)
  - [ ] Add links to your refactoring PRs in a `refactoring.md` file in your artifact repo

## Quality Rubric

**Clean code and commit messages**
- Code is well formatted with proper spacing and indentation. [30 points]
- Descriptive, well-named functions, variables, files, etc. [40 points]

**Good project management**
- Commit messages are concise and descriptive. [10 points]
- All features are added via pull requests. [10 points]
- Every pull request has a description summarizing the changes made. [10 points]

## Resources

- [Mostly Adequate Guide ][mostly-adequate-guide] book
- [CodeWars functional programming in JS katas][codewars-chals]

Articles, guides, and courses

- [So You Want to Be a Functional Programmer](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-1-1f15e387e536)
- [Eloquent JavaScript Chapter 6: Functional Programming](http://eloquentjavascript.net/1st_edition/chapter6.html)
- [Functors, Applicatives, And Monads In Pictures](http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html)
- [Category Theory for Programmers](https://bartoszmilewski.com/2014/10/28/category-theory-for-programmers-the-preface/) (advanced)
- [Professor Frisby Introduces Composable Functional JavaScript](https://egghead.io/courses/professor-frisby-introduces-composable-functional-javascript)

Tools and libraries

- [Ramda](http://ramdajs.com/docs/) - similar to lodash, but for functional programming
- [Ramda REPL](http://ramdajs.com/repl/) (read-evaluate-print-loop)


[mit-license]: https://opensource.org/licenses/MIT
[fp-exercises]: https://github.com/GuildCrafts/functional-programming-exercises
[mostly-adequate-guide]: https://drboolean.gitbooks.io/mostly-adequate-guide/content/
[codewars-chals]: https://www.codewars.com/kata/search/javascript?q=&tags=Functional+Programming&beta=false
