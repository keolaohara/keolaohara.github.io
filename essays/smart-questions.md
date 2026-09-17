---
layout: essay
type: essay
title: "Questioning your Questions"
# All dates must be YYYY-MM-DD format!
date: 2026-09-17
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---

## Is there such thing as a stupid question?

Being able to ask good questions is an important skill for software engineers. When programming, there are always problems that we cannot immediately solve on our own, so knowing how to ask other developers for help can save a lot of time. In [How To Ask Questions The Smart Way](https://www.catb.org/~esr/faqs/smart-questions.html), Eric Raymond and Rick Moen explain that a good question should be clear, specific, and informative. Before asking, a developer should also research the problem and attempt to solve it themselves. Asking questions this way respects the time of the people helping and makes it easier for them to understand the problem and provide a useful answer.

One example of asking a question the smart way is the Stack Overflow question [Python: can unittest display expected and actual values?](https://stackoverflow.com/questions/4634625/python-can-unittest-display-expected-and-actual-values). The developer was using Python's `unittest.TestCase` that checked whether a person's age was equal to 42. When the test failed, it only displayed the custom message "age incorrect." The developer wanted the test to display both the expected value and the actual value, such as an expected age of 42 and an actual age of 39. This is a smart question because the developer provides the relevant code, explains what currently happens, describes what they want to happen, and asks a specific question about whether `unittest` can provide this information. Instead of simply saying that their code does not work, they give other developers enough information to understand the problem.

The responses to the question also show why asking questions this way is effective. Since the problem was clearly explained, people were able to immediately provide possible solutions instead of asking for more information. One answer suggested using `assertEqual()` instead of `assertTrue()`, which can automatically show the values being compared when the assertion fails. Another answer explained how the `longMessage` attribute could be used so the assertion displays both the comparison information and the developer's custom error message. These answers directly address the original problem and demonstrate how a specific question can lead to specific and useful responses.

A not-so-smart question could instead be something like, **"Python code doesn't work. My program keeps giving me an error and I tried changing some things, but it still doesn't work. Can someone fix it?"** This question would violate many of the principles discussed by Raymond and Moen. It does not provide the code that is causing the problem, the error message, what the program is supposed to do, or what the developer has already attempted. The title is also too vague to tell other developers what the actual problem is. Someone trying to help would first have to ask questions such as "What error are you getting?", "Can you provide your code?", or "What are you expecting the program to do?" Instead of immediately working toward a solution, both the person asking and the people responding would have to spend additional time figuring out what the problem actually is.

After comparing these two examples, I learned that asking a smart question does not mean that you are expected to already know the solution. Instead, it means doing your own research first and providing enough information for another person to understand the problem. As I continue studying software engineering, I know I will encounter problems where I need help from classmates, instructors, online communities, or other developers. When that happens, I should explain what I am trying to accomplish, provide relevant code and error messages, describe what I have already tried, and ask a specific question. Doing this will not only make it easier for others to help me, but it can also help me understand my own problem better and sometimes even find the solution while preparing the question.
