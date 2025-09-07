---
title: "Be Confident in Learning Calculus"
date: 2025-09-07
# weight: 1
# aliases: ["/first"]
tags: ["Calculus"]
author: "Haoyun (Jacqueline) Hong"
math: true
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "If I can make it, then you can make it : )"
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "<https://www.3blue1brown.com/content/lessons/2017/essence-of-calculus/figure-4.14-4.57.svg>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: true # when using page bundles set this to true
    hidden: false # only hide on current single page
editPost:
    URL: "https://github.com/HaoyunHong/Haoyun_Jacqueline_Hong/tree/main/content"
    Text: "Suggestion" # edit text
    appendFilePath: true # to append file path to Edit link
---

---
I still remember the feeling of sitting in my freshman calculus class at Tsinghua University, Beijing, China. The blackboard was filled with symbols, theorems, and proofs that seemed completely disconnected from reality. It felt intimidating, like a towering wall of abstract concepts I could never hope to climb. I saw my peers (especially my boyfriend at the time, who is now my husband💗) - it seemed - grasping these ideas with ease, and I questioned whether I had what it took to succeed.


But here's a secret: my journey with calculus didn't end in that lecture hall. It was a winding path that took me through my undergraduate studies, research, and into my professional life. Through repeated exposure and practical application in other fields, such as Computer Science, Artificial Intelligence, Statistics, and Economics, I started to see Calculus not as a collection of complicated formulas, but as a powerful language for understanding change. My initial fear slowly gave way to a quiet confidence.
This blog post is for every undergraduate student who shares this sentiment. It's a reminder that it's okay to struggle. The most important thing is to maintain an open mind and adopt a new perspective. Calculus isn't just a subject you "pass"; it's a tool you "learn to use."

---

Understanding the Essence: The Language of Change
At its core, Calculus is the mathematics of change. It gives us the tools to measure and describe how things change over time or space. Think about it:
Velocity is the rate of change of your position.
Marginal revenue is the rate of change of your revenue with respect to the quantity of goods produced.
Acceleration is the rate of change of your velocity.

Calculus is essentially a framework for understanding these dynamic relationships. It's broken down into two main branches:
Differential Calculus: This is about finding the instantaneous rate of change at a specific point. It helps you find the slope of a curve at a single point, which tells you how fast something is changing at that exact moment.
Integral Calculus: This is about understanding the cumulative effect of all these changes. It helps you find the area under a curve, which can represent the total accumulation of a quantity over a specified interval. The Fundamental Theorem of Calculus even tells us that these two operations - finding slopes and finding areas - are opposites of each other.

Building the Foundation: Key Concepts to Master
Like building a house, you need a solid foundation before you can build the rest of the structure. Here are some fundamental concepts that you should focus on, with detailed definitions from the NYU Stern PhD Math Camp notes:

### 1. Sets and Functions

A set is a collection of objects whose order has no significance (e.g.,`{3,2,1}={1,2,3}={2,3,1}`) and whose multiplicity is generally ignored (e.g., `{1,1,1}={1}`). The objects or members of a set are called the elements of the set. An element a of the set A is denoted as a in A. 

Some examples of sets include:

* $\mathbb{R}$, the set of all real numbers.
* $\mathbb{N}=\lbrace 1,2,3,\dots\rbrace$,  the set of natural numbers.
* $\(3,10]=\lbrace x\in\mathbb{R}:3<x\le 10\rbrace$, a half-open interval.
* $\[0,+\infty\)=\lbrace x^2:x \in \mathbb{R}\rbrace$, which can be described in more than one way.
* $\emptyset$, the empty set.


A function is a special type of mapping that assigns exactly one element from a domain set to an element in a codomvarious ways. Functions can be expressed in many ways, like ordered pairs, tables, graphs, or formulas. 


### 2. Limits


This is the cornerstone of calculus. A limit describes the behavior of a function as its input gets infinitesimally close to a certain value. It's crucial for understanding continuity and derivatives. The limit of a function f(x) as x approaches a is denoted as $\lim_{x \to a} f(x)=A$. This means that for any number $\epsilon_0$, there exists a number $\delta_0$ such that if $0 \< |x - a| \< \\delta$, then $|f(x) - A| \< \\epsilon$.
A key takeaway is that for the limit to exist, the function must approach the same value from both the left and the right.


