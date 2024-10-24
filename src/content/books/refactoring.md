---
title: Refactoring
author: Martion Fowler
img: refactoring.jpg
readtime: 355
description: A guide to improving the design of existing code through small, incremental changes.
buy:
    spain: https://www.casadellibro.com.co/libro-refactoring-improving-the-design-of-existing-code/9780201485677/1109504
    usa: https://www.amazon.com/Refactoring-Improving-Existing-Addison-Wesley-Signature/dp/0134757599
    colombia: https://www.buscalibre.com.co/libro-refactoring-improving-the-design-of-existing-code/9780134757599/p/51344649
---

Refactoring is a controlled technique for improving the design of an existing code base. Its essence is applying a series of small behavior-preserving transformations, each of which “too small to be worth doing”. However the cumulative effect of each of these transformations is quite significant. By doing them in small steps you reduce the risk of introducing errors. You also avoid having the system broken while you are carrying out the restructuring - which allows you to gradually refactor a system over an extended period of time.

My book describes the process of refactoring and spends most of its time explaining how to do the various refactorings - the behavior preserving transformations. The book opens with a simple example that describes the whole process. There are then some introductory chapters that discuss broader issues around refactoring, the “code smells” that suggest refactoring, and the role of testing.

The bulk of the book is around seventy refactorings described in detail: the motivation for doing them, mechanics of how to do them safely and a simple example.

This is the second edition of the book, published late in 2018. The first edition came out in 1999. This is the book that I'm proudest of, in that it's had a high impact on the world of software development. Several development environments now automate many of the refactorings described in the book. Refactoring has become a full-fledged part of the software development lexicon (sadly also leading to *misuse*).
