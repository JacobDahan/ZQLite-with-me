---
title: Part 0 - Introduction to the RDBMS 
date: 2024-06-08
---

## Overview

I don't know how databases "work". As a software engineer, I program against them every day.
I know how to store data in them, and retrieve that data later.
And I know there is no such thing as a "simple" database.
But beyond that, the average DBMS is, more or less, a black box.

I want to understand databases, and I can't think of a better way than to build one myself.
But jumping in head-first is... well... overwhelming. And probably stupid.

To learn the basics, I've decided to follow the Carnegie Mellon University [15-445/645 Intro to Database Systems course](https://youtu.be/vdPALZ-GCfI?si=X_blfAtr-8o0KiOb),
which is freely available on YouTube along with [all of the relevant coursework](https://15445.courses.cs.cmu.edu/fall2023/assignments.html).
As I complete the course, I'll post my project code here, along with diagrams and relevant learnings.

Because I am a masochist, I've also decided to write the SQLite clone entirely in Zig -- a language which I have never used.
To learn the lagnuage, I'll be completing the coursework in Zig, too. This will probably be a mess.
I expect (or hope) that things will become more idiomatic as the projects move forward,
but this is a learning process, so I won't shy away from publishing my naivete.

Well, I've delayed long enough. Let's begin...

---

### Buffer Pool Manager

---

[Home](../)