### 3. Continuity and Differentiability


A function f is continuous at a point $x\_0$ if $f(x\_0)$ is defined and $lim\_{x \to x\_0}f(x)=f(x\_0)$. A function is differentiable at a point if it is both continuous and "smooth," meaning it has no sharp corners or kinks. A key point to remember is that if a function is differentiable, it must be continuous, but the converse is not always true.


For example, the function $f(x)=|x|$ is continuous everywhere, but its derivative does not exist at $x=0$.


### 4. Derivatives

The derivative is the instantaneous rate of change of a function, which is the slope of the tangent line at a given point. It is denoted by $f^{\prime} (x)$ or $\frac{dy}{dx}$. The formal definition of the derivative is:
$f^{\prime} (a)=\lim_{h \to a}​ \left[f(a+h)-f(a)\right]​$
There are specific rules for computing derivatives, such as:


* Power Rule: For $f(x)=x^n$, the derivative is $f^{\prime}(x)=nx^{n−1}$.

* Product Rule: For $h(x)=f(x)g(x)$, the derivative is $h^{\prime}(x)=f^{\prime}(x)g(x)+f(x)g^{\prime}(x)$.

* Chain Rule: For $h(x)=f(g(x))$, the derivative is $h^{\prime}(x)=f^{\prime}(g(x))\cdot g^{\prime}(x)$.

The second derivative of a function, $f^{\prime\prime}(x)$, tells you about the rate of change of the first derivative and is related to the function's concavity and convexity. A function is strictly convex if $f^{\prime\prime}(x)>0$ and strictly concave if $f^{\prime\prime}(x)<0$.


### 5. Integrals

An indefinite integral of a function $f(x)$ is a function $F(x)$ whose derivative is the original function, i.e., $F^{\prime}(x)=f(x)$. It is written as:

$F(x)=\int f(x)dx$

The definite integral of $f(x)$ from $a$ to $b$ is written as:

$\int_{a}^{b} f(x)dx$

This can be interpreted as the area under the curve of a function that is always positive on the interval [a,b]. The image below illustrates this concept visually.


The Fundamental Theorem of Calculus connects indefinite and definite integrals with the formula:

$\int_{a}^{b} f(x)dx = F(b) - F(a)$


This powerful theorem tells us that we only need to know the value of the indefinite integral at the endpoints of an interval to compute the total area under the curve.


Learn from the Best: Resources to Supercharge Your Study


Finding the right resources can make all the difference. My personal journey was greatly helped by finding explanations that weren't just about the "what" but the "why."


1. Paul's Online Math Notes: These notes, which were utilized in the NYU Stern PhD Math Camp materials, are a fantastic and accessible resource. They offer clear explanations and plenty of examples, which are great for reinforcing core concepts and working through problems.


2. 3Blue1Brown: This is, without a doubt, one of the most transformative resources for understanding calculus. Grant Sanderson's video series, "The Essence of Calculus," uses stunning visual animations to explain the geometric intuition behind the concepts. He doesn't just show you how to compute a derivative; he shows you what a derivative is. It's a game-changer for anyone who struggles with the abstract nature of the subject. I highly recommend spending time with his videos and exploring his [website](https://www.3blue1brown.com/):



3. Official Course Materials: Don't forget your primary course materials! The NYU Stern PhD Math Camp notes used for this blog post are a great example of a clear, structured resource that breaks down complex topics into digestible parts. Use them as a blueprint for your own study, making sure you can explain each concept in your own words.


### A Final Word of Encouragement


Learning calculus is a marathon, not a sprint. There will be moments of frustration and confusion. But with persistence and the right mindset, you will get there. Remember my journey: from a confused freshman at Tsinghua to someone who now uses calculus with confidence in my work. The key is to see it not as a list of rules to memorize, but as a fascinating world of ideas to explore.
Believe in your ability to master this subject. The rewards, both in your academic and professional life, are well worth the effort.



### References

* 3Blue1Brown. ["The Essence of Calculus"](https://www.3blue1brown.com/?v=essence-of-calculus).