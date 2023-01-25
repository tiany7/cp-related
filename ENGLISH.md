# Competitive Programming related issues (continuously updated)

I sorted out some of the questions you had just now and put them here. If you have any questions, you can go to the document to find them first. If you don’t have any, you can ask questions in the group or chat with TA privately.

- [ ] [codeforces related]
- [ ] [Language-related issues]
- [ ] [Online Judge related]
- [ ] [TA-related issues]

## Syllabus related questions
This suggestion is to consult syllabus, go to discord or ed (will be opened later) to ask, so that more students can see that everyone may have the same problem.

## Codeforces related issues

### 1. Which contests count as live contests?

Everyone click into [cf](www.codeforces.com)

![image](https://user-images.githubusercontent.com/46698520/214207788-3d117f5d-d331-46d8-9580-37bfa2a37e0f.png)

In the contest tab, you can see that there are many upcoming contests at the top.

![image](https://user-images.githubusercontent.com/46698520/214207912-7459293d-6172-44b3-addf-2d8c0de0be3a.png)

These competitions with the label of div X are all considered as live contests, where X is the difficulty of the competition, the higher the level, the easier it is. Everyone can choose the contest according to their own level.

The recommended ones are div2 and div3. The title of div3 is much simpler than that of div2. If you think div2 is too difficult, you can go to div3 to practice first.

### 2. How to calculate live?

Each contest has a contest time written in the above picture, and the general div2 is about 2-2.5 hours. **Only if you participate in the contest within the marked time will it be counted as live! **

After the contest, you can click on virtual participation. This is a simulation of past contests. It will replay the situation and results submitted by the contestants at that time. The simulation is really a contest.

This is not a live contest, but it is a good contact tool for students who want to improve.

### 3. Where to look at the score that Professor Lim said

Each question will have a problem tag, and there will be a score tag after the contest, which means that about 50% of the people in this segment have solved it. The score is calculated according to this tag

![image](https://user-images.githubusercontent.com/46698520/214210016-69ffc500-6150-4d45-9f6d-9bc290c2404b.png)

1-2 days after each competition ends, the problem tag will be updated to the title, and the title will be added to the gym

### 4. What is the rating?
Rating is the score of cf, the initial score is 0, there will be a bonus point in the first 6 contests, and the score will be scored normally in the subsequent contests

Each question made has an initial score, which decreases over time, and each error after test case 2 will have a penalty, which will be subtracted from the final score

The difficulty of the questions in cf generally increases gradually from A to F, but there is no guarantee that this is the case, so everyone should pay attention when doing the questions.

There will be a change in rating after 1-2 days after each competition. This is calculated based on your score + the relative position of other people's scores. You can check your own rating change.

Score calculation is very metaphysical. You can download carrot in the chrome plug-in market. This plug-in can help you calculate the approximate score during the contest.

The names of different rating handles will have different colors


### 5. Do I have to participate after signing up?
Don't submit, it won't be counted. Once submitted, it will be added to the scoring queue. If you don't want to participate in the competition, be careful not to submit!

### 6. Can I do cf in a group of three?

No, the cf competition is an individual competition, and discussion and communication are prohibited. If someone is found to communicate or copy other people's answers, cf will be punished with 0 points for the contest on the spot - the punishment varies from title to title. It is also forbidden to exchange codes during the contest in the group.

Doing questions by multiple people will not help everyone to improve, and everyone can discuss after the contest.

### 7. Can I view other people's code in the competition?
Same as above, if it is found, it will be processed with 0 points.

### 8. Can I check other people's code after the competition?

Go to standing and click on the problem score, and you can see other people's codes in it. You can learn how the big guys write their codes.

![image](https://user-images.githubusercontent.com/46698520/214211163-573b3b02-91ab-4fbc-a64f-2b8990e7cda3.png)

![image](https://user-images.githubusercontent.com/46698520/214211232-17f3e60e-6776-4697-8b77-058a542c9448.png)

### 9. Where can I see the solution after the contest?

![image](https://user-images.githubusercontent.com/46698520/214211277-b2487c83-ebad-4a53-a8ba-7ad6acc7021f.png)

### 9. What should I do if I can’t solve the questions in cf and feel very painful?

This is normal for beginners, most people's rating will be below 1400, don't be discouraged. Slow practice always improves.

# language related

### Recommended language
First of all, in cp, we use more algorithms than languages. We will not use the spring framework in cp, nor will we use pytorch and C pointers, so don't get entangled in languages. In theory, all Both languages can be used as CP questions.

But in the actual competition, we still recommend everyone to use C++, because C++ is unshakable in cp so far in terms of expression, efficiency, running time, and memory usage.

Recommended order

C++ >>>>>>>> Python >>> Java > Other languages

### Why is C++ recommended?

Advantages of C++

- Fast speed and low memory usage
- Small amount of code, strong readability
- Support overloading, template, STL, convenient and fast
- There are many excellent libraries that can be used directly
- All cp topics are basically written with cpp by default, and all ojs support cpp
- Most of the online competition solutions are written by cpp
- Can play tricks

### Python


So what are the advantages of python?

- Simple grammar and strong expressive ability
- Short code and high readability
- python does not limit the size of int, it can be directly used for large number operations

shortcoming:

- Interpretive languages are relatively slow, and the speed difference between python and C++ is about 10 times
- Some questions have the same algorithm, and it will time out when written in python, but not in C++
- For some topics, C++ has some excellent data structures, such as set and map, but python does not, so writing some topics in python will be very troublesome
- The memory usage of python is much larger than that of C++, so in the problem with relatively small memory limit, python will exceed the memory

### Java

There are many students who use java, yes, but I really don't recommend everyone to use java, because java has no obvious advantage over python. On the contrary, there are many disadvantages

shortcoming:
- The amount of code is huge, and it is very laborious to write
- Slow speed, large memory usage, few questions specifically consider java, there will be an algorithm, writing in java will time out, but neither in C++ nor python
- Special processing of input and output is required, otherwise it is very easy to TLE
- not supported by many ojs

Here we will only use process-oriented features, so the cost of switching to cpp is very small.


## Input and output processing

### 1. What is input and output?

Input and output refer to the way a program interacts with the outside world. For example, when we type on a computer, this process is input, and the words we see are output. In the program, the input and output are the same. We let the program read the data through the input, and then let the program output the data to the screen through the output.

All data in the contest will be input into the program through stdin, and then the program will output the result to stdout, so that the correctness of the program can be judged through oj.

### 2. Why do we need to process input and output?

Some languages have some defects in the way of obtaining input, so we have to deal with the input and output methods to reduce the time consumption on input and output.

### C++

The input and output methods of C++ are cin and cout. The disadvantages of these two functions are: because of the historical legacy of C, cin and cout share a buffer with scanf and printf, so there will be a huge time consumption during input and output. .

Regarding this problem, we can solve it by turning off synchronization, you just need to add a line before the code starts

```cpp
ios::sync_with_stdio(false);
cin.tie(0);
cout.tie(nullptr);
```

In addition, every time endl is used, the buffer will be refreshed, so we can use '\n' instead of endl, which can reduce a lot of time consumption.

### Java

Java's native input and output methods are Scanner and System.out.println. The disadvantage of these two functions is: due to design reasons, they are inherently slow and require special processing of input and output, otherwise most problems cannot be passed.

I suggest you refer to [This article](https://blog.csdn.net/m0_50917429/article/details/123610348?spm=1001.2101.3001.6661.1&utm_medium=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1-123610348-blog-127570434.pc_relevant_aa2&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1-123610348-blog-127570434.pc_relevant_aa2&utm_relevant_index=1)

In terms of efficiency, buffered reader is slower than stream tokenizer

** Again, language is not the focus of this lesson, don't get entangled! ! **

# Online Judge related questions
Under the ICPC competition system, there are 9-13 algorithm problems in each game, and you need to solve some problems. Each problem has a time limit and a space limit. You need to use as little space as possible to solve the problem within the specified time . These questions will be submitted to oj, and oj will judge whether your code is correct based on your code. If it is correct, you can get a certain score.
If you make a mistake, you will have a penalty time. When sorting, you will sort according to the penalty time. For the same number of questions, the less penalty time, the higher the ranking.

### Wrong Answer (WA)
If the result output by your code is different from the result on oj, Wrong Answer will appear. In this case, you need to check your code carefully to see if there is something wrong.

Common problems are:
1. Algorithm error
2. Debug traces are not deleted
3. The 32-bit int exploded during the calculation

### Time Limit Exceeded (TLE)
If the running time of your code exceeds the time limit of the topic, Time Limit Exceeded will appear. In this case, you need to check your code carefully to see if there is something wrong.

Generally speaking, this is because the complexity of your algorithm is not good enough, and the calculation is repeated too many times, resulting in too long running time.

But the probabilistic complexity is correct, but because the constant is too large, it is necessary to consider optimizing the writing method at this time, such as using an array instead of map, using scanf instead of cin, using printf instead of cout, and so on.

The calculations that a machine can do in 1 second are about 1e7-1e8 times. You can know the approximate complexity according to the range of input data.

corresponding form

| Data Range | Complexity |
| --- | --- |
| 100-500 |O(n^3) |
| 500-1000 |O(n^2) |
| 1e5 | O(n) |
| 1e6 | O(n or nlgn) |
| 1e7 | O(n) |
| 1e8 - 1e18 | O(1) or O(lgn) |


### Memory Limit Exceeded (RE)
If your code running space exceeds the space limit of the topic, Memory Limit Exceeded will appear.

### Runtime Error (RE)
If there is a runtime error in your code, a Runtime Error will appear. In this case, you need to carefully check your code to see if there is something wrong.

Common problems are:
- divisor is 0
- array out of bounds
- Too many layers of recursion
- burst 32-bit int

### Accepted (AC)
If your code runs correctly, Accepted will appear, congratulations, your code has passed all the test cases.

### What is Online Judge?
Online Judge, referred to as OJ, is an online evaluation system that can be used to evaluate the correctness of programs, generally used to evaluate the running time and running space of programs.

Common OJs are:
- [Codeforces] (codeforces.com)
- [Codechef](codechef.com)
- [AtCoder] (atcoder.jp)
- [TopCoder](topcoder.com)
- [LeetCode](leetcode.com)
- [vjudge](vjudge.net) (you can find most oj entries here)

# TA related

If you have any questions, you can ask them in the group. There are several experienced students in the group, and everyone will try their best to answer every question.

You can also go to the office hour to ask questions. I recommend everyone to listen to the office hour lecture on code implementation by our classmate Andrei Coman
