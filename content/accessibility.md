---
title: "Accessibility"
date: 2018-02-13T13:42:49-05:00
images:
    - /clients.png
---
> Accessibility is commonly wrapped up in other testing activities, but it is worthy of focus effort.

A lot can be done to mitigate accessibility errors, by investing time at design phase and integrate checks in the CI pipeline.

> Level AA marks a definite point where a screen reader user can naviage the app.

While some apps will sail through Level AA, some may struggle - for example, an app that depends on sight to annotate an image. A first important step is to realise Acessibility is an evolving improvements exercise.  Just because your app passes in Sprint 5, it doesn't mean it will pass in Sprint 7. So treat an audit as a review, with errors and suggestions provides - most fails are simple fixes and in many cases duplicated. Document this (honestly) in an accessibility statement, that you can keep updated, as your app progresses and improves.

- Listen to most of the app using a screen reader
- Verify zoom in up to 300% without the text spilling off the screen
- Run code-level checking tool
- Navigate most of the app using speech recognition software
