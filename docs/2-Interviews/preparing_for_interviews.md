## Preparing for interviews

There are lots of resources out there to learn more about how to prepare for technical interviews, so I'm just gonna mostly link to resources here (see below). A lot of this stuff feels like a game - you just have to know the rules, the patterns, develop certain skills from repetition. Once you understand the game, you can play it well. You just have to *know how*.

Be prepared to:

- talk about past experience (projects, work)
  - what you did
  - what you liked
  - what you didn't like
  - a technical problem you encountered and how you fixed it
- talk about and work towards writing an algorithm to solve a problem, during the interview
- you can also expect a “tell me about yourself” question (so be prepared!) and some time where they tell you about their company

### What material should I know?

This is a difficult question to answer. The more you know, the fewer the number of weak points that could trip you up. Knowing more things is a good thing in general, you shouldn't learn things just for interviews.

That being said, you have limited time to learn things so you probably want the biggest bang for the buck.

Things that interviewers will expect you to know:
- Understanding O() analysis
- Arrays vs linked-list
- Stacks and queues
- Dictionaries (one of the most used data structures in interviews)
- Being able to traverse a binary search tree recursively.

Things that are quite useful:
- Be able to give a 5 minute answer the question "how does the internet work?" or "what happens when I type google.com in the URL bar and press enter?"
- Breadth-first search and depth-first search on graphs
- Being able to add and remove a node from a non-balanced binary search tree.
- Using a heap, having an idea of how they are implemented.
- Being able to implement quicksort and mergesort
- Dynamic programming (most advanced concept you'll probably need to know, some companies like Google love dynamic programming questions)
- Tries, how to use them (also relatively more advanced but they do show up not infrequently)

Things that are not that important unless you have time:
- Any graph algorithm more advanced than Djikstra search
- Being able to implement a balanced binary search tree from scratch

(The lists above are work in progress and NOT comprehensive. Submit a GitHub issue if you want to ask about a particular concept)

### Know what your weaknesses are

And work on them!

- Have you only done assignments and/or academic work? Make sure to practice writing programs from scratch that compiles and runs. Make sure to familiarize yourself with the tools and libraries of your prefered language.
- Have you mostly done web development written business logic? Make sure to practice breaking down large problem into smaller pieces and practice algorithms. Write code that isn't just about putting together APIs.
- Do you make a lot of mistakes while coding and need several debugging passes to get a program right?
  - If those tend to be type errors (e.g. `TypeError: unsupported operand type(s) for -: 'tuple' and 'tuple'`) and you haven't used a typed language yet, learn one
  - If you do know a typed language, try a functional language like Scala, F#, OCaml or Haskell that require you to do more thinking upfront. Those languages are difficult to get to compile but when they compile, they tend to just work.
- Have you only used a typed language? Try a dynamic one.
- Have you only used a high-level language? Write some C/C++ to practice understanding pointers.
- Have you only worked on large codebases? Try implementing something from scratch.

### Practice makes perfect!

But **please please please** don't overdo it. It's so easy to feel like you can just keep preparing and studying and getting better - you can sink hours and hours and days and weeks into this, and it's not worth it. Being happy, spending time with friends, doing your assignments, etc are all very important. Definitely practice, it will help you feel more comfortable. But don't let it take over your life.

If you can find friends or friendly people who are willing to interview you to help you practice, that is very valuable. Practice talking out loud and going through a problem from beginning to end.

### Resources:

Tutorials/books

- Cracking the Coding Interview ([pdf to old version](https://inspirit.net.in/books/placements/Cracking%20the%20Coding%20Interview.pdf) or you can buy it). This is the classic book. In addition to practice problems, the newer versions also cover most of the material that can show up in an interview.
- Elements of Programming Interviews (less up-to date than CtCI but they have a few design problems if you need more advanced practice)
- Programming Interviews Exposed
- [Online course-version of Cracking the Coding Interview](https://www.hackerrank.com/domains/tutorials/cracking-the-coding-interview)

Practice coding questions

- [HackerRank](https://www.hackerrank.com/dashboard) for online practice questions.
- [LeetCode](https://leetcode.com/) for online practice questions.
- [Pramp](https://www.pramp.com/) for the full interview experience. They match you with a peer and you take turns interviewing each other.
