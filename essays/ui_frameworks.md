---
layout: essay
type: essay
title: "Enjoying Bootstrap 5 and Its Simplicity"
# All dates must be YYYY-MM-DD format!
date: 2026-02-26
published: true
labels:
  - Essay
  - UI Frameworks
  - Bootstrap 5
---

Designing a website isn’t always easy as everyone seems to assume it is. It requires lots of effort to get all the contents, buttons, images, navigation bars, etc… to be placed according to the developer’s vision. And implementing all of these in pure HTML and CSS codes, although possible, for the person behind doing all of this tedious amount of work, however, would take close to forever to get the first version done. Having to manually configure the correct HTML tags and CSS attributes to fit your needs may lead to massive amounts of lines of code, and it is exhausting to navigate through the files just to find the button you want to change within a field of diverse tags.

At this point, a developer should be asking themself is there a quicker way to get these things done so that they don’t have to sit for hours on end trying to center a div or perfecting their navigation bar. Learning how to build a website should be fun, but should not be about writing repetitive codes that barely make a visual difference. Hence, modern frameworks built for styling websites are introduced, and the one that I’m working and enjoying myself with is Bootstrap 5. It is the equivalent of having a professional designer by your side, guiding your layout and styling choices so you can focus more on the core functionality of your application and not working up from scratch.

# Forming a Shortcut

Take a following look at this sample HTML code with Bootstrap 5 implemented as an example:

```
<nav class="navbar navbar-expand-lg navbar-dark bg-dark rounded">
  <div class="container-fluid">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Projects</a></li>
        <li class="nav-item"><a class="nav-link" href="#">Contacts</a></li>
      </ul>
    </div>
  </div>
</nav>
```


