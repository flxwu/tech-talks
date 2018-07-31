---


---

<h1 id="testing-your-tests-quality---introduction-to-mutation-testing">Testing your tests’ quality - Introduction to Mutation Testing</h1>
<h2 id="abstract">Abstract</h2>
<p>Code Testing: Some love it, many hate it. In the end, the only purpose of testing is making your code succeed in all test cases. But ever wondered about the effectiveness of your tests? Well, this talk will explore the art of <em>testing whether your tests fail properly</em> using Mutation Testing, a Unit Testing method that injects Mutants into your code to make your tests fail - but in case they don’t, you should definitely rewrite them.</p>
<h2 id="talk-description">Talk Description</h2>
<p>Everyone talks about code testing being vital to any software engineer, and so does everyone talk about Code Coverage. But Code Coverage doesn’t tell you anything about your tests’ effectiveness and quality, instead it might give you a clue of how many tests in the project don’t have an assertion but only exist for Code Coverage reasons.<br>
Well, meet Mutation Testing: Bugs, so called <em>Mutants</em>, wrong return values for example, are automatically inserted into your code to test whether your tests fail - if they do, the mutant dies, if they pass, the mutant survives. The higher the percentage of mutants killed, the more  <em>effective</em>  your tests are.</p>
<p>In this talk, I will introduce the attendees to this concept and show some live mutation testing in different languages.</p>
<p><strong>Objectives</strong></p>
<ul>
<li>Explain what Mutation testing is and why developers should try it out</li>
<li>Introduce the basic concepts of Mutation Testing</li>
<li>Showcase different Mutators</li>
<li>Do some live Mutation Testing in JavaScript, (Java and PHP).</li>
</ul>
<p><strong>Timing</strong></p>
<ul>
<li>10 minutes intro - What is Mutation testing?</li>
<li>3 minutes basic live example</li>
<li>15 minutes basic concepts and Mutators</li>
<li>10 minutes Live Mutation testing</li>
<li>Remaining time: Q&amp;A</li>
</ul>
<h3 id="pitch">Pitch</h3>
<p>As testing becomes more and more important, I feel like many developers more care about having a high code coverage and therefore a higher tests quantity than quality. But I believe that quality is even more important than quantity, having many tests doesn’t enhance your project in any way if all these tests aren’t written properly or aren’t handling all edge cases.<br>
During my time at Runtastic, a co-worker drew my attention to Mutation Testing and it immediately caught my eye, as I think that Mutation Testing can take Unit Testing to a whole new level.</p>
<h3 id="additional-links">Additional Links</h3>
<ul>
<li>Mutation Testing: <a href="https://www.guru99.com/mutation-testing.html">Complete Guide - Guru99</a></li>
<li><a href="https://www.codeaffine.com/2015/10/05/what-the-heck-is-mutation-testing/">What the Heck Is Mutation Testing?</a></li>
<li>Mutation Testing frameworks:
<ul>
<li><a href="https://stryker-mutator.io/">https://stryker-mutator.io/</a> (JavaScript)</li>
<li><a href="https://github.com/infection/infection">https://github.com/infection/infection</a> (PHP)</li>
<li><a href="http://pitest.org">http://pitest.org</a> (Java)</li>
</ul>
</li>
</ul>

