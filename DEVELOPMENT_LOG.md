# Development Log

## Instructions
Document your development process as you work on the assignment. Add entries showing:
- What you worked on
- Problems you encountered
- How you solved them
- Time spent

**Requirements**: Minimum 5 entries showing progression over time.

---



Entry 1 - [March 27, 2026, 2:00 PM]

What I did: Started the assignment and set up the project

Details:
-creat gitgub account using my university email
-Forked the repository and renamed it
-added my studentID in SchedulerSimulatiob.java
-Opened the project in VS Codeand Ran the program for the first time

Challenges: Did not understand how the scheduler loop works

Solution: Reviewed lecture slides and traced the code step by step

Time spent: 2 hours

---


### Entry 2 - [March 27, 2026, 4:00 PM]

**What I did:** Analyzed the SchedulerSimulation class and understood Round Robin scheduling

**Details:**

* Analyzed the SchedulerSimulation class to understand how the program works
* Studied the concept of Round Robin scheduling
* Tracked the program execution step by step to understand the flow

**Challenges:** Found it difficult to understand how processes move in the ready queue

**Solution:** Followed the execution step by step and focused on how processes are scheduled

**Time spent:** 4 hour

---

### Entry 3 - [March 27, 2026, 9:00PM]

**What I did:** Implemented Feature 2 (context switch counter)

**Details:**

* Added a variable to count context switches
* Incremented it inside the scheduling loop

**Challenges:** Was unsure where to increment the counter

**Solution:** Tested different positions until the output was correct

**Time spent:** 2 hours


---
Entry 4 - [March 28, 2026, 1:00 PM]

What I did: Implemented Feature 1 (process priority)

Details:

Added priority attribute to Process class
Generated random priority values
Displayed priority in output

Challenges: Confusion about random number generation

Solution: Used Random class with correct range

**Time spent**: 2 hour

---
Entry 5 - [March 29, 2026, 4:00 PM]

What I did: Implemented Feature 3 (waiting time)

Details:

Used System.currentTimeMillis() to calculate waiting time
Added waiting time output for each process

Challenges: Output showed repeated processes

Solution: Fixed output to display each process once

Time spent: 3 hours


---

### Entry 6 - [March 30, 2026, 5:00 PM]

**What I did:** Final testing, debugging, and video preparation

**Details:**

* Verified all features are working correctly
* Checked output formatting
* Reviewed code for any errors
* Prepared explanation points for the assignment video

**Challenges:** Minor formatting issues in output

**Solution:** Adjusted print statements

**Time spent:** 3 hours


---

## Summary

**Total time spent on assignment**: 16 hours

**Most challenging part**: Understanding how processes move in the ready queue and how Round Robin scheduling manages execution order

**Most interesting learning**: Learning how Round Robin scheduling works in practice and how processes are executed step by step using threads

**What I would do differently next time**: Start earlier and try to understand the code structure before implementing features
