---
title: "Test engineering"
date: 2018-02-13T13:42:49-05:00
---
## _Less is more_
Sometimes investing is a feature-rich test framework is a good idea, but starting small is always the best place to start. Tests run as part of CI/CD should be as lean (fast) as possible. Conversely, don’t waste too much time on native coding - packages are there too help you, just be selective and conscious of potential overheads created on the build pipeline server.

## _Start non-functional tests early_
You don’t need to run a heavy load test to get useful feedback. Security testing is an essential not an option, and investing in code analysis tool will help maintain  performance.

## _Accessibility_
Web or mobile app accessibility checks should be covered by default (any excuses are poor excuses). 

> **Importantly, all tests of all kinds should evolve constantly, or they are most likely useless**

## _DevOps is our friend_
