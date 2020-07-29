# Anatomy of an Interview

## Ex-Googlers Guide to Interviewing

When given a coding problem in an interview, whether on a whiteboard or on a hackpad, you’ll generally want to resist the temptation to jump straight into code, and instead solve the problem collaboratively with the interviewer roughly following a specific set of steps in order.

### Walkthrough Video <a id="Video"></a>

Check out this [video by an ex-Googler for a walkthrough](https://youtu.be/uQdy914JRKQ):

{% embed url="https://www.youtube.com/watch?v=uQdy914JRKQ&feature=youtu.be" caption="Cracking a Google Interview" %}

### Steps Recap <a id="Steps"></a>

There are six key steps to follow within a coding interview:

* **Step 1: Ask Clarifying Questions** - Ask the interviewer questions to better understand the problem. Check about edge cases, possible inputs, assumptions you can or can’t make, and verifying your understanding of the correct outputs.
* **Step 2: High-level Discussion** - Explain the ideas you have in concept first without using much code to avoid wasting time writing code on a solution that won’t work. Instead, draw or diagram out a basic approach without code and explain the basic solution idea. If the problem is complex or you aren’t confident about the optimal approach, list out a few potential approaches you think might work \(e.g iterative vs recursive, use data structure X or Y, etc\). Discuss with the interviewer to get their feedback and look for any hints or guidance from them if they are more communicative \(“Should I start coding with this approach?”\).
* **Step 3: Choose an Approach and Confirm Inputs and Outputs** - Pick a potential approach from above and then explain that you are going to start coding with that one in mind if the interviewer confirms this seems like a good direction. From there, you might start documenting the method “header” to confirm you understand the inputs being provided to you as well as explaining the outputs. You should list out several examples of inputs and then the expected outputs. Confirm the header, and the examples align with the interviewer's expectations and look for any hints or guidance they provide.
* **Step 4: Start Writing Code and Thinking Aloud** - Start writing the body of your solution in code. The process is iterative, where you might write a bit of code, and then circle back to make sure that will work for all the example inputs. Then continue writing code. Think with specific examples in mind as you start on the code. Be sure to be talking while your work on the code, explaining aloud your thought process whenever possible for what you are doing.
* **Step 5: Test Your Solution** - Walk through your code line by line using several examples of inputs, and verifying outputs. In other words, make sure your solution works reliably, especially for edge cases, blank inputs, or odd inputs. Track the output as it’s being created and show the interviewer, you believe each example works or if you do find an issue with a case, be clear that you caught a failing case for your current code.
* **Step 6: Discuss Complexity** - If there is time at the end, check to see if your interviewer wants you to discuss space and/or time complexity of the code. You’ll explain the current time complexity of your solution, and then explain the space complexity of your solution. These are both using [Big-O notation and complexity analysis of code](https://www.interviewcake.com/article/java/big-o-notation-time-and-space-complexity), which are important concepts to understand before you interview.

## Whiteboard Interview Guidelines

**Source**: [https://twitter.com/bria\_sullivan/status/1171852539551199232](https://twitter.com/bria_sullivan/status/1171852539551199232)

Here's an even more concise step of steps for tackling a whiteboard interview compatible with the more detailed framework above.

#### Clarifying questions

* Interviewers are usually asking you something vague on purpose. They want you to identify this.
* For example: Is there a max character length on the input string? Are we expecting positive numbers only?

#### Test Cases

* Show your understanding by coming up with different inputs and outputs.
* This also helps me come up with a solution and helps me understand the problem better. \(It also helps me to actually write it out on the board\)

#### Propose a solution with pros and cons

* Propose a possible solution then discuss the pros and cons.
* Always mention storage and time complexity.
* Also if your solution isn’t the most optimal, say that. It’s much better to have a working inefficient solution by the end than an unfinished solution trying to make it O\(log n\).
* You’ll probably come up with a more optimal solution as you go anyway

#### Start Coding the Solution

* Actually write out the code. 
* Make sure to check for null. 
* Write the method signature, account for inputs, etc.
* If you get stuck, Pause.
* Build an example \(maybe those inputs and outputs you had from earlier\) and step through every single line.
* Write down what each variable stores along the way \(yay for dry erase I guess?\)
* This usually shows me what I need to do to get unblocked
* If you reach this point \(hopefully you do\) and you have something that works \(again, doesn’t have to be optimized\)

#### Try to break your code

* Build more test cases and walk through your code to try to break it! 
* Usually, this is where I’ve seen places to make the solution better
* Talk it out. Every time you write a conditional, say why. It’s usually conditional statements that make stuff work or not

