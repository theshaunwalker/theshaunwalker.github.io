---
title: Philosophies
layout: default
---
#Philosophies
##Iterative Design
Refactoring older code to a newer design doesnt have to be an “all or nothing” project. Make iterative improvements.

“We cant touch this till we can change it all” means it will never be addressed because its a huge barrier to entry.

Make small steps, constantly, towards the cleaner, better design. It might still take 2 years to get close. But in 6 months you’ll be a lot closer than using the “all or nothing” approach.


# Rules
##Dont Fix a Shit Design
If a bug arises in something that violates basic design principles. Dont waste effort chasing a fix for that bug. Spend the effort refactoring to the better design to avoid the bug being an issue.

Exceptions:
The bug fix is obvious and quick
Refactoring to a clean design would be a huge amount of work where bug finding is very likely to be a lot less effort. (But this is unlikely following “iterative design”)

Write verbose code, avoid one liners
We always need to debug, its easier to debug when the steps are already separated. Rather than needing to refactor to analyse a nested operation (thus introducing risk of red herrings by changing the code you’re debugging)
