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

"The man who asks a question is a fool for a minute, the man who does not ask is a fool for life"

This quote is ingrained in my mind, and it's never a bad thing to ask questions. However, have you ever thought hard about what type of questions you're asking? Being able to ask good questions is an important skill for software engineers. When programming, there are always problems that we cannot immediately solve on our own, so knowing how to ask other developers for help can save a lot of time. In [How To Ask Questions The Smart Way](https://www.catb.org/~esr/faqs/smart-questions.html), Eric Raymond and Rick Moen explain that a good question should be clear, specific, and informative. 

##What Is a Smart Question?

One example of asking a question the smart way is the Stack Overflow question Python: can unittest display expected and actual values?. The developer was using Python's unittest.TestCase that checked whether a person's age was equal to 42. When the test failed, it only displayed the custom message "age incorrect." The developer wanted the test to display both the expected value and the actual value, such as an expected age of 42 and an actual age of 39.

I thought this was a smart question because the developer provides the relevant code, explains what currently happens, describes what they want to happen, and asks a specific question about whether unittest can provide this information. Instead of simply saying that their code does not work, they give other developers enough information to understand the problem.

<img src="/img/smart-question.png"
     alt="Smart Stack Overflow Question"
     width="300"
     style="float: left; margin-right: 20px; margin-bottom: 10px;">

##Why Smart Questions Work

The responses to the question also show why asking questions this way is effective. Since the problem was clearly explained, people were able to immediately provide possible solutions instead of asking for more information. One answer suggested using assertEqual() instead of assertTrue(), which can automatically show the values being compared when the assertion fails. Another answer explained how the longMessage attribute could be used so the assertion displays both the comparison information and the developer's custom error message. These answers directly address the original problem and demonstrate how a specific question can lead to specific and useful responses.

##What Is Not a Smart Question?

An example of a not-so-smart question on Stack Overflow is What is wrong with my code and how do I fix it?. The user provided some Python code but did not clearly explain what the program was supposed to do or provide the full error message they were receiving. The question was eventually closed, and commenters asked the user to describe the problem, properly format their code, and provide the complete error message.

This question shows why providing enough information is important when asking for programming help. Someone trying to help would first have to determine what the code is supposed to do and what is actually going wrong. Instead of immediately working toward a solution, both the person asking and the people responding have to spend additional time figuring out the problem. Providing the expected result, actual result, error message, and what has already been attempted would make the question much easier to answer.

##Insights and Lessons Learned

After comparing these two examples, I learned that asking a smart question does not mean that you are expected to already know the solution. Instead, it means doing your own research first and providing enough information for another person to understand the problem. As I continue studying software engineering, I know I will encounter problems where I need help from classmates, instructors, online communities, or other developers. When that happens, I should explain what I am trying to accomplish, provide relevant code and error messages, describe what I have already tried, and ask a specific question. Doing this will not only make it easier for others to help me, but it can also help me understand my own problem better and sometimes even find the solution while preparing the question.

###Use of AI
I used AI to grammar check my work, spelling, and to improve the wording in some sentences.
