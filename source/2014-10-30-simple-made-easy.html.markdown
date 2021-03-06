---
title: Simple Made Easy
date: 2014-10-30 20:16 UTC
tags: Review, Video, Talk, Functional Programming
summary: "A talk by Rick Hickey, the author of the JVM-based functional programming language Clojure, about the value of writing simpler, non-complected code. The talk was given to a functional programming audience, so some of the material (and the jokes) may go over OO programmer's heads at times. Along the way he critiques object oriented approaches, test driven development, programmer centric coding, and breathes new life into common and archaic words by carefully defining their meanings."
---

## Gist

A talk by Rick Hickey, the author of the JVM-based functional programming language Clojure, about the value of writing simpler, non-complected code. The talk was given to a functional programming audience, so some of the material (and the jokes) may go over OO programmer's heads at times. Along the way he critiques object oriented approaches, test driven development, programmer centric coding, and breathes new life into common and archaic words by carefully defining their meanings.

## Good

1. He offers a good reminder that most of us ship artifacts not constructs. How something was made (the constructs) matters very little to your end users (unless your end users are other programmers), all they care about is what they can see (the artifacts of the constructs). It's important to not lose sight of that as the process unfolds.

2. *What's true about every bug that made it into production code?* It passed all the tests and made it through the type checker. Just because you have these things in your toolkit or language doesn't mean you're using them well or that they can ever be fool proof.

3. His explanation of using a modular/functional approach even when your language does not necessarily make that easy. The what, who, how, when & where, and why slides really helped me as someone from an OOP background start to grok what he was saying. That said, I wish he would have spent a bit more time here, perhaps with some more concrete examples (but maybe that's a whole other talk...).


## Bad

1. The whole Test Driven Development as guard rails analogy. Yeah, it made for a good laugh, but it also shows Hickey has totally missed the point behind TDD. Later on in the talk he makes an argument against agile sprints, saying that before diving into code, one should first think through the problem and make design decisions. You know what that sounds an awful lot like? Writing tests before code. He seems to think that TDD is the idea that mindless tests in and of themselves will solve all our problems. When in reality tests are just about formalizing and writing down the very thought process he advocates for in this talk! You write tests so you don't forget all that reasoning and designing you did three or four months down the road.

2. The idea that following standards or conventions or having nice systems to work with is a bad thing because they make programmers replaceable. I know that was just one of a few arguments he was making there, but it really bothers me that he even brought it up. If all we care about is job security than why don't we just write wrappers in domain specific languages around Assembly, they'll never be able to fire us then! I just find it ironic how the whole talk he goes on and on about being able to swap pieces in and out of a system and then somehow thinks this is suddenly a bad thing when it comes to programmers.

3. At around 29 minutes he talks about how programmers are all looking for benefits and never weigh the cost of using a given library or tool and he uses Hacker News as an example of this. However, I think he's got it completely backwards people on places like Hacker News and /r/programming are some of the most critical places I've ever been on the internet. Yeah, there's the occasional bloke with a positive comment, but most of the people on there are like, "Why would I do that when I can just write that for myself in x86 assembly?" Programmers are way more critical than he thinks, it's the pressure from management that forces us to churn out code quickly that leads to the behaviour he describes.


## Questions

1. If I wanted to start writing code from a functional perspective, where would be the best place to start? From one of my own languages like Ruby or JavaScript, or a functional-specific approach? What books or sites are a good place to get started with that?

2. I want more details about how state differs from values, preferably some examples. What does it mean to compose values with time? I don't know a whole lot about the functional paradigm, but that sounds a whole lot like what state is to me...

3. What the hell are monads and why are they funny?


## Review

There is a lot I disagree with from this talk and I thought a lot of concepts from the TDD community that Hickey either does not understand or deliberately straw manned (occasionally to comedic effect). That said while the talk was salty at times, I think a great deal of it was insightful, and better still, these insightful bits no one else is saying. I think this talk is important for every developer to think about as a way of self-critique. You may not agree with or comprehend everything he says, but I think there are enough nuggets in there to be useful for just about anyone.

I begrudgingly give it 5 out of 5 arbitrary units.
