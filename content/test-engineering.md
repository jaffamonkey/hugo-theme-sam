---
title: "Test engineering"
date: 2018-02-13T13:42:49-05:00
---
### Less is more
Sometimes investing is a feature-rich test framework is a good idea, but starting small is always the best place to start. Tests run as part of CI/CD should be as lean (fast) as possible. Conversely, don’t waste too much time on native coding - packages are there too help you, just be selective and conscious of potential overheads created on the build pipeline server.

### Start non-functional tests early
You don’t need to run a heavy load test to get useful feedback. Security testing is an essential not an option, and investing in code analysis tool will help maintain  performance.

### Accessibility
Web or mobile app accessibility code checks should be covered by default (any excuses are poor excuses). 

> **Importantly, all tests of all kinds should evolve constantly, or they are most likely useless**

_And remember .... developers are our friends_
