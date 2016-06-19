---
layout: post
title:  "C++ your way to the browser!"
date:   2016-06-05 12:00:00 +02:00
categories: projects
---
Hey everybody,
it's been a harsh week over here, with exams and deliveries all over the place.

I want to show you one of the deliveries, from my Compilers course. More precisely,
I'll show you a C++ interpreter for the web.

<img src="/img/posts/js-cpp-logos.jpg" alt="js-cpp-logos" style="width: 400px; display: block;
    margin-left: auto;
    margin-right: auto;"/>

Written in Coffeescript, Node.js and with the help of Browserify
we built a little system capable of performing syntactic analysis of the code and interpret it right away. For this to happen, semantic code analysis previous to the execution is needed. This is due to the
nature of C++, which is a compiled language and a lot of checking is done in order
to ensure things like type-safety or returning the correct type from a function.

This project is still in its early stages and a lot needs to be done. Expect frequent
updates in the course of the summer and in September, when classes start again.
You can checkout our project [here](https://github.com/jutge-org/cmm) or watch a little
[demo](http://c--lang.xyz/) showing its core functionalities.
