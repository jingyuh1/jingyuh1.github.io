---
layout: essay
type: essay
title: "Smart Questions"
# All dates must be YYYY-MM-DD format!
date: 2024-01-24
published: True
labels:
  - Questions
  - Answers
  - StackOverflow
---
![Smart-Questions-for-Managers-to-Lead-Better](https://github.com/jingyuh1/jingyuh1.github.io/assets/156954674/cbd6acf8-b66a-4ab6-a4d1-36058faad042)


## What’s a smart question?

Topics refer to disputes that cause dialogue or discussion, including descriptive topics and prescriptive topics. Developers ask detailed questions and think about why the answer is what it is.

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

While there are decent questions that benefit everyone, there are those one can ask to create an entirely different effect. In the following example, a user asks how he would, in short, create a desktop application with Facebook.

```
Q: Facebook Desktop Notifier

I am a beginner programmer that have never used anything other than what's included in a language.

I am trying to create a desktop application that notifies me anytime I get an update onfacebook. 
How should go about doing this? Thanks in advance.

edit Sorry I was not clear. Is there any way to make a DESKTOP application with facebook?
```

A simple “yes” would have answered the question, but we know that’s not the sort of answer he or she is looking for. Fortunately, someone kindly responded with a link to Facebook’s developer website. The asker should have done more research on his or her potential project. Then further down the road, he or she could have asked more specific and detailed questions that wouldn’t require a thousand-paged response for a sufficient answer.

## Conclusion

When we rely on others’ generosity and expertise to provide answers to our questions, it should hold that the question we ask should be one that leads to efficient and effective help that not only benefits us, but also the people we ask and others who might ask the same question in the future. Thus, if you have a question… make it a smart one! Asking questions may not always get you the best answer, but asking them in a way that will make others want to answer them will increase the success of finding a good solution and make it a positive experience on all sides.
