---
layout: post
title: "Discourage Abuse"
date: 2022-06-22
tags: C# OOP abuse properties
excerpt_separator: <!--end_of_excerpt-->
---

I've come across a lot of legacy code which has been worked on by many developers over the years
and of course style and convention changes with time.
A common problem has been that the code isn't always that object oriented (to be nice) and classes are often anemic [^](Behavior is leaked due to that internal state is accessible from outside of the class).

<!--end_of_excerpt-->
So what is the remedy? Of course to not leak internal state or even details. 
If a method or a property is not available, you can't change or call it.


