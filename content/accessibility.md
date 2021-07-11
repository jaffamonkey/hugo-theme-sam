---
title: "Accessibility"
date: 2018-02-13T13:42:49-05:00
images:
    - /clients.png
---
> Accessibility is commonly wrapped up in other testing activities, but it is worthy of focus effort. A lot can be done to mitigate accessibility errors, by investing time at design phase and integrating checks in the CI pipeline.

# WCAG

> Accessibility involves a wide range of disabilities, including visual, auditory, physical, speech, cognitive, language, learning, and neurological disabilities. 

[Web App Accessibility Standards (WCAG 2.1)](https://www.w3.org/TR/WCAG21/)

[Mobile App Accessibility Standards (WCAG 2.0)](https://www.w3.org/WAI/standards-guidelines/mobile/)

Both [Apple](https://www.apple.com/uk/accessibility/vision) and [Android](https://developer.android.com/guide/topics/ui/accessibility) is very proactive with tools and development standards of their own, based on w3 web app Accessbility standards, but with additional attention to mobile-specific challenges.

## Level A
Minimum level – without addressing these items, barriers exist that cannot be overcome by assistive technology.  This level affects the broadest group with the most benefits and is essential.

### Standard Level A Checks

- Run code-level checking tool
- Navigate the app with keyboard-only

## Level AA
More accessible – With the minimum level of support, some barriers will still exist which impact certain groups of users.  The criteria at this level establish a level of accessibility which should work with most assistive technology on desktop and mobile devices. Addressing Level AA criteria may impact the look of a page or affect site logic to a greater extent.

While some apps will sail through Level AA, some may struggle - for example, an app that depends on sight to annotate an image. A first important step is to realise Acessibility is an evolving improvements exercise.  Just because your app passes in Sprint 5, it doesn't mean it will pass in Sprint 7. So treat an audit as a review, with errors and suggestions provides - most fails are simple fixes and in many cases duplicated. Document this (honestly) in an accessibility statement, that you can keep updated, as your app progresses and improves.

### Standard Level AA Checks
Level AA will be more demanding check of the app, but striving for this will improve not only Accessibility of the app, but the quality.

- Screen reader
- Verify zoom in up to 300% without the text spilling off the screen
- Run code-level checking tool
- Navigate most of the app using speech recognition software

_[Contact me](mailto:paullittlebury@gmail.com) for further discussion of how I could help. No commitment. You may be interested in getting a comprehensive review, or assistance in putting Accessiblity in a [shift left state], in the SDLC._
