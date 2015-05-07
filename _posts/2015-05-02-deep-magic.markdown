---
layout: post
title:  "Deep Magic"
date:   2015-05-02 23:35:34
categories: jekyll update
---

**This is still a draft. Any feedback is welcome.**

- - -

In past few years, Deep Learning started to permeate our daily lives with many extremely useful applications and the number keeps growing every minute. Most of the time we are not even aware of the underlying technology because it works like *magic*. And not only for the end users, but also for practitioners of this deep dark secrets.

# Year After

Last year I published a short video demonstration of interactive approach to creating and understanding systems based on the connectionist paradigm in cognitive modeling. To put it plainly, it’s an environment that lets you explore artificial neural networks by playing with them. Here is the video if you haven’t see it yet…

<iframe width="560" height="315" src="https://www.youtube.com/embed/JsyKf_RlWLo" frameborder="0" allowfullscreen></iframe>

So what is it?

# Visual Programming

Even though the prototype was based on universally hated *Visual Programming* paradigm, people liked it. As you can see from the video, visual programming is about boxes and arrows.[^1] They enable a person to create a program in a visual manner instead of typing code in some programming language. Programmer simply connects some boxes with arrows and *voilà* – there is the program.

[^1]:  Well, not really arrows, but simple lines in this case.

This paradigm is good especially for the beginners. Traditional coding can provide overwhelming number of possibilities that can confuse and discourage hopeful novices. On the other hand, visual programming environment shows everything in a nice form, so the programmer can easily understand what is going on.

# Thought Vectors

It is not the rule, but many visual programming environments do not show the state of the program, only it’s architecture. Here is a missed opportunity, because showing the state enables programmer to better understand the system by seeing the program in action. Instead of mentally running it in our heads, we can directly observe it and learn from it. This feature was the principal idea behind the simple prototype.

The state in context of neural nets is simply a collection of activations of every unit. By visualizing the state of the neural net, we can say that we can see what it is thinking. To borrow an analogy from the neuroscience – by looking on a MRI scan we can say something about the brain structure, i.e. it’s architecture, but a fMRI scan can show us much much more.

# Deutch Limit

Visual programming paradigm is nothing new – it had its glory in the past, but never gained momentum necessary to make a difference. Visual programming as it was popular in the 1980s was basically a general purpose programming environment where you can program any functionality you can think of. But there was a major design flaw that killed the promising concept. The main objection against visual programming is called [Deutch Limit](http://www.wikiwand.com/en/Deutsch_limit) and it can be summarized by this comment:

> "Well, this is all fine and well, but the problem with visual programming languages is that you can’t have more than 50 visual primitives on the screen at the same time. How are you going to write an operating system?"

In other words, there is no way how you can use visual programming to create complex systems. This is a reasonable argument against this approach, but what followed was comparable to the neural net winter after Minsky and Pappert wrote off Perceptrons. This was basically the reason why visual programming did not make any significant splash.

# Visual Scripting

However, visual programming lived a secret life hidden in places where people think visually, in contrast to symbolic representations that pervade general purpose programming languages. This field is dominated by creative people who use computers in an artistic way and often do not have technical training that would enable them to use traditional programming languages.

What is really interesting about visual scripting environments is that they are not burdened by thinking of visual programming as a general purpose system, therefore they are much more streamlined to the needs of the domain.

# Caffe

In the Deep Learning community, [Caffe framework](http://caffe.berkeleyvision.org) is really an exceptional piece of software. Its developers chose different way of expressing neural networks and it somehow opened my eyes. You don’t need a general purpose programming language to define an extremely powerful system. You see? By composing predefined components in a declarative way you are able create a system that is able to learn without any silly concepts as if-then-else, for loops, etc. You can throw away everything you know about programming and start from scratch.

# Different Programming

Machine Learning is really an other kind of programming that significantly differs from the traditional sense of the word. At the end of both “programmings” is a system capable of performing some task, but the ways you took are really unlike. It’s like comparing  assembly language to JavaScript. Theoretically, you can achieve same result, but the time pressure won’t let you.

# To the Future

Right now, we are at the starting point. These thoughts are just a reminder that Artificial Neural Networks, Deep Learning or whatever it is going to be called next, can and must be approachable. You must be able to learn about it by play.