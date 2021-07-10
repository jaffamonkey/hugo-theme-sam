---
title: "Test engineering"
date: 2018-02-13T13:42:49-05:00
---
## _Less is more_
Sometimes investing is a feature-rich test framework is a good idea, but starting small is always the best place to start. Tests run as part of CI/CD should be as lean (fast) as possible. Conversely, don’t waste too much time on native coding - packages are there too help you, just be selective and conscious of potential overheads created on the Build server. Scope of automation

## _Start non-functional tests early_
You don’t need to run a heavy load test to get useful feedback. Security testing is an essential not an option, and investing in code analysis tool will help maintain  performance.

## _Accessibility_
Web or mobile app accessibility checks should be covered by default (any excuses are poor excuses). 

## _Exploratory testing_
Exploratory testing is a mindset that can be applied to automation. Whilst test automation is primarily testing for regressions (as well as demontsrating progress), non-functional testing has more scope for this. For example load testing involves defining

> **Importantly, all tests of all kinds should evolve constantly, or they are most likely useless**

## _DevOps is our friend_
Test engineering can help beleaguered DevOps in several ways: Dockerizing your test framework (better portability), keep package-count low (and specify versions so pointless updates do not occur on every install), use cloud service to store reports and other test artifacts (like screenshots)
