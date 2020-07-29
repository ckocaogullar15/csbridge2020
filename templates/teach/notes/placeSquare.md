template: templates/teach/notes/template.ptl
problemtitle: Place Square

This is the first activity for the morning.  It gives students practice with `while` loops along with `for` loops in Karel.  The challenge is that the program must work in a variety of worlds (any square world other than 1x1).  Generalized programs are important, but hard, so you may need to walk students through these concepts.  The hardest part is figuring out how to make multiple beeper lines one after the other.  When helping students with loop conditions, it can help to talk through what it is that may no longer be true once we want the loop to stop that is true when we want the loop to continue.  It's also worth highlighting when different types of loops are appropriate - e.g. we always know that we will be drawing 4 beeper lines, so a `for` loop is appropriate there.  But when drawing a single beeper line, we don't know how many beepers we will be putting down, so a `while` loop is appropriate there.

**Milestone:** draw a single beeper line across one side of the world.