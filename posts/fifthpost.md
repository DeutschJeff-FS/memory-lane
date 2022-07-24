---
title: MVC Architecture
description: This is a post on the concept of mvc and its architecture
date: 2022-07-24
tags:
  - mvc
  - web architecture
layout: layouts/post.njk
---

{% image "./img/mvc-design-pattern.jpg", "MVC design graphic", "(min-width: 30em) 50vw, 100vw" %}

&emsp;What is MVC? As a beginning developer, when I first was introduced to this concept, it was a little difficult to wrap my head around. Since that time, though, it has become much easier to understand and even implement.
<br />
&emsp;Model-View-Controller, or MVC for short, is an architectural pattern used in development to split the application into three components, hence its name and acronym. The View component that presents data from the Model to the user. The Model component holds this data and all the logic related to it. The Controller component acts as the middleman between the View and the Model, waiting for interaction from the View to tell the Model what data is needed. Confused? I was too. So look at it from a real-world example: a person ordering food at a restaurant. In this case, you are the View, a waiter is the Controller, and a chef is the Model (with the data coming from refrigerator). The waiter is the go between you and the chef. They wait on your interaction (receiving your order) to tell the chef what food to prepare, which is then in turn given back to the waiter once the food is ready (the specific data needed for the View) to give to you.
