# How a Deep Dive into TypeScript Impacted My Job Search

### Spoiler: TypeScript isn't the only thing TypeScript taught me.

If you're a boot camper like me, you may know that most coding boot camps teach more functional programming than anything. You may also know that languages that strongly favor a functional pattern are the roots of the skills taught at boot camps. This includes languages like JavaScript (JS) and Python. What is the problem with this?

## JavaScript and Python are implicitly typed languages

At least Python's type-safe rating is strong. JS's type-safe rating is "weak". Let's talk about JS. JavaScript has been the most-loved and the most-hated programming language all at once for quite some time now. A lot of the hate for JavaScript is due to its absence of a strict typing system. Where a language such as Java will crucify you for a null check, JavaScript says, "String divided by string? Yeah, that might work. Let's run it."

For noobs, that's great! For experienced developers with a background in type systems and object-oriented programming (OOP), not so much. They'll likely spend some time scratching their head when working in JS. Actually, an argument can definitely be made that typing systems should be introduced to juniors as early as possible. I definitely agree after learning TypeScript (TS).

In an implicitly typed language, the type of a variable is implied by its definition and other mutations, yet the variable is never restricted to its original implied type. JavaScript fixed a little bit of this with the `const` keyword in ES6. Not too much and not nearly as much as say, Java, however. In JavaScript, any properties on an object can still be changed to whatever type you like if you are not using TS to strictly type. This gets very dangerous in large code bases. At the very best, it can require a ton of comments and developer focus to make sure something is never changed or coerced to a type that will not work with the operations working on that variable. The worst case scenario, of course, is production coming down.

## The decision to learn TS

After my boot camp concluded, I had trouble deciding what to learn next. I thought about GraphQL, Shopify, a deep dive into Node, and many others. I eventually settled on TypeScript because it can be used anywhere JavaScript is used. I hope that you will consider learning TS after reading this post.

## What did I learn?

Everything. Er... well, everything about strict typing. I thought possibly TypeScript might be missing some things in comparison to the strict typing systems in Java or C#. I did not find that to be the case. Here is what surprised me... I found that the more I learned about TypeScript, the more I learned about typing systems in general. Eventually, I became completely committed to typing every reference and variable I possibly could in my projects. This saved me a lot of debugging in the long run. Not to mention, there is something charming about being able to document the shape of your models and use said shapes to prevent errors in one fell swoop. Experienced OOP developers are reading this like, "Um... yeah. That's kind of the point. It's called an interface." Right you are! Interfaces and classes are the heart and soul of what will make TypeScript special for you as a junior JavaScript developer.

## What did it do for my job search?

It made me a better interviewee and more attractive candidate. Not only did I have another popular technology under my belt, but I was able to approach interview coding challenges in strictly-typed languages with a lot more confidence. While in the job search, I had to complete a take home challenge in Java. Now, I've had a little bit of experience in Java, but never anything like my experience in JavaScript. Meaning, I didn't write an API or desktop application or anything like that in Java. So, I was reasonably concerned with my ability to do well on a Java coding challenge.

Once I began the challenge and started researching how to implement my solution, I was pleasantly surprised by just how much of TypeScript is transferrable to Java! It makes perfect sense when I think about it now, however. TypeScript is developed by Microsoft and is meant to function a lot like the typing system of C#, their alternative to Java.

## TypeScript is the best next thing to learn for a junior

I did really well with that challenge. I attribute a lot of my success in that situation to the fact that I decided to start using TS in all of my JS endeavors about two months before. If you're a boot camp graduate or a junior JavaScript developer looking to learn something that will vastly broaden your coding horizons, learn TypeScript.

As a bonus, you will finally understand all of the JavaScript hate when you see just how much chaos JavaScript was allowing you to get away with before TypeScript.

<small>If anything in this article is inaccurate or misleading, please do not hesitate to reach out so I can change it! I am still a junior myself and I want to learn as much as possible.</small>
