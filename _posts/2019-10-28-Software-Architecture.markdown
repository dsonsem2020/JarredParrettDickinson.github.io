---
layout: post
title:  "Software Architectures"
date:   2019-10-28 8:04:00 -0500
categories: seminar architectures software
---

With such an array of software architectures covered within An Introduction to Software Architecture by David Garlan and Mary Shaw, the senior seminar class length fell short on providing sufficient definitions for all the options. Specifically, it saw this when defining State Transition Systems. With this platform, I am hoping to take time to shed light on the topic.

State transition systems, as described in the aforementioned article, are systems defined in a set of states and a set of transitions from a state to a new state. While to the point, this definition, perhaps, takes liberties on how a reader may understand the concept. In a course at Washington University at St. Louis, they develop deeper into the concept and provide applied examples. By their definition, a state transition system follows the model of having an environment and a system. The environment is the input set of data records provided and the output of consumed and processed data records. The function of the system itself relies on the use of data management as records and the updating of said records following the reception.

While this may shed some clarity, an applied example may better define the system. Again, provided by [University Washington University at St. Louis CSE 422](University Washington University at St. Louis CSE 422), a hands-on example in a Welding machine. This machine carries out the process of receiving some items that must be welded, weld said piece and maintain records on all welds. 

![architecture](/assets/system.png)

The state solution is then relatively simple. It starts with a pre-state of the piece or item, it receives some input instructing how to make a particular weld, performs weld and stores a complete record of the pre-state, post-state and weld. This system maintains records and executes necessary tasks as intended. However, it may fall short in areas such as in-process changes and may have drawbacks in storage as it maintains states for each object.

As an extension of this, one can explore how it may be possible to marry this with the process control system. To provide a sample problem, how would an engineer correct an error when the weld is underway? For example, if they perceive the welder is running too hot and making poor welds. This could be a justification for the introduction of a system that allows them to make changes while functioning.

Through the introduction of a process control system, this could be organized as a process control architecture in conjunction with the state transition architecture. This addition would introduce the ability to introduce changes during the process. Within the state transition system, this could be either a new record or a change in the present record - thus achieving the same end as intended at the outset of maintaining records and producing welds. Overall, the knowledge of software architecture provides developers with valuable toolset in the development of systems.
