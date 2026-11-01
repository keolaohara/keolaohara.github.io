---
layout: essay
type: essay
title: "Reflecting on Coding Standards"
# All dates must be YYYY-MM-DD format!
date: 2026-10-31
published: true
labels:
  - ESLint
  - Coding Standards
  - Software Engineering
---
## When Working Code Still Needs Work
Getting a program to run feels like crossing a finish line. After spending time figuring out the logic, fixing mistakes, and checking the output, seeing the correct answer is satisfying. I think I'm done, but then I look at VSCode and notice that ESLint still has complaints. An unused variable. An inconsistent space. Something that needs to be written differently even though the program already works.

The first thing that comes to mind is why are these details important. If the computer understands my code and produces the right result, did I not complete the task?
After using ESLint in ICS 314, I am starting to redefine my definition of being "finished". Getting the correct output is part of the process, but it does not tell the whole story about the quality of a program.

<img src="/img/man.jpeg"
     alt="man"
     width="600"
     style="display: block; margin: 20px auto; max-width: 100%;">

### The Extra Work After It Works
During my first encounter with ESLint, fixing its warnings felt like another assignment attached to the actual assignment. I would work through a programming problem, finally get the output I wanted, and then realize I had to spend more time cleaning up the code.

That process was frustrating, especially during a timed programming exercise. When I am focused on solving a problem, formatting is usually not the first thing on my mind. I care more about whether my functions do what they are supposed to do.

However, I can also see the problem with always leaving cleanup until the end. Once the program works, it becomes easy to convince myself that the remaining issues are too small to matter. An unused variable was a common problem for me. It might not change the output, but someone reading the program could reasonably wonder why it exists. Did I forget to use it? Is part of the solution unfinished? Is it left over from an earlier approach?

Removing it makes the code clearer, even if the result on the screen stays exactly the same.
That helped me understand why a warning can be really helpful rather than only identifying a mistake that crashes the program.

### Small Choices Add Up
I still think some coding standards involve personal preferences. There is not always one universally correct place to put a curly brace. Different projects can choose different conventions and still produce good software.
Making those choices consistent are what really seperates good code and bad code. Reading code requires attention. I have to understand what information is being stored, how functions interact, and why certain decisions were made. When the formatting changes constantly, it adds another thing to interpret.

For example, consider these two versions of a simple function:
function calculateTotal(price:number,quantity:number){
return price*quantity;
}
function calculateTotal(price: number, quantity: number) {
  return price * quantity;
}

Both of these functions calculate the same value. However, the second version makes the structure easier to recognize. The parameter types are separated clearly, and the indentation shows the function body.

For three lines of code, that difference might seem minor. Across several files, repeated inconsistencies become much more distracting.


### Learning Through Critism
I agree that coding standards can help someone learn a programming language, although they cannot replace understanding the language itself.

Learning TypeScript involves more than remembering syntax. I also need to become comfortable expressing familiar ideas in ways that fit the language and the project.

ESLint provides feedback while I am doing that. Depending on the rules enabled, it can identify unused values, discourage certain patterns, and encourage more consistent code. TypeScript’s type checker handles a different part of the process by checking whether my use of types makes sense.

At first, those messages can blend together into one large collection of editor complaints. Understanding where a message comes from helps me understand what I need to improve.
A type error might mean I misunderstood the data a function accepts. A lint warning might mean I left unnecessary code behind or ignored a project convention. Those are different problems, and recognizing the difference is part of learning.

The most useful part is the repetition. If I keep receiving the same warning, eventually I start remembering the rule while writing the code. Fixing it becomes less of a separate cleanup task because I begin avoiding the issue in the first place.

### Standards Give a Team a Starting Point
After using ESLint more frequently coding standards became easier to think about when I imagined someone else working with my code.

When I write something myself, I already know what I mean. That background can make confusing code seem more understandable than it really is. Another programmer does not have access to the thought process I had while writing it.

Consistent conventions give that person a starting point. They know what formatting to expect and can move between files without constantly adjusting to a different style.
This also changes how I think about code reviews. If a tool can catch routine formatting issues automatically, people can spend more time discussing whether the logic is correct, whether the design makes sense, and whether the program meets its requirements.

I would rather have a teammate spend their time helping me improve a difficult function than pointing out spaces that an automated tool could have fixed. Following standards is therefore partly a way of respecting other people’s time.

### What Does Finished Mean to You?
My impression of ESLint is that it is both painful and useful. The painful part is immediate: there is another warning to understand and another change to make. The benefit is sometimes less obvious because clearer code does not always produce a visibly different result.

However, the experience is changing what I look for when I review my work.

I still want the satisfaction of running a program and seeing the correct output. I also want to understand the code when I return to it later. If someone else opens the file, I want them to spend their time understanding my solution rather than decoding my formatting.

I probably will not get excited about every ESLint warning. But I am beginning to see those warnings as part of the work of programming.

The finish line is moving. “It runs” is still an important milestone, but I am learning to leave time for the question that comes afterward: “Is this ready for someone else to read?”

