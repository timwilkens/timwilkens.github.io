---
layout: post
title: Type Erasure in C
---

As I was reading [Hacking The Art of Exploitation](https://en.wikipedia.org/wiki/Hacking:_The_Art_of_Exploitation) I was struck by the following quote

> The important thing to remember about variables in C is that the compiler is the only thing that cares about a variable's type.
> In the end, after the program has been compiled, the variables are nothing more than memory addresses.

I don't know that much about [type erasure](https://en.wikipedia.org/wiki/Type_erasure) but I am familiar with the concept in general. Based on the first sentence on the Wikipedia page

> In programming languages, type erasure refers to the compile-time process by which explicit type annotations are removed from a program

it seems like it *could* be the case that C has type erasure. However, I researched a little via google but I wasn't able to find anything specific discussing C (though plenty about C++). Does anyone know if C would be classified as a language with type erasure?
