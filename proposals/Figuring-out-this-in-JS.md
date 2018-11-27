# Figuring out `this` in JavaScript and why it's not `that` 

### Abstract
The concept of “this” can be thoroughly confusing for both new and seasoned JavaScript developers alike. This talk aims to elucidate _this_ in its entirety, so that you'll never have to worry about that part of JavaScript again. We will understand how to use _this_ correctly in every scenario, including the ticklish situations where it usually proves most elusive. We all use _this_ in constructors and all kinds of frameworks, but it's never truly explained. So, let's change that!

### Description
Whether at home, at work or with the family, there is no way to avoid saying 'this'. In some cases, it's the only pronoun you can use to refer to a particular thing or thought. It's one of the first words our kids learn to use everyday - yet we Software Developers often never learn about the right usage of 'this'. Similar to its usage in spoken languages, we use 'this' in JavaScript to refer to an object. But this object is dynamic, which leads to 'this' referring to different objects in different cases: It can refer to the some global object, it can be used inside methods on objects, in function contexts, or in 'new' declarations. If we only take on 'this' inside methods, we still have to differentiate between methods on an object, a nested object or in an arrow function. Let's conquer JavaScript’s 'this', because understanding and using it properly can be very powerful!

<br><br><br>

##### Combined Description
The concept of 'this' can be thoroughly confusing for both new and seasoned JavaScript developers alike. While there is no doubt that we cannot avoid using ‘this’ in our natural language and daily life, we as Software Developers often never learn about the right usage of ‘this’. Similar to its usage in spoken languages, we use ‘this’ in JavaScript to refer to an object. But this object is dynamic, which leads to ‘this’ referring to different objects in different cases: It can refer to the some global object, it can be used inside methods on objects, in function contexts, or in ‘new’ declarations. If we only take on ‘this’ inside methods, we still have to differentiate between methods on an object, a nested object or in an arrow function.
This talk aims to elucidate this in its entirety, so that you’ll never have to worry about that part of JavaScript again!


#### Motivation
I'd love to give this talk because I've myself never really understood 'this' for a long time, and when I first saw myself writing 'let that = this' at Runtastic, I wondered about all the different use cases of 'this' and how to optimize its usage in my code, so I started researching and trying out things. However, this exploration turned out to be quite confusing, and I want to help the attendees understand and use 'this' better so that they don't have to do hours of research. 