# Competitive Programming 相关问题（持续更新）
For English version, please click this [link](https://github.com/tiany7/cp-related/blob/main/ENGLISH.md)

我整理了刚才大家的一些问题，放到了这里。大家有问题可以先来文档找找，如果没有的话可以在群里提问或者私聊TA

- [ ] [codeforces相关](#如何在本地调试代码)
- [ ] [语言相关问题](#如何在本地调试代码)
- [ ] [TA 相关问题](#如何在本地调试代码)

## Syllabus相关的问题
这个建议查阅syllabus，去discord或者ed(后面会开)问，让更多的同学看到，大家可能也有一样的问题。

## Codeforces相关的问题

### 1. 有哪些contest算live contest？

大家点进[cf](www.codeforces.com)

![image](https://user-images.githubusercontent.com/46698520/214207788-3d117f5d-d331-46d8-9580-37bfa2a37e0f.png)

在contest的tab里面可以看到最上方有很多upcoming contest.

![image](https://user-images.githubusercontent.com/46698520/214207912-7459293d-6172-44b3-addf-2d8c0de0be3a.png)

这些比赛标签为div X 的都算live contest，X是比赛的难度，越高越简单。大家可以根据自己的水平选择比赛。

比较推荐的是div2和div3，div3的题目相对于div2要简单很多，如果觉得div2太难的同学可以先去div3练练手

### 2. 怎么算live？

每场比赛在上面这张图片里有写比赛时间，一般的div2大概是2-2.5小时，**只有在这个标记的时间内参加比赛才会算live！**

赛后大家可以点击virtual participation, 这个是模拟过去发生的比赛，会回放当时比赛选手提交的情况和结果，模拟真是比赛。

这个不算live contest，但是对想要提高的同学是一个很好的联系工具。

### 3. yongwham说的分数在哪里看

每道题都会有一个problem tag，赛后会有一个分数tag，这就意味着在这个分段大概有50%的人做出来了。是按照这个tag计算分数的

![image](https://user-images.githubusercontent.com/46698520/214210016-69ffc500-6150-4d45-9f6d-9bc290c2404b.png)

每次比赛结束1-2天之后，这个problem tag会被更新到题目里，题目会被加入到gym

### 4. rating是什么
rating是cf的分数，初始分数为0，前6场会有一个加分，之后的比赛正常计分

做出来的每道题都有一个初始分数，随着时间进行而降低，另外每次在test case 2之后的错误都会有一个penalty，这个penalty会在最后的分数里面减去

cf的题目难度一般是A-F难度逐渐递增，但是也不保证一定是这样，所以大家在做题的时候要注意。

每次比赛之后过1-2天会有一个rating的变化，这个是根据你的分数 + 别人的分数相对位置 来计算的，大家可以看看自己的rating变化。

分数计算很玄学，大家可以在chrome插件市场下载carrot，这个插件可以帮助大家比赛时计算大概的分数。

不同的rating handle的名字颜色会不一样


### 5. 报了名一定要参加吗
不要提交，就不会算分，一旦提交就会加入到算分队列里面去，如果你不想参加比赛，注意不要提交！

### 6. 我可以三个人一组做cf么？

不可以，cf的比赛是个人比赛，禁止讨论和交流，如果发现有人交流,复制别人答案，会被cf处以当场比赛按照0分处理-封号不等的处罚。群内也禁止在赛时交流代码。

多个人做题对于大家的提高没有任何帮助，大家可以在比赛结束后讨论。

### 7. 我可以在比赛中查看别人的代码么？
同上，如果发现是会0分处理的。

### 8. 我可以在比赛后查看别人的代码么？

到standing点击problem分数，里面可以看到别人的代码，大家可以学习一下大佬们的代码是如何写的。

![image](https://user-images.githubusercontent.com/46698520/214211163-573b3b02-91ab-4fbc-a64f-2b8990e7cda3.png)

![image](https://user-images.githubusercontent.com/46698520/214211232-17f3e60e-6776-4697-8b77-058a542c9448.png)

### 9. 哪里可以看到赛后题解

![image](https://user-images.githubusercontent.com/46698520/214211277-b2487c83-ebad-4a53-a8ba-7ad6acc7021f.png)

### 9. 我在cf做不出来题，感觉很痛苦怎么办？

这个对于入门的同学很正常，大部分人的rating会在1400以下，不要灰心。慢慢练总能有所提升的。

# 语言相关

### 推荐语言    
首先在cp里面，我们用到的更多的是算法，而不是语言，我们在cp里面不会用到spring框架，也不会用到pytorch和C的指针，所以大家不要纠结语言，理论上所有语言都可以做cp题目。

但是在实际的比赛中，我们还是推荐大家使用C++，因为C++无论在表达，效率，运行时间，还是内存占用上到目前为止在cp里面都是无可撼动的

推荐顺序

C++ >>>>>>>> Python >>> Java > 其他语言

### 为什么推荐C++？

C++的优点

- 速度快，内存占用少
- 代码量少，可读性强
- 支持重载，模板，STL，方便快捷
- 有很多优秀的库，可以直接使用
- cp所有题目基本都是默认了用cpp写标程的，所有oj都支持cpp
- 网上绝大部分竞赛题解都是cpp写的
- 能玩出花样

### Python


那么python的优点是什么呢？

- 语法简单，表达能力强
- 代码短，可读性强
- python没有限制int的大小，可以直接用来做大数运算

缺点：

- 阐释性语言速度相对慢，python和C++的速度相差10倍左右
- 有些题同样一份算法，用python写会超时，但是用C++就不会
- 有些题目C++有一些优秀的数据结构，比如set，map，但是python没有，所以有些题目用python写会很麻烦
- python的内存占用比C++大很多，所以在内存限制比较小的题目中，python会超内存

### Java

用java的同学比较多，可以，但是我这里真的不推荐大家用java，因为java相对于python没有明显优势。反而多了很多缺点

缺点：
- 代码量巨大，写起来非常费劲
- 速度慢，内存占用大，很少有题目专门考虑到java，会出现一份算法，用java写会超时，但是用C++和python都不会
- 需要特殊处理输入输出，不然非常容易TLE
- 不被很多oj支持

这里我们只会用到面向过程的feature，所以换用cpp成本很小。


## 输入输出处理

### 1. 什么是输入输出？

输入输出是指程序和外界交互的方式，比如我们在电脑上打字，这个过程就是输入，而我们看到的字就是输出。在程序中，输入输出也是一样的，我们通过输入，让程序读取数据，然后通过输出，让程序把数据输出到屏幕上。

比赛中所有数据会通过stdin的方式输入到程序中，然后程序会把结果输出到stdout中，这样就可以通过oj来判断程序的正确性。

### 2. 为什么要处理输入输出？

有些语言的获取输入的方式有一些缺陷，所以我们要处理输入输出方式，减少在输入输出上的时间消耗。

### C++

C++的输入输出方式是cin和cout，这两个函数的缺点是：因为C的历史遗留，cin和cout和scanf和printf共用了一个缓冲区，所以在输入输出的时候会有极大的时间消耗。

关于这个问题，我们可以通过关闭同步的方式来解决，你只要在代码开始前加入一行

```cpp
ios::sync_with_stdio(false);
cout.tie(nullptr);
```

另外每次使用endl的时候，都会刷新缓冲区，所以我们可以用'\n'来代替endl，这样可以减少很多时间消耗。

### Java

java原生的输入输出方式是Scanner和System.out.println，这两个函数的缺点是：因为设计原因，本来就很慢，需要特殊处理输入输出，不然大部分问题无法通过

建议大家参考[这篇文章](https://blog.csdn.net/m0_50917429/article/details/123610348?spm=1001.2101.3001.6661.1&utm_medium=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1-123610348-blog-127570434.pc_relevant_aa2&depth_1-utm_source=distribute.pc_relevant_t0.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1-123610348-blog-127570434.pc_relevant_aa2&utm_relevant_index=1) 来处理输入输出

效率上buffered reader比stream tokenizer要慢一点

**再次强调一下语言不是这节课的重点，不要纠结！！**

# TA相关

如果有不会的问题，可以在群里问，群内有好几位经验丰富的同学，大家会尽力解答每一个问题。

也可以去office hour来问问题，推荐大家去听听我们的Andrei Coman同学关于code implementation的office hour讲座





