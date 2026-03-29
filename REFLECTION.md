# Reflection Questions

## Instructions
Answer the following questions about your learning experience. Each answer should be **at least 5-7 sentences** and show your understanding.

---

## Question 1: What did you learn about multithreading?

**Your Answer:**

[Write your answer here. Discuss specific concepts like thread creation, thread states, how threads execute concurrently, what surprised you, etc.]
I discovered that multithreading enables the simultaneous execution of several tasks within a single program. To better emulate CPU scheduling, each process in this assignment was constructed as a thread. I started utilizing the start() technique after comprehending how threads are formed. Additionally, I learnt how to regulate the execution of threads and how they share resources. In order to guarantee correct execution order, I also learned about thread synchronization via join(). I gained a better understanding of how operating systems effectively manage several tasks thanks to this assignment. All things considered, I now understand multithreading both theoretically and practically.
---

## Question 2: What was the most challenging part of this assignment?

**Your Answer:**

[Describe the specific challenge. Was it understanding the code? Implementing a feature? Using Git? Explain what made it difficult and how it relates to the course concepts.]
Putting the waiting time calculation into practice was the hardest part. Finding the right moment to measure time was challenging. Additionally, I was confused by the output's repeated operations. Analyzing the scheduling logic was necessary to understand why some procedures were repeated. Choosing where to put the calculation in the code presented another difficulty. These difficulties forced me to consider thread execution in great detail. Understanding system behavior was equally as important as coding.
---

## Question 3: How did you overcome the challenges you faced?

**Your Answer:**

[Describe your problem-solving approach. Did you read documentation? Ask for help? Debug systematically? What resources did you use? What strategies worked?]
By closely examining the software flow, I was able to overcome the difficulties. I followed the flow of processes in the ready queue. In order to see the output behavior, I also ran the application several times. When I encountered recurring procedures, I determined the reason and modified the output logic. I printed interim values as one of my debugging strategies. I also went over the lecture materials again to make sure I understood them. This enabled me to progressively resolve the problems one by one.
---

## Question 4: How can you apply multithreading concepts in real-world applications?

**Your Answer:**

[Give specific examples from real applications you use (web browsers, games, mobile apps, etc.). Explain why threads are useful in those scenarios. Connect to what you learned in this assignment.]
Real-world applications like mobile apps and web browsers frequently use multithreading. For instance, a browser can use threads to load several tabs at once. Threads are used in mobile apps for background operations like notifications and downloads. Both performance and user experience are enhanced by this. Applications can stay responsive while carrying out demanding activities thanks to threads. Round Robin and other scheduling algorithms in OS systems guarantee equity. This task improved my comprehension of how these ideas function in real-world situations.
---

## Additional Reflections (Optional)

### What would you like to learn more about?

[Any topics related to threading, concurrency, or operating systems that you're curious about?]

I'm interested in finding out more about thread synchronization and safe resource management. I'm particularly curious about how to prevent race situations and guarantee proper execution when several threads are operating simultaneously.
Beyond Round Robin, I also want to investigate more sophisticated scheduling algorithms and learn how they enhance efficiency and performance. Gaining knowledge of these subjects will enable me to create multithreading applications that are more robust and dependable in the future.


---

### How confident do you feel about multithreading concepts now?

[Rate yourself and explain: Beginner / Intermediate / Confident]
After finishing this project, I am confident in my comprehension of multithreading concepts. I now comprehend the creation, operation, and management of threads within a program. I also discovered how CPU time is distributed across processes using scheduling methods like Round Robin.



[Explain your rating - what do you understand well? What needs more practice?]
I was able to observe how threads transition between various states, including running, waiting, and terminated, thanks to the implementation. I feel at ease using these ideas in comparable situations, but I still want to practice more to advance my abilities.


---

### Feedback on the assignment

[Any comments about the assignment? Was it helpful? Too easy/hard? Suggestions for improvement?]
Understanding how theoretical ideas like CPU scheduling are used in actual applications was greatly aided by this project. I now have a better understanding of how threads and processes work together and how scheduling maintains equity between them.
The learning process was made more interesting by the practical use of elements like priority, context switching, and waiting time. All things considered, the task was well-organized and gave me a solid grasp of multithreading principles.
