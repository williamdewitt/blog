---
layout: post
title: 30 Days of Testing - Day 05
tags: [testing, 30daysoftesting]
---

## Read and comment on one blog post

I just finished reading Michael Boltons series on [Breaking the Test Case Addiction](https://www.developsense.com/blog/2019/01/breaking-the-test-case-addiction-part-1/) and oh boy here do I begin... oh yes,  I am never writing another "test case" again.

For a long time it has bothered me.  This idea of writing down step for step, detail for tiny detail, on every little thing you are planning to test.  I mean don't get me wrong, you need an plan or some idea of how you are going to approach the testing of a solution.  The way we would go about it though just seemed... wrong.

The team would start by writing a test plan (which was never signed off) against requirements (that were never signed off).  Then, we would go about analyzing the requirements and writing test cases.  I have found that the sole purpose of test cases though is for management to have some way of drawing a conclusion to the state (read time still left to finish testing) of testing. ie. Will we be done by the end of the already shortened test cycle.

This just emphasizes my troubles about reporting but that will be another exercise.

There are plenty of issues that arise from this type of testing and management style.  Firstly, a tester will end up writing the same steps over and over and over again which creates some problems of its own.  Maintainability goes out the window because how you have 100 test cases that all start the same way. And, from a reporting point of view, a large chunk of the steps at this point are just noise.

Here is a nice one.  A manager look at the test but is really only interested in the count of steps, then looks at the team and the time allocated to testing which in turn leads to the formula:

1000 steps / 5 testers / 10 days = 20 steps/day/tester = burn down chart to manage the project.

Easy and clean, and we get a percentage complete.  The problem comes in when you fall a little behind,  well the solution there is "Seen as we already passed the first step, then, technically the first step of all 100 test cases pass"  so you can just pass the first step until you hit your quota for the day and on the flip side,  if you are ahead, no problem, kick back and do nothing cuz you have completed your quota for the day... right?

No, not right at all!  When you write test cases down to the detailed level then all you are doing is parrot work and I think that this might also be the reason why I so often hear "anyone can test" and the latest one "if my developers wrote better code then I wouldn't need testers"...

As Michael put it "Testing is a performance".

My ranting is done for now but far from over.  I will be coming back to this.

My take away is that there are far more informative and value adding ways to produce test artifacts and in my books, a test case does not make it on the list.