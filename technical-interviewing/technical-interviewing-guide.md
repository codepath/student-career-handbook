# Technical Interviewing Guide

This post is meant to help computer science undergraduates looking for a software engineering internship in the summer. Applying to internships can be daunting, and this post will hopefully address some of the commonly asked questions. This post covers two questions:

* _**What are most technical internship interviews like?**_
* _**How should I prepare for them?**_

👋🏽 **Note:** This post is adapted from the [post started here](http://louisrli.github.io/blog/2014/01/18/tips-for-computer-science-internship-interviews/). It has been modified and adapted from that post written by a student Louis Li.

### The three types of internship interviews <a id="The-three-types-of-internship-interviews"></a>

Internship interviews tend to fall into one of three categories:

1. **The programming interview:** algorithms, data structures, coding
2. **The “what you’ve done interview”:** you and your projects
3. **The domain-specific interview:** quizzed about a tech stack you claim to know

We’ll explain these in more depth below, adding details on how to prepare for each category. Note that not every interview falls precisely into one of the three categories, and some interviews are a mix of multiple categories.

### Prep Before the Interview

A popular question you will get asked is a variation of "Why this company?" in which the interviewer wants to understand from you why you want to work with them in particular. This is an important question to be prepared for on the day of the interview.

Ahead of your interview, you want to take that extra time to learn about the companies. Think about why the company exists in the first place and ask these questions:

* What's their mission?
* What are their products? Which ones do you like and why?
* How would they define "having an impact"? \(based on their mission\)
* How do you define "having an impact"? \(based on your goals and experiences\)
* Why would you like to work there?

If you have a clear understanding of what the company does, and why you would like to work there, then you are already ahead of the game! 

### Beginning the interview <a id="Beginning-the-interview"></a>

Some bigger companies dive straight into the technical part of interviews, but your interviewer will **almost always** ask you a very important question \(or some variant\) that you should prepare:

> Tell me about yourself.

Keep it succinct! This should be a minute or two at most. Hit the important points about your interests and experience. Additionally, be prepared for questions that **highlight your interest in the company**. For example, why you want to work here, what you like about the product, a feature or improvement you might like to work on during a hackathon.

{% hint style="info" %}
Have a well-prepared intro that highlights one project or a team that you worked on previously. We highly recommend rehearsing your spiel ahead of time. It will give you a few moments to slow your breathing and heart rate down and settle into the interview environment. Plus, having a good answer to this question can set the right tone.
{% endhint %}

### 1: The programming interview <a id="1-The-programming-interview"></a>

The **programming interview** is the most common type of interview, especially if you’re not interviewing for a specific team. This is how most people envision computer science interviews: you’re asked one or more programming questions, and you implement solutions on a collaborative editor like [CodeShare](https://codeshare.io/) or [Collabedit](http://collabedit.com/).

These interviews can be further divided into two topics:

1. Questions involving loops, lists, or strings \(easier\)
2. Questions involving specific data structures \(harder\)

The first category is easier, and it includes questions like: _Remove duplicates from a list_ or _Generate all of the permutations of a string_.

The second category trickier, and sometimes the question will be hard or near impossible if you don’t know about a specific data structure or algorithm. For example, if you’ve never done breadth-first tree traversal, and you’re asked: _Print the values in this tree level-by-level_, the question will be much harder.

In some interviews, at the end of certain questions, you will be asked to discuss the [Big-O complexity](https://www.interviewcake.com/big-o-notation-time-and-space-complexity) of your implementation.

#### Steps in a Coding Interview <a id="Steps-in-a-Coding-Interview"></a>

When given a coding problem in an interview, whether on a whiteboard or on a hackpad, you’ll generally want to resist the temptation to jump straight into code, and instead solve the problem collaboratively with the interviewer roughly following these steps:

* **Step 1: Ask Clarifying Questions** - Ask the interviewer questions to better understand the problem.
* **Step 2: High-level Discussion** - Explain the ideas you have in concept first without using code to avoid wasting time writing code on a solution that won’t work.
* **Step 3: Choose an Approach and Confirm Inputs and Outputs** - Pick a potential approach from above and then start documenting the method definition and several example inputs and outputs.
* **Step 4: Start Writing Code and Thinking Aloud** - Start writing the body of your solution in code iteratively and talking aloud to the interviewer as you do.
* **Step 5: Test Your Solution** - Walk through your code line by line using several examples of inputs, and verifying for each case that the outputs are what you expect.
* **Step 6: Discuss Complexity** - If there is time at the end, check to see if your interviewer wants you to discuss [space and/or time complexity](https://www.interviewcake.com/article/java/big-o-notation-time-and-space-complexity) of your solution.

Check out [this more extended step-by-step overview](anatomy-of-an-interview.md) or this [video by an ex-Googler for a walkthrough](https://youtu.be/uQdy914JRKQ) for more details. You can also read [this guide by an ex-Facebooker](https://hackmd.io/@nesquena/ex-fb-interviewer-tips).

#### Topic Overview <a id="Topic-Overview"></a>

The technical interviews tend to involve coding questions of the following data structure and algorithm topics:

* Complexity Analysis: [Big-O Notation](https://www.interviewcake.com/big-o-notation-time-and-space-complexity)
* Core data structures: [Hash Tables](https://www.interviewcake.com/concept/hash-map), [Arrays](https://www.interviewcake.com/concept/array), [Linked Lists](https://www.interviewcake.com/concept/linked-list), [Stacks](https://www.interviewcake.com/concept/stack)/[Queues](https://www.interviewcake.com/concept/queue)
* Searches: [Binary Search](https://www.interviewcake.com/concept/binary-search), [Breadth-First Search](https://www.interviewcake.com/concept/bfs)/[Depth-First Search](https://www.interviewcake.com/concept/dfs)
* Graph data structures: [Binary Trees](https://www.interviewcake.com/concept/binary-tree), [Graphs](https://www.interviewcake.com/concept/graph)

In particular, depth-and breadth-first search \(DFS and BFS, respectively\) can be extremely popular questions so be sure to practice them. You might also encounter harder topics such as these but you will tend to see them less frequently for internship interviews:

* Sorting: Merge Sort and Quick Sort
* Recursion and Combinatorial
* [Dynamic Programming](https://www.interviewcake.com/concept/overlapping-subproblems)
* [Greedy Algorithms](https://www.interviewcake.com/concept/greedy)
* Object-Oriented Design \(OOP\)

If you are looking for introductions to these concepts that are fun and accessible, check out [BaseCS](https://hackmd.io/s/HJ9YQDE2b) and the [related podcast](https://www.codenewbie.org/basecs). You can also read through this [algorithms tutorial series](https://adrianmejia.com/blog/2018/04/04/how-you-can-change-the-world-learning-data-structures-algorithms-free-online-course-tutorial/). For more resources, check out our [data structures and algorithms links](https://hackmd.io/s/rkg8GyDiQ) guide.

#### Checklist <a id="Checklist"></a>

Before walking in for a technical interview, **you need to study and practice for interviews**. Unless you do algorithmic challenges on a regular basis, it’s necessary to read and practice problems.

* **Use Leetcode to Practice**: To practice coding problems, check out [Leetcode](https://leetcode.com/). Focus on these topics: string manipulation, linked lists, doubly linked lists, hash tables, trees, queues, stacks, depth-first search, breadth-first-search, basic graphs, basic complexity.
* **Check Glassdoor**: Many companies have interview questions on [Glassdoor](https://www.glassdoor.com/index.htm). Your goal isn’t to study the interview questions in advance, but you can get a good idea of the general difficulty of the programming questions.
* **Practice talking while you solve problems**: When you feel a bit more prepared, you can do a mock interview to see where you’re standing. Check out [Mock Interviews](http://www.mock-interviews.com/) or [Pramp](https://www.pramp.com/). You will receive feedback afterward with details about what went well and what you need to improve, which will definitely help you with upcoming interviews.

#### Coding Interview Tips <a id="Coding-Interview-Tips"></a>

* While working through a problem, it’s natural to need some time to think. Feel free to take a breath and a few moments to think before verbalizing your thoughts to reduce the confusion of the interviewer. At the same time, try to avoid staying quiet for long periods of time, it’s important to keep the interviewer “in your loop” and talk them through your approach. This can often allow them to help you along and provide guidance as well.
* Pick a language you feel most comfortable with when interviewing and use that whenever possible. Make sure you have a solid understanding of data structures and algorithms and their respective APIs in that language. Most interviewers will have no problem letting you look up \(or telling you\) an API call, but keep in mind that time is a precious resource! Knowing that stuff beforehand gives you more time and headspace to focus on the problem at hand.
* Be sure to ask any questions you have about edge cases, assumptions, etc directly to the interviewer. You can double-check to confirm details about the problem, if you have to deal with bad or invalid input, etc. Questions are good and they show the interviewer that you consider all aspects of the problem instead of just diving in head-first.

### 2: The “what you’ve done” interview <a id="2-The-&#x201C;what-you&#x2019;ve-done&#x201D;-interview"></a>

The **“what you’ve done” interview** is a non-technical, pleasant conversation with your interviewer, where you get the opportunity to talk about your resume and projects. This type of interview was more common in small and medium-sized companies.

These interviews are an opportunity to pitch yourself as a passionate developer. You can talk about research, past internships, and/or other interesting experiences related to software.

During these types of interviews, keep your answers open and honest and don’t try to mislead or make up stuff that you don’t know. You aren’t expected to have a holistic working knowledge of every part of a large project.

If you’re a freshman or sophomore, **don’t panic if you don’t have a lot to talk about yet**. Without side projects and/or past internships, however, this interview can be a bit tough. You can use course projects, but it’s better to talk about hackathons, CodePath projects, etc since many basic on-campus projects will sometimes be considered overly trivial.

**Checklist**

Be prepared to talk in-depth about any jobs and projects on your resume. For each project, you’ll want to be ready to answer these questions:

* What was the project?
* What was the scope of the project? \(i.e., how much time, how big was it\)
* What was your role in the project?
* What did you learn?
* What were some of the challenges in the project?

If you prepare these answers, you’ll be ready to answer a more general question that frequently shows up in interviews:

* Tell me about an interesting technical challenge that you have encountered.

### 3: The domain-specific interview <a id="3-The-domain-specific-interview"></a>

The domain-specific interview tests your knowledge about a specific language, framework or platform that you claim to know on your resume. This interview often shows up if you’ve been placed to interview with a specific team \(e.g., iOS Safari team at Apple, YUI team at Yahoo\).

The interviewers expect you to show knowledge through answers to quiz questions, discussion of relevant projects, and opinions on language or framework features.

#### Checklist <a id="Checklist2"></a>

If you are placed to interview with a team that uses a specific language \(or framework\), you should prepare for the following questions:

> What makes {language} different from other languages?

> If you had to change something in {language}, what would you change?

> Tell me about a technical challenge that you had when you were working on a project in {language}.

> Tell me about {feature} in {language} \(i.e Tell me about closures in JavaScript\)

### Ending the Interview <a id="Ending-the-Interview"></a>

Even when the interview runs over the allocated time, your interviewer will ask:

> Do you have any questions for me?

Treating this as an opportunity for a conversation can make things easier. This is a chance to connect on a personal level with the interviewer. If your performance was borderline, having an insightful conversation with the interviewer can’t hurt.

If the interviewer hadn’t described himself or herself yet, the first thing you can ask is:

> Can you tell me more about what you do?

Let the conversation flow from there. Make sure you have some questions prepared to ask the engineer. Think about questions that demonstrate a curiosity in working for the company. Some examples:

* Asking about the different teams in the engineering organization.
* Asking what the Engineer enjoys most about working at the company.
* Asking about the company’s vision, where do they see the company in a year from now.

If there’s not much to follow up on, you can ask about how they test their products or what they enjoy about working there. There’s [a very good list](http://programmers.stackexchange.com/questions/16436/do-you-have-any-questions-for-us-in-an-interview) on Programmers Stack Exchange, although not all of them are suitable for potential interns to ask.

### Miscellaneous: FAQ <a id="Miscellaneous-FAQ"></a>

These are answers to common questions:

> How long should my resume be?

For companies based in the US, your resume should not be longer than one page. Most recruiters don’t like reading resumes longer than one page.

Make sure your resume looks professional – spacing, font, structure. Use a serif font!

If your resume is too long, consider cutting out parts that are not tech-related – clubs, extracurriculars, experience in a different field.

Finally, don’t include things like your high school GPA, because they don’t matter to the people reading your resume.

> When should I start applying?

Most internship applications started popping up in October and November. Before last summer, after I had already decided to do research, I did receive a few emails for interviews as late as March. If you didn’t jump on it in October, don’t panic.

> How important are side projects?

It depends on the company, but if you’re a freshman \(first year\) or a sophomore \(second year\) without work experience, it’s very important. When you apply to your first internship, the recruiter will want to know if you have any side projects and see them listed on your resume/LinkedIn. In addition to spicing up your resume, it gives you something substantive to talk about in the “what you’ve done” interviews.

> How long can it take to hear back after an interview?

It varies by company. From small to medium-sized companies, you might hear back anywhere from a day to a week. After a final round interview, it can take a big company two weeks to a month to respond with either an offer or rejection.

> How can I overcome nervousness during interviews?

Practice a lot before your interview, and build up your confidence **solving problems while you talk**.

In some of the algorithmic interviews, if you start doing poorly, you might start to freeze or panic. If this happens to you, consider telling the interviewer, “Let me consolidate my thoughts for a moment.” Take a few deep breaths, don’t think about anything, and then tackle the question again.

If you feel nervous from the very beginning, try to persuade yourself that it’s only a friendly conversation.

> How can I know how well my interview went?

There’s no way to know for sure. However, if the interviewer starts talking about how much responsibility interns have _and_ you didn’t explicitly ask about it – the interview probably went well. You can also consider asking your interviewer how they felt the interview went at the end.

### Practical Coding Interview Tips <a id="Practical-Coding-Interview-Tips"></a>

#### Ex-Googler Interviewing Tips <a id="Ex-Googler-Interviewing-Tips"></a>

These tips are for focused around top companies like Google or Facebook, check these out to understand more about the purpose of interviews, and what to make sure you try and do during the interview:

* Your interviewers are trying to understand what it feels like to work with you on a daily basis. An interview question is a method in achieving that, it is not necessarily always there to specifically measure your skills on a topic but a tool to understand the depth of your thinking.
* Before the interview starts, ask them what they want to get out of this interview. Good interviewers should already have a plan and a set of expectations. Ask them what you should do. Don’t start coding yet. Ask them you should produce. Discussion, diagrams, pseudo code, code?
* Next, start to breakdown the question. List whatever questions you think it is important to solve this question, ask your edge cases. Get to a point where you are discussing about pros/cons of the solutions. These steps are critical. Don’t just start coding. Have a consensus first.
* Your interviewer will try to give you hints. Don’t ignore them because you are too confident about your solution. This is not a intelligence contest. Also, don’t panic if a hint doesn’t make sense. Ask what interview’s perspective is that they gave that hint.
* Talk, talk, talk as you are doing your thing. Talk about even the most obvious steps. Ask about testing, talk about testing cases if testing discussion is expected. Discuss what you’d fix to iterate your solution if you realized you are missing something.
* Don’t get freaked out if the interviewer jumps to a different question. Sometimes, they think they got enough of what they have been looking for from a question and will do something else. Don’t try to overdo a solution if interviewer think it is good enough.
* Don’t freak out just because your interviewer is taking too many notes. They need to provide evidence to the hiring committee and they want to remember as many signals as possible. Make sure you are clearly communicating your new ideas if you are iterating on the initial ones.
* At any interview regardless it is at Google or not, don’t see your interviewer as someone who has the full authority but some who you are already working with. Try to have a feel how productive it will feel in real life. Remember, interviews shouldn’t be a monologue.

These tips were sourced from [this tweet stream](https://threader.app/thread/1058433116002381824) and originally authored by [@JBD](https://rakyll.org/) from Google.

### Ex-Facebook Interviewing Tips <a id="Ex-Facebook-Interviewing-Tips"></a>

Check out [this post by an ex-Facebook interview](https://hackmd.io/@nesquena/ex-fb-interviewer-tips) on his recommendations for how to interview effectively, to briefly summarize his points:

* Make sure as the person being interviewed to properly lead the interviewer through the solution following a general set of steps.
* **Most common mistakes in an interview:** 1\) Making incorrect assumptions, 2\) Not asking questions, 3\) Not using the whiteboard to visualize or pseudocode, 4\) Not talking out loud to share your thought process, 5\) Writing no tests or poor tests
* **Important steps to an interview:** 1\) Ask clarifying questions, 2\) Analyze various solutions and tradeoffs, 3\) Plan solution with pseudocode, 4\) Implement solution, 5\) Test
* **When you get stuck:** 1\) Try to match this problem to previous similar problems 2\) Align the weakness of a solution to the strength of a data structure, 3\) Look for the twist that makes this easier to solve, 4\) Don’t be afraid to ask for a hint

### Attribution <a id="Attribution"></a>

This post is adapted from the [post authored here](http://louisrli.github.io/blog/2014/01/18/tips-for-computer-science-internship-interviews/). It has been modified and adapted from that post written originally by Louis Li.

