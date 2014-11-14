PHP Programming best practices
------------------------------

PHP is a complex language that has suffered years of twists, bends, stretches, and hacks. It's highly inconsistent and sometimes buggy. Each version has its own unique features, warts, and quirks, and it's hard to keep track of what version has what problems. It's easy to see why it gets as much hate as it does sometimes.

Despite that, it's the most popular language on the web today. Because of its long history, you'll find lots of tutorials on how to do basic things like password hashing and database access. The problem is that out of five tutorials, you have a good chance of finding five totally different ways of doing something. Which way is the "right" way? Do any of the other ways have subtle bugs or gotchas? It's really hard to find out, and you'll be bouncing around the internet trying to pin down the right answer.

That's also one of the reasons why new PHP programmers are so frequently blamed for ugly, outdated, or insecure code. They can't help it if the first Google result was a four-year-old article teaching a five-year-old method!

This document tries to address that. It's an attempt to compile a set of basic instructions for what can be considered best practices for common and confusing issues and tasks in PHP. If a low-level task has multiple and confusing approaches in PHP, it belongs here.