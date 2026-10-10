# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | Lina Khalid Albarqi |
| **Student ID** | 446540002 |
| **University Email** | 446540002@std.psau.edu.sa |
| **GitHub Username** | 2l8ena |
| **Repository Link** | https://github.com/2l8ena/OS-Assignment1-Lina-Khaled |
 
---

## 🎥 Video Link

**Video Link**: [![Watch Video](https://img.shields.io/badge/▶_WATCH_VIDEO-2ea44f?style=for-the-badge)](https://drive.google.com/drive/folders/1VQuv2YEusnWYQXzJ80Obldum61FALf8A)

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [October 6,2026, 7:30 PM]
**What I did**: Set up my repository and set up my student ID

**Details**:
1. Create Github with my university E-mail and make it public
2. Forked the starter repository and rename it to OS-Assignment1-Lina-Khaled
3. Set my actual student ID in SchedulerSimulation.java 

**Challenges**:
I wanted to make sure my student ID was updated correctly and posh it to Github

**Solution**:
I checked the file, committed the change, and verified in my repository

**Time spent**:
20 minutes
---

### Entry 2 - [October 7,2026, 11 AM]
**What I did**:
Implemented Feature 1

**Details**:
1. Implemented Process Priority
2. Generated random priorities from 1 to 10
3. Display the priority when a process entered the ready queue

**Challenges**:
I need to make sure the priority was displayed without changing in FIFO of Round-Robin scheduler

**Solution**:
I added a getter method for priority and only it for display puposes

**Time spent**:
50 minutes
---

### Entry 3 - [October 7,2026, 5 PM]
**What I did**:
Tested and debugged Feature 1

**Details**:
I ran the program and checked the output to make sure every process displayed its priority correctly

**Challenges**:
I encountered a compilation error caused by incorrect string concatenation in the output statement

**Solution**:
I corrected the missing operators and tested the program again until it ran successfully

**Time spent**:
25 minutes
---

### Entry 4 - [October 8,2026, 9 PM]
**What I did**:
Implemented Feature 2

**Details**:
1. I added a static counter to track the total of context switches 
2. Displayed the final total after all processes completed

**Challenges**:
I had to determine the correct location where the counter should increase

**Solution**:
I incremented the counter whenever a process started running and verified the final count in the output

**Time spent**:
1h 25min
---

### Entry 5 - [October 9,2026, 7 PM]
**What I did**:
Implemented Feature 3

**Details**:
1. I added waiting time
2. Turnaround time calculations using (System.currentTimeMillis())
3. Created a summary final table showing the process name, burst time, waiting time, and turnaround time(Waiting+ Burst)
   
**Challenges**:
I faced several compilation errors while formatting the summary table

**Solution**:
I debugged the code, corrected the syntax errors, and verified that the summary table was displayed correctly at the end of execution

**Time spent**:
2 hours
---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [ 6 hours]

**Most challenging part**: Implementing the waiting time tracking feature and debugging compilation errors

**Most interesting learning**: Understanding how Round-Robin scheduling works with Java threads

**What I would do differently next time**: I would start earlier and test each feature immediately after implementing it

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

During this assignment, I learned how Java threads can be used to simulate process execution. I learned how a class can implement the Runnable interface and then run inside a Thread object. I understood how Thread.start() begins the execution of a process and how Thread.join() makes the scheduler wait until the current process finishes its execution before continuing. I also learned how Thread.sleep() is used to simulate process execution time. By running the scheduler simulation, I observed how processes share CPU time using the Round-Robin algorithm. This assignment helped me understand how multithreading works in a practical way rather than only studying the theory

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

The most challenging part of this assignment was implementing the waiting time tracking feature. It was difficult because I had to understand where and how the waiting time should be calculated in the existing scheduler code. I also needed to add new variables and display the results correctly in the summary table. During implementation, I encountered several compilation errors that required debugging and testing. Finding the correct locations to add the new code was sometimes confusing. After carefully reviewing the program structure and testing my changes, I was able to complete the feature successfully 

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

I overcame the challenges by working step by step and testing the program after every small change. I carefully re-read the README whenever I was unsure about a requirement. When I encountered errors, I used debugging techniques and checked the output to identify the source of the problem. I also reviewed the code multiple times to understand how the scheduler and processes worked together. Testing each feature separately helped me find mistakes early and fix them more easily. This method made the assignment more manageable and improved my understanding of the code

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

Multithreading can be applied in many real-world applications. For example, a web browser uses multiple threads to load web pages, play videos, and respond to user actions at the same time. Mobile applications also use threads so that the user interface remains responsive while data is being downloaded in the background. Online games use multithreading to handle graphics, player input, and network communication simultaneously. A music player can use one thread to play audio while another thread manages the user interface. Similar to this assignment, multiple tasks share CPU time and execute efficiently without preventing other tasks from running.

### Optional: What would you like to learn more about?

I would like to learn more about advanced multithreading and thread synchronization in Java

### Optional: How confident do you feel about multithreading concepts now?

I would consider myself at an intermediate level because I understand the basics of threads and scheduling, but I still need more practice with advanced multithreading concepts 

### Optional: Feedback on the assignment

The assignment was helpful because it improved my understanding of multithreading and CPU scheduling. It was challenging at first, but I learned a lot while working on it 

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

A process is an independent program, while a thread is a smaller unit that runs inside a process. In this assignment, the Process class represents a simulated process, but it is executed by a real Java thread using new Thread(process) in addProcessToQueue(). Threads share memory and have lower creation overhead than processes, which is why threads were used to simulate CPU scheduling in this project


## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

In Round-Robin scheduling, if a process does not finish within its assigned time quantum, it is returned to the end of the ready queue and waits for another CPU turn. In my program output, process P3 did not finish after its first quantum of 2000ms because it still had 757ms remaining. As a result, P3 was re-queued 1 time before it finally completed execution. This re-queueing mechanism is important because it allows all processes to receive CPU time fairly instead of allowing one process to monopolize the CPU. It improves fairness and responsiveness in the scheduling system

Example from my output:
```
P3 executing quantum [2000ms]
P3 completed quantum 2000ms
Remaining time: 757ms
P3 yields CPU for context switch

P3 added to ready queue | Burst time: 4757ms | Priority: 8

```

**Explanation of example:**
The output shows that P3 could not finish during its first time quantum. Since it still had 757ms remaining, it yielded the CPU and was added back to the ready queue. After waiting for another turn, P3 executed again and completed its remaining execution time.
( P3 be in the ready queued one time )
## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: P1 was in the New state when its Thread object was created in addProcessToQueue() before start() was called

2. **Runnable**: P1 became Runnable when the scheduler selected it and called Thread.start() 

3. **Running**: P1 entered the Running state when its run() method began executing and it started using CPU time.

4. **Waiting**: While P1 was executing, Thread.sleep() temporarily paused its thread. The main thread also entered a waiting state when join() was used to wait for P1 to finish

5. **Terminated**: P1 reached the Terminated state after run() completed and its remainingTime became 0, meaning the process had finished execution

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): Running Multiple Programs on a Computer

**Description**:
When I use my computer, I often have several programs open at the same time, such as a browser, a music app, and a document editor. All of these programs need CPU time to continue working smoothly. The operating system schedules them and gives each one a small amount of time to run before moving to the next program

**Why Round-Robin works well here**:
Round-Robin works well because it gives every program a fair chance to use the CPU. This keeps the computer responsive and prevents one program from blocking the others. In this situation, each running program acts like a process, the CPU time given to it is the time quantum, and moving the CPU from one program to another is a context switch

### Example 2: Online Game Server
**Description**:
In an online multiplayer game, many players send actions and requests to the server at the same time. The server needs to handle all of them quickly so that the game feels smooth and responsive. Different threads can be used to process these requests

**Why Round-Robin works well here**:
Round-Robin helps make sure that no player's requests are ignored for too long. Each thread gets a chance to run, which improves fairness and keeps the game responsive for everyone. In this example, player requests act like processes, the processing time given to each request is the time quantum, and switching between request-handling threads is the context switch

## Summary

**Key concepts I understood through these questions:**

1. How Round-Robin scheduling shares CPU time fairly between processes
2. The thread lifecycle and the role of start(), sleep(), and join()
3. How context switches and the ready queue affect process execution

**Concepts I need to study more:**

1. Advanced thread synchronization techniques
2. Different CPU scheduling algorithms and their performance


---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
