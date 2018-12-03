# CSS in JS: The Future of Component-Based Styling?

# Abstract

You probably already heard the term "CSS-in-JS". Maybe you just ignored it, or you thought "Well, I am perfectly fine with writing regular CSS". Why is it a thing then? Because it solves a lot of problems that you might stumble upon while writing regular CSS. Writing CSS in JavaScript is not a guaranteed productivity-boost, but without knowing the concept and the reasons behind it you might be missing out a whole new perspective on CSS. In this talk, I am going to show what writing CSS through JavaScript means, which problems it solves, and also showcase it in a live demo.

# Description

CSS has already frustrated many developers, and I personally have to admit that I just don't have a broad knowledge of CSS. But CSS also frustrates experienced CSS devs over and over again, and that might also be because CSS as a language has its limitations and therefore problems like global namespacing and styling conflicts. By adopting CSS styles in JavaScript, we can write plain JavaScript that translates to normal CSS. This gives us the programmatic affordances of JavaScript and thus benefits of something like a CSS pre-processor (variables, mixins, and functions). It also enables us to **Think in Components** - something that has been talked about a lot recently, especially in the React world. No longer do you have to maintain bunch of stylesheets. CSS-in-JS abstracts the CSS model to the component level, rather than the document level. And this is just one example - there are many other problems with CSS that CSS-in-JS solves.

In this talk, I will be presenting these problems, how JavaScript can solve them, and showcase writing CSS in JavaScript in a live demo.

**Objectives**

- Present the concept and thoughts behind CSS in JavaScript
- Demonstrate some problems of CSS that CSS-in-JS solves
- Showcase a live demo of CSS-in-JS in JSS, React's Stylesheets/styled-components, and Aphrodite.

**Timing**

- 3 minutes introduction
- 10 minutes demo
- 15 minutes concepts & problems that CSS-in-JS solves
- 10 minutes demo in common frameworks/use cases like React