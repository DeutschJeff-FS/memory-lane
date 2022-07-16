---
title: APIs in React - Best Practices
description: This is a post on API best practices with React.
date: 2022-07-11
tags:
  - api
  - react
  - react-hooks
layout: layouts/post.njk
---

---

{% image "./img/reacthooks.png", "React Logo with Fish Hook", "(min-width: 30em) 50vw, 100vw" %}

&emsp;Working with APIs is a great way to add some fun features and information to your website. When using APIs in React, however, there are a few things to keep in mind. Calling an API tends to have, what is called, "side effects." Within the React component lifecycle method, what this means is the API is rendered at the same time as the React component it is a part of. While that's not always bad if done correctly, it isn't best practice. Plus, if you have an error somewhere in your code that causes the component to re-render, then your API keeps getting called, sometimes almost infinitely. And if you have a limited amount of calls you can make to your API, then that's a very big, and sometimes costly, problem.
