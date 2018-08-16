# Testing your tests’ quality - Introduction to Mutation Testing

## Abstract

Code Testing: Some love it, many hate it. In the end, the only purpose of testing is making your code succeed in all test cases. But ever wondered about the effectiveness of your tests? Well, this talk will explore the art of *testing whether your tests fail properly* using Mutation Testing, a Unit Testing method that injects Mutants into your code to make your tests fail - but in case they don’t, you should definitely rewrite them.

## Talk Description

Everyone talks about code testing being vital to any software engineer, and so does everyone talk about Code Coverage. But Code Coverage doesn’t tell you anything about your tests’ effectiveness and quality, instead it might give you a clue of how many tests in the project don’t have an assertion but only exist for Code Coverage reasons. Well, meet Mutation Testing: Bugs, so called *Mutants*, wrong return values for example, are automatically inserted into your code to test whether your tests fail - if they do, the mutant dies, if they pass, the mutant survives. The higher the percentage of mutants killed, the more *effective* your tests are.

In this talk, I will introduce the attendees to this concept and show some live mutation testing in different languages.

**Objectives** 

- Explain what Mutation testing is and why developers should try it out
- Introduce the basic concepts of Mutation Testing
- Showcase different Mutators
- Do some live Mutation Testing in JavaScript, (Java and PHP).

**Timing**

- 10 minutes intro - What is Mutation testing?
- 3 minutes basic live example
- 15 minutes basic concepts and Mutators
- 10 minutes Live Mutation testing
- Remaining time: Q&A

## Pitch

As testing becomes more and more important, I feel like many developers more care about having a high code coverage and therefore a higher tests quantity than quality. But I believe that quality is even more important than quantity, having many tests doesn’t enhance your project in any way if all these tests aren’t written properly or aren’t handling all edge cases. During my time at Runtastic, a co-worker drew my attention to Mutation Testing and it immediately caught my eye, as I think that Mutation Testing can take Unit Testing to a whole new level.

## Additional Links

- Mutation Testing: [Complete Guide - Guru99](https://www.guru99.com/mutation-testing.html)
- [What the Heck Is Mutation Testing?](https://www.codeaffine.com/2015/10/05/what-the-heck-is-mutation-testing/)
- Mutation Testing frameworks:
  - https://stryker-mutator.io/ (JavaScript)
  - https://github.com/infection/infection (PHP)
  - http://pitest.org (Java)