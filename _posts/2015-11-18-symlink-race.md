---
layout: post
title: Symlink Race
---

While reading today I came across the term "temp race". After some googling I was able to find references to both [Symlink race](https://en.wikipedia.org/wiki/Symlink_race) and [Insecure File Creation](https://www.owasp.org/index.php/Insecure_Temporary_File). In particular, I like this use case from the Wikipedia article

> A malicious user can create a symbolic link to a file not otherwise accessible to him or her. When the privileged program creates a file of the same name as the
> symbolic link, it actually creates the linked-to file instead

I think this idea is really clever and doesn't seem like something most developers would consider while writing code. Given that an attacker would need both read and write privileges as well as the ability to create symlinks this seems mostly useful for privilege escalation.
