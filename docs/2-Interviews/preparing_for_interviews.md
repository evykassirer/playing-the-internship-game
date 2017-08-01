## Preparing for interviews

There are lots of resources out there to learn more about how to prepare for technical interviews. As we can't cover everything, we've linked to some resources that could be helpful (see below).

A lot of this stuff feels like a game - you just have to know the rules, the patterns, develop certain skills from repetition. It'll take a few tries to get it right. That's part of the process: it's just like how you need to cook a dish a few times to get it right, even if you have a recipe. Once you understand the game, you can play it well. You just have to *know how*.

Be prepared to:
- talk about past experience (projects, work)
  - what you did
  - what you liked
  - what you didn't like
  - a technical problem you encountered and how you fixed it
- talk about and work towards writing an algorithm to solve a problem, during the interview
- you can also expect a “tell me about yourself” question (so be prepared!) and some time where they tell you about their company

### What material could show up in an interview?

This is a difficult question to answer. The more things you know, the less likely it is that an interview question could trip you up. That being said, you have limited time to learn things. There a few concepts that are very likely to show up. There's also a long list of algorithms that _could maybe_ show up once in a while, depending on the company, the interviewer, and whether Venus and Mercury are in the same quadrant of the solar system this week. You could be spending an arbitrarily long time preparing for all possible eventualities.

You can do that if you enjoy it, but it's healthy to set a timebox. That is, allocate yourself a certain amount of time in advance to prepare for interviews. Learn as much as you can during that time, but no more. And in that time, you probably want the biggest bang for the buck.

Very likely to show up in interviews:
- Understanding O() analysis - that is, how to measure the performance (space and time cost) of your program
- Arrays vs linked-list
- Stacks and queues
- Dictionaries (one of the most common data structures in interviews, and industry!)
- Being able to traverse a binary search tree recursively. e.g. search for an element in a BST

The above provide a solid foundation to start with. Some intro-level internships will not ask technical questions at all, or teach you concepts during the interview. For places that do ask technical questions, most will assume that you have a good understanding of these basics.

Likely to show up in interviews at more competitive/intermediate-level internships:
- [Representing graphs](https://www.khanacademy.org/computing/computer-science/algorithms/graph-representation/a/representing-graphs) (e.g. edge lists, adjacency matrices, adjacency lists)
- Breadth-first search and depth-first search on graphs
- Being able to add and remove a node from a non-balanced binary search tree
- Knowing how to use heap and having an idea of how they are implemented
- Being able to implement quicksort and mergesort
- Dynamic programming (the most advanced concept you'll probably need to know, some companies like Google love dynamic programming questions)
- Tries, how to use them (also relatively more advanced but they show up not infrequently)
- Be able to give a 5 minute answer the question "how does the internet work?" or "what happens when I type google.com in the URL bar and press enter?" (see resources below for some resources on how to answer this)

If you use a textbook such as Introduction to Algorithms by Cormen, the book will often cover algorithms and data structures that are very unlikely to appear in an interview.  Things that are not that important unless you have time:
- Any graph algorithm more advanced than Djikstra search
- Being able to implement a balanced binary search tree from scratch
- Fibonnaci heaps, van Emde Boas Trees, interval trees, linear programming, etc

These lists can never be comprehensive, but hopefully it should provide a good starting point. [Submit a GitHub issue](https://help.github.com/articles/creating-an-issue/) if you want to ask about the importance of knowing a particular concept for interviews.

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
- [Interview Cake](https://www.interviewcake.com/) where you get a few free, very well explained questions, and they email you a new one every week

What happens when you type google.com in the URL? There are many resources that answer this question on the Internet. For example, [this](https://www.linkedin.com/pulse/what-happens-when-you-type-url-browser-press-enter-wijesinghe), [this](https://www.quora.com/What-are-the-series-of-steps-that-happen-when-an-URL-is-requested-from-the-address-field-of-a-browser), or [this](https://www.youtube.com/watch?v=jKrBh94O4WA). Keep in mind that a lot of guides introduce some technical jargon like TCP, but you mostly need to know how to answer the question at a high level (it's a question that you can go in arbitrary detail in any subarea depending on your preferences).
