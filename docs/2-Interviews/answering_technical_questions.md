## Answering technical questions

### Foreword

This section contains a lot of information and can look very daunting. **You don't need to know everything in here to interview!**. The good news is that a lot of these will probably come to you naturally as you practice and get experience interviewing. It's totally expected that the first few interviews are going to involve some learning! There's no substitute to practice. The goal of this section is **not to memorize it**, but to use it as a **guide to help you reflect** on your experience and help you improve in the long run.

### Which language should I use?

The best answer to this question is "whatever you're the most comfortable with". In 99% of algorithm interviews, they want to see if you understand programming concepts and can write code. You can show that to them in just about any language. Using the language you are most familiar with will minimize friction, such as unfamiliarity with the language and its libraries.

That being said, some languages allow you to express concepts much more quickly and ergonomically than others, and eventually you'll want to get comfortable with one of those languages. We recommend Python in particular *for interviews* (though it's also a useful language to know in general).

Things that can get in the way in other languages include:
- Writing types (we love types, but you only have one hour to write your code and explain it!)
- Manual memory management
- Verbose syntax
- Boilerplate code
  - Class definitions, keywords like public or static
  - Writing conversions between conceptually similar data structures (e.g. a library function returns `String[]`, you want `List<String>`)
  - Simple tasks like creating a set out of the elements of an array
- Writing uninteresting subroutines (e.g. manually iterating over an array to find the max element or to do a linear search)

