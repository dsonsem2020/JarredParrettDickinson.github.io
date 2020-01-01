---
layout: post
title:  "Software Testing"
date:   2019-11-28 9:58:00 -0500
categories: seminar testing UAT PROD DEV SIT
---

When creating a software application, it is necessary to understand the importance of testing before releasing the product to the public. While many undergraduate institutions will touch on the importance of testing, it can be difficult to see it in an applied context. As both a personal exercise and an effort to assist fellow undergraduates in their transition from academic to industry world, I am taking some time to layout common pipeline for testing in the industry.

![cycle](/assets/cycle.png)

A common layout for software within the industry is the using of environments by the name of DEV, SIT, UAT, and PROD. Each of these 4 environments holds a place and both written and unwritten rules persist in each to ensure sufficient and valid testing.

### DEV ###
The dev or development environment is one in which engineers are most comfortable. It is the environment where they may build, destroy and try out. This environment allows developers to make changes to code and deploy on the fly without any approvals from other branches or teams.

### SIT ###
The SIT or system integration testing environment follows dev in that it is the handoff from the developer to the QA tester when there is a relative completion of the changes. For many teams, this can be a collaborative process where the QA tester looks to the developer for clarification if needed on certain things. For many teams, the SIT environment may be available to the developers for deployment.

### UAT ###
 The UAT or user acceptance testing environment follows the internal testing of SIT and is the first formal departure of control from a development team. In many development pipelines, it is only permissible for the QA tester to deploy to UAT as this prevents any changes that have not been fully tested internally. As an aside, the separation of duties at this point can be an effective tool for the mitigation of errors. This environment is also often the closest in appearance to production without the scale of production that may demand.

### PROD ###
PROD or production environment is the final step in the software development pipeline. Once the developers have made their changes, the QA testers have signed off and deployed to UAT, the code or version is finally pushed to production for real-time use.

The software testing pipeline is one in which it can seem unnecessary to have separation of duties but is all too important. This has been a brief delve into the understanding of testing in the industry. I hope it can provide anyone who is reading some provisional knowledge for understanding industry testing.
