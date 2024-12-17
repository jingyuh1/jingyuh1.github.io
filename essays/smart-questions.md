---
layout: essay
type: essay
title: "Smart Questions"
# All dates must be YYYY-MM-DD format!
date: 2024-09-10
published: false
labels:
  - Questions
  - Answers
  - StackOverflow
---
![Smart-Questions-for-Managers-to-Lead-Better](https://github.com/jingyuh1/jingyuh1.github.io/assets/156954674/cbd6acf8-b66a-4ab6-a4d1-36058faad042)


## What’s a smart question?

Good questions can not only lead to constructive solutions, but also stimulate people's curiosity, creativity and motivation to learn. Official documentation is a must-read for developers during the learning process. Documentation often explains step-by-step procedures and frequently asked questions. For example, when you want to learn Git, the correct way is to first study the official documentation to understand the basic concepts, instead of going to the community or forum to ask "Why did I submit the code using git commit, but I can't be seen in the Git code repository?" Modifications?" Topics refer to disputes that cause dialogue or discussion, including descriptive topics and prescriptive topics. Developers ask detailed questions and think about why the answer is what it is.

In the following example, we examine the components of a decent question. In this case, the asker is trying to figure out a way to get Why do certain random strings produce colors when entered as background colors in HTML.
```
Q: Why do certain random strings produce colors when entered as background colors in HTML?

For example, bgcolor="chucknorris" produces a red background:
<body bgcolor="chucknorris"> test </body>

Conversely, bgcolor="chucknorr" produces a yellow background:

This holds true across various browsers and platforms. What’s going on here?

```

The title of this question is very concise and makes it clear to the respondent how the answer should be given. The question "Why do different words have different background colors" contains the questioner's confusion and the basic structure of HTML.
```
A: The reason is the browser can not understand it and try to somehow translate it to what it can understand and in this case into a hexadecimal value!...
chucknorris starts with c which is recognised character in hexadecimal, also it's converting all unrecognised characters into 0!
So chucknorris in hexadecimal format becomes: c00c00000000, all other characters become 0 and c remains where they are...

Now they get divided by 3 for RGB(red, green, blue)... R: c00c, G: 0000, B:0000...

But we know valid hexadecimal for RGB is just 2 characters, means R: c0, G: 00, B:00

So the real result is:

bgcolor="#c00000";

```
 
The respondent answered the question of the asker very clearly. He wrote some code that explained the logic of the background color., I can confidently say that it is a good question.

## The foolproof way to get ignored.

While there are decent questions that benefit everyone, there are those one can ask to create an entirely different effect. In the following example, a user asks how he would, in short, No clear questions raised
.

```
Q: Date Object in react giving not a number

In react the date object gives me an error when i use it with local Storage, but without it it works fine. what I wan to know is. like for example when I get the date and convert it to a string, i get some invalid value error, which pretty much means that the date wasn't generated as a number. Why does this happen ?

I tried to create a date object
```

His questions are vague, and questions without data are often confusing. Some people were confused by the questions he asked, and they didn't know how to answer them accurately. He or she can ask more specific and detailed questions
## Conclusion

A good question should describe the problem in detail, such as the development environment used, the error message generated during the running of the program (you can paste a screenshot), locate the location where you think the error may occur (paste the source code that generated the error), and put Write down your guesses and thought process. Endless questions are an almost endless black hole of time. The people most likely to give us useful answers are also usually the busiest people (busy because they do most of the work themselves). Such people are quite disgusted with the uncontrolled black hole of time, so they also tend to hate those rambling questions. We're most likely to get useful answers if we explicitly state what we need the responder to do (such as provide pointers, send a piece of code, check your patch, etc.). Because this will set an upper limit on time and energy so that the respondent can concentrate on helping us. It's great to do this.
