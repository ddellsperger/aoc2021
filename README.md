# Advent of Code 2021
## Done on the SnapLogic Intelligent Integration Platform

### Day 1

[slp file](day1.slp)

#### Part 1
I used the Head snap to use a 1-document offset after a copy in order to provide both the current and previous numerical value to do the comparison.

#### Part 2
While you could just use a 3-document offset to do the increase check, I wanted to actually do the sum as my part 2 solution, so I did a triple copy, with two different offsets to use the trick in part 1 to calculate the sum of the 3 values in a running sum fashion. Then used the same work to do the increase/decrease check.