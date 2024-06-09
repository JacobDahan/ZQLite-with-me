---
title: ZQLite With Me 
---

# What is ZQLite?

I'm building a clone of [SQLite](https://www.sqlite.org/index.html) from scratch in [Zig](https://ziglang.org/).

### Why follow along?

In this process, I'll learn database systems fundamentals and, along the way, the Zig language. 
The project will be split into three portions. 
* First, we'll learn how modern RDBMS function, following a wonderful course from Carnegie Mellon University. 
* Next, we'll discover Zig, widely considered the best modern "C replacement." 
* Finally, we'll build SQLite... in Zig!

I'll document every step of the away, providing useful resources, so you can learn with me.

### Why clone SQLite? 

Learning is doing. But doing __too much__ does not mean learning more.
So if we want to discover the inner workings of databases, re-creating PostgreSQL from scratch would probably be more head-aches, and less learning.

SQLite is a simple (if one can call a DBMS simple), highly performant, and widely used RDBMS.
It uses a single file to store the entire database and it contains a reduced feature set as compared with more enterprise-ready RDBMS options.
That being said, it's hard to go a day without somehow interacting with it (at time of writing, [there are over 1T SQLite databases deployed](https://sqlite.org/mostdeployed.html)).
It's hard to think of a better option to clone.

And I'm not the first to clone SQLite: 
This project is heavily inspired by [this (unfinished) C clone of SQLite](https://cstack.github.io/db_tutorial/), 
which deserves immense credit for being the awesome resource that it is.

### Dive right in!

Let's start building ZQLite! But first, let's [find out how database systems work]({{site.baseurl}}{{site.parts.first.url}})...

Or, dive back in to a specific chapter...

# Table of Contents
{% for part in site.parts %}- [{{part.title}}]({{site.baseurl}}{{part.url}})
{% endfor %}
