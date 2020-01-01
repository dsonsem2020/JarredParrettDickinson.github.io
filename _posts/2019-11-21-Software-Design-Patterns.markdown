---
layout: post
title:  "Software Design Patterns"
date:   2019-11-21 9:38:00 -0500
categories: seminar pattern lock
---
During the latest discussion, the class provided only a cursory glance at the many different types of software design patterns. In that, we took about 10 minutes to educate ourselves and present on one of those patters. While that was partially informative, it may have been a bit too much of a superficial glance. I am going to use this blog to dive into the more granular parts of the pattern my group covered: Lock.

![lock](/assets/lock.png)

The concurrency family of patterns is those that involve the practice of multi-threading. To best understand the concept of a lock, it is first necessary to understand multithreading. The concept of multithreading can be difficult to understand; however, [GeeksForGeeks](https://www.geeksforgeeks.org/multithreading-in-operating-system/) suggests an approach that is more approachable. They state that a thread is much like a task such as writing something or reading something. While they may not be complicated, concurrent execution of both is impossible with the same resource. By this, imagine doing two relatively work-intensive tasks simultaneously. Whether it is juggling or simply clapping, these tasks to a person require two hands. Formally, this is known as mutual exclusion or mutex.

 As a member of the concurrency family, a lock is a tool used within the scope of its practice. Intuitively, the lock ensures that, for a particular task, the proper resources are allocated. Locks can be used in a variety of ways from the procurement of memory to the securing of a connection one a particular port within a system. Much more can be investigated when considering locks, but I hope this can provide a quick introduction.
