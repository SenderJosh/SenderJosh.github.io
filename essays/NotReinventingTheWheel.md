---
layout: essay
type: essay
title: Not Reinventing The Wheel
date: 2017-02-09
labels:
  - UI Frameworks
---

<h2>My History</h2>

Cascading Style Sheets (CSS) are almost entirely new to me. I used to dabble very little, just enough to understand the basic syntax was like, such as the difference between defining a <i>class</i> and an <i>id</i> among them. I never went beyond that because I never saw myself as a front end person, having a not-so-great taste or much interest in design. My intention was purely to learn enough so if I wanted to, I might be able to recreate Facebook’s layout- or maybe make a beautiful landing page for my online resume.

Unfortunately I did not know of the existence of UI frameworks so every attempt and all learning was being done with the base of CSS. Needless to say, my motivation dwindled quickly after coming to the realization of how much time and effort I would need to recreate something as basic as a landing page.

<h2>The Wheel</h2>

As courageous and as ambitious a goal would be to create my own UI framework, needless to say, I would be doing the virtual equivalent of building my own piano. There would be a lot of between-steps to learn, such as browser compatibility, and the general sweat work that comes with building any sort of application on top of the application I aim to build using my framework.

Reinventing the wheel for my situation would be very tedious and unnecessary given how many open source options that exist to fulfill my exact needs. Other than not having to learn the steps to develop the UI framework, I would also not have to deal with maintenance or other updates that will be required for future projects because a larger team of developers will be working on them.

In addition, many use content distribution networks (CDNs) that I can use to directly reference in my HTML. Doing so will allow me to switch to and from version by just changing the number. For example

```
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.2.2/semantic.min.css">
```

To 
```
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/semantic-ui/2.2.3/semantic.min.css">
```

In my case with Semantic UI, the CSS classes are very English-oriented. This makes development more seamless and learning the framework less painful. The bulk of the work then becomes learning the framework and when to implement each part, rather than learning how to create a framework and implement it in my site.