Search for [Python tricks](http://sahandsaba.com/thirty-python-language-features-and-tricks-you-may-not-know.html) to find [useful shortcuts](https://stackoverflow.com/questions/101268/hidden-features-of-python).

There are other languages that are quite ergonomic, like Ruby and some functional languages. But Python is the most widely understood and useful outside of interviews.

> Rudi says: sometimes the interviewer might specify which language you have to use. You don't really have a choice but to comply to their demands. However, for algorithm questions, it's not a great sign unless they have a good and specific justification. While all programmers begin programming by learning a programming language, transferring concepts between programming languages is not very difficult once you've used 2 or 3.

> Rudi says: some questions are better suited for some languages than others. For example, you can better communicate that you understand low-level concepts if you use C++ than Python. However, often times, you can still get the concepts across in a high-level language, and just mention why it would be more efficient in a low-level language. I've once implemented a garbage collector in Python during an interview and did pointer arithmetics on Python integers while pretending they were pointers. It was basically pseudo-code that actually ran and worked. But it's something I'd never do in real life, there would be no situation where it would make sense!

### General communication tips

- Speak loudly, clearly, and confidently
  - Being confident does not mean being confident that you are always right or that your code is guaranteed to work. A confident person is also comfortable communicating that there are things that they don't know, and places where they could be mistaken.
  - It's hard to 'teach' being confident, but seeing examples might help gain awareness (see the resources section)
- Make eye contact if you're doing an in-person interview
- Practice shaking hands with friends if needed, to get a sense of what a good, firm handshake looks like
- Explain what you're thinking and doing throughout the interview
- Using clear variable names and even writing comments while coding is part of communication. It helps the interviewer follow what you're doing, and it demonstrates a care for quality code that employers value

> Rudi says: Communication is a difficult life skill to master. We're not saying that you have to worry about how much you talk at any point in the interview. That would be super stressful and trip you up! Rather, we only mean that this is something to keep in mind and improve in the long term. Also, it's more important to become good at solving the problem at first than focus on perfecting your delivery. I know it's really hard to think about clear communication when your brain is 100% focused on solving the question! I can't do it. The more comfortable you become with solving the question, the more bandwidth you'll free up to think about other things.

### Algorithms: starting the interview

- State what language you intend to use. Many C-style (curly brace) languages look similar but have subtle difference
- Get started right away (on something)
  - Don't think to yourself, or go back and forth on things for too long. It's perfectly fine to take a few minutes to time to think in the beginning, but interviewers want to see things moving at some point
  - You don't have to get *coding* right away. In fact, you probably shouldn't
  - Some things you can start with is to ask questions, draw some examples, describe possible approaches, write pseudocode
- Ask questions!!!
  - Clarify the problem to make sure you know what you're being asked (explain it back)
  - Clarify requirements and assumptions (ask about edge cases, or clarifying details). E.g. shuffle a deck of cards - do I know how many cards? what does shuffling mean in this case?
  - Go over 1-2 small test cases to make sure you know how the algorithm will work
  - Note: figuring out what to ask is something you learn over time. Typical questions include: "what is the input size?", "is the input sorted?", "can I assume the input is always valid/well-formatted?", "how much memory do I have?".
- Explain to the interviewer how you intend to approach and solve the problem at a conceptual level before you start writing code
  - It helps you clarify your own thoughts
  - It helps the interviewer follow along when you start coding
  - It allows the interviewer to correct you if you misunderstood the question
  - It allows the interviewer to jump in if the solution is totally off-track. Better to know early on before you write too much code going down the wrong path!
  - Write stuff down as you think so they can see that you can organize your thoughts
- It's okay to start with an inefficient approach, even brute force! Just get started, you can optimize things later - better to get a simple solution than no solution. Just don't forget to tell the interviewer that you're going for the brute force route. You don't want the interviewer to think that you think O(c^n) solution is efficient. So just tell the interviewer that you are aware that this is not the most efficient solution, but that writing even an inefficient approach will give you insight into the problem

### Algorithms: solving the problem

- Explain your thought process. Keep talking throughout the interview. Humans (interviewers included) tend to be uncomfortable with long silences for whatever reason.
  - It's perfectly fine to take time to think. Just state it. The point is to avoid suddenly going silent. Useful phrases include "I'm going to take a minute to think about possible solutions" or "I'm worried that my solution does not handle this edge case. Let me think about this for a minute". Think of it as if you were narrating your own thought process: "I am wondering whether I should use approach A or approach B"
  - Always explain what you are coding next. It doesn't have to be a long-winded explanation, often a sentence is enough. For example, "next, I'm going to find the object in this array with the largest index" before writing the 3-5 lines of code that achieves it
  - There's a natural fear of being judged for saying something wrong, but it's often fine to keep talking even if you're not sure that you're right. Interviewers often want to know how you struggle just as much as (if not more than) they want to see you just "get it"
  - One way to practice this is to do problems on a sheet of paper and [talk to a rubber duck](https://en.wikipedia.org/wiki/Rubber_duck_debugging)
- Keep a good pace (keep in mind how long you have and how much you're aiming to get done ... but not too much cause it can be sort of terrifying)
- It's definitely not about getting the right answer right away - any good coder will eventually write code to do it - it's about the process that got you there and getting there within time constraints
- Make sure you handle common edge cases, like an empty input! People always forget that

A common question students ask is **"am I allowed to use library functions?"** (e.g. find element in array). The answer is **probably yes**. However:
- If the library solves the question in one line, the interviewer probably wants you to implement it to see if you understand how it works. Feel free to mention that an implementation already exist, but just don't start complaining about how you wouldn't do it in real-life (it's not the point)
- Do explain very clearly the input and outputs of the function you are using, and when possible how it's implemented or what kind of tricky behavior it might have
- Just to make sure, it's worth asking permission, or at least make sure the interviewer knows what the function is
- It's fine to make up a function if you can't remember what the existing one is called. Nobody cares if you use `File.open(...)` when it's supposed to be `Sys.open_file(...)`

On that subject, a very useful bit of preparation that can only take an hour or two is to familiarize yourself with the libraries that come with your language. It's worth reading over the operations you can do on strings, arrays/lists and maps/dictionaries. Useful functions include `zip`, `split`, `substr`/`slice`, `join`, `find`, etc.

### Algorithms: finishing the interview

- Once you have an initial implementation mostly right, ask if any further optimizations are necessary
  - Are you optimizing for time? Space? Which is more important?
- Offer to make further improvements the code. This tends to impress interviewers
  - How can the style of your code be improved?
  - Is there any redudancy that could be eliminated?
  - Could you refactor your solution to be more generalized? e.g. accept an arbitrary iterable data structure as an input when the question just asked you to handle arrays
  - Can you write the solution more concisely? e.g. you used a bunch of for loops when you could have used map/filter/reduce
- Write/talk through some test cases if you have time, to prove to yourself and the interviewer that your code works
  - Volunteering to do this also impresses interviewers, because it shows that you take responsibility for making sure your code is correct

### Algorithms: advanced tips

- Implement functions in breadth-first order, not depth-first order
  - For example, supposed you have your main function f1 that calls f2 and f3. Function f2 calls f4. An effective implementation order is f1, f2, f3, f4. Don't implement part of f1, jump to f2, then f3, and end up coming back to f1 later. You'll lose track of what you were doing. Instead, just call the functions, explaining to the interviewer what the function does and promise that you'll implement it after you're done with your current function
- If the solution to a problem is already familiar to you or you can find the solution instantly, be careful not to code it directly without any explanations
  - There's a danger that the interviewer will think you just memorized the solution, which doesn't provide them much information about your problem solving-abilities
  - To mitigate this, explain the constraints of the problems, the conditions that need to be satisfied for the solution to work, and the reasoning behind each part of the solution. For example, if your solution involves using a set, explain that you need constant-time access, that you don't need to store duplicate elements, that you have no values (keys only) and that order doesn't matter (unless the set implementation in your language guarantees an order)
- Learn to use the accurate and precise terminology
  - For example, I've heard people say "null tree" when they meant "empty tree". In some cases, an empty tree is represented with a null pointer, but the term "null" is very language and implementation-specific
  - Another example is saying that you want to use an ArrayList when discussing what data structure to use. Probably you would want to say either an array or dynamic array, which conveys more information that you understand how ArrayList is implemented and what the performance implications are
  - The problem with language-specific terminology is that it may convey that your current understanding of programming is mostly tied to a particular language

### Questions about your experience/projects

- be excited about what you did!
- talk about technical aspects and explain the things *you* did and what you learned

### Whiteboard tips

- I hate this, but sometimes you have to write code on the whiteboard. If this comes up, I recommend you...
- start as high up as you can, to give yourself room
- leave some space between function calls and the "first line" because there's a good chance you're going to want to go back to initialize some variables there
- in general, leave some space between lines just in case
- use helper functions as much as possible so you can write different parts of the algorithm in different parts of the board and keep track of what parts do what
- PRACTICE THIS if you know you're going to have to do it - it's really weird and different from writing code on your laptop

From [Steve Yegge's blog](http://steve-yegge.blogspot.com/2008/03/get-that-job-at-google.html):
> One last non-technical tip: bring your own whiteboard dry-erase markers. They sell pencil-thin ones at office supply stores, whereas most companies (including Google) tend to stock the fat kind. The thin ones turn your whiteboard from a 480i standard-definition tube into a 58-inch 1080p HD plasma screen. You need all the help you can get, and free whiteboard space is a real blessing.

### Other resources

[A video walkthrough of a coding question using some of the tips above](https://www.youtube.com/watch?v=7mR9PJDjRjo&t)
[YouTube channel on charisma and confidence](https://www.youtube.com/user/charismaoncommand/videos)
[The Charisma Myth](https://www.amazon.com/Charisma-Myth-Science-Personal-Magnetism/dp/1591845947)

[How to identify edge cases on algorithms](http://softwareengineering.stackexchange.com/questions/72761/how-do-you-identify-edge-cases-on-algorithms)!
