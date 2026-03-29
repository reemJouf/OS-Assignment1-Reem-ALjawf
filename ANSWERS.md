# Assignment Questions

## Instructions
Answer all 4 questions with detailed explanations. Each answer should be **3-5 sentences minimum** and demonstrate your understanding of the concepts.

---

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes?

**Your Answer:**
A thread is a smaller unit of execution inside a process that shares memory, whereas a process is an independent program with its own memory and system resources. The creation and management of processes is more labor-intensive and involves greater overhead. The creation of threads is quicker and lighter. Because threads are more effective and manageable within a single program, they were employed in this project to emulate processes. We may mimic concurrent execution without actually generating system processes by using threads.

[Write your answer here. Consider: What is a process? What is a thread? How do they differ in terms of memory, resources, creation overhead? Why are threads more suitable for this simulation?]

---

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from your program output.

**Your Answer:**

[Write your answer here. Describe the specific behavior - where does the process go? When does it run again? Give an example from your actual program output showing a process that was re-queued.]

A process is pushed to the end of the ready queue in Round-Robin scheduling so that other processes can run if it does not complete within its time quantum. My program's output makes this behavior quite evident.

Example from my output:
```
P1 completed quantum 4000ms  
Remaining time: 5343ms  
P1 yields CPU for context switch  
P1 (Priority: 3) added to ready queue  

[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:**
[Explain what's happening in the output snippet you pasted]
In this instance, process P1 had 5343 milliseconds left because it failed to complete its execution inside the allotted 4000 milliseconds. As a result, it returned to the ready queue after yielding the CPU. Later, when its turn comes again, it reappears at the end of the line and resumes execution. This demonstrates how Round Robin permits all programs to share CPU time, ensuring fairness.

---

## Question 3: Thread States

**Question**: A thread can be in different states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (P1) from your simulation.

**Your Answer:**
## Question 3: Thread States

The lifecycle of process P1 in my simulation can be explained using the thread states as follows:

1. **New**:
   P1 is in the New state when the thread is created but has not started yet. This happens when a thread object is created for the process:

Thread thread = new Thread(process);
```

---

2. **Runnable**:
   P1 enters the Runnable state when it is added to the ready queue and becomes ready for execution. In my program, this is shown when the process is added to the queue and waits for CPU scheduling:
P1 (Priority: 3) added to ready queue
```

---

3. **Running**:
   P1 is in the Running state when it starts executing its task in the CPU. This is clearly shown in the output when the process begins its time quantum:
P1 executing quantum [4000ms]


---

4. **Waiting**:
   P1 enters a waiting-like state during execution when `Thread.sleep()` is used inside the `run()` method. This simulates execution delays and represents the process being temporarily inactive before continuing execution.

---

5. **Terminated**:
   P1 reaches the Terminated state when it finishes all its execution and its remaining time becomes zero. This is shown clearly in the output:


P1 completed quantum 1343ms  
Remaining time: 0ms  
P1 finished execution!

---

This sequence shows how P1 moves through all thread states during the simulation based on the program behavior and output.

[Write your answer here. For each state, explain when P1 enters that state during the simulation. Use your understanding of the code to trace through the lifecycle.]

1. **New**: [When is P1 in New state?]

2. **Runnable**: [When does P1 become Runnable?]

3. **Running**: [When is P1 Running?]

4. **Waiting**: [When/why would P1 be Waiting?]

5. **Terminated**: [When is P1 Terminated?]

---

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. Explain why this scheduling algorithm works well for those scenarios.

**Your Answer:**
Example 1: Internet browsers

Browsers manage several tabs and tasks at once.

Why Round-Robin is effective in this situation:
It guarantees that every tab receives CPU time without causing the system to freeze. It offers responsiveness and impartiality.

Example 2: Operating Systems

The operating system schedules several active programs.

Why Round-Robin is effective in this situation:
It keeps a single program from using all of the CPU. By giving each process a fair amount, system performance is improved.

---

## Summary

**Key concepts I understood through these questions:**
1. Round-Robin scheduling and the equitable use of time quantum to distribute CPU time among processes.
2. How unfinished processes are re-added to the ready queue.
3. A thread's execution lifecycle, including New, Runnable, Running, Waiting, and Terminated. 

**Concepts I need to study more:**
1. Safe handling of shared resources and thread synchronization.
2. The variations in performance of advanced scheduling methods.
