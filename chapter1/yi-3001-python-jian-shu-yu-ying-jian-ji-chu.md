本章主要讲述python的一些常识：python的软件配置、硬件需求、以及开发应用场景等。

# 1.1 python简介

python由吉多·范罗苏姆（Guido van Rossum）在1989年创造。社区都称创始人为龟叔。1989年，鬼叔z爱阿姆斯特丹为了打发圣诞节的无趣生活，开发了一个新的脚本解释程序，这便是python。

## 1.1.1python的定义

对于众多的计算机语言，根据其特点和语法本身侧重点的不同，一般会有不同的分类和叫法。python作为计算机语言一般会被定义为四种语言：1、脚本语言，2、解释性语言，3、高级语言，4、面向对象的语言。

### 1、脚本语言

脚本：script。脚本就像电影的剧本一样，剧本决定了电影中的人和物的发展以及具体事务过程；计算机脚本决定了计算机上电后硬件初始化驱动、操作系统初始化加载以及接下来各种软件程序要做什么事，以及何时做。例如，Windows里的命令行文件或者.bat批处理文件等、linux的shell脚本等通过一个普通文本文件，并添加脚本命令或者代码并保存，就可以在有相关环境的操作系统中运行执行相应的操作了。一般脚本语言经过编译后就可以执行了。

**编译型语言和脚本语言**

**编译型语言：**就是用此语言将程序源代码编译成可执行程序（机器语言），然后就可以运行了。一般均通过编译语言将源代码和相应的库打包链接编译为最终的可执行文件。这种语言一般执行效率高（直接运行可执行程序）、依赖编译器、跨平台性能差些，如C、C++、Delphi等。

```
源代码->编译器编译为可执行程序->运行程序
```

**脚本语言：**脚本语言不需要编译器编译源代码，可以直接在操作系统的命令行中运行，当前环境本身就是此脚本的解释器。

```
源代码->直接运行
```

### 2、解释型语言

相对于脚本语言直接在操作环境中读一行解释一行执行一行，解释型语言一般需要专门的解释器来执行。每个语句也是在执行的时候才翻译为机器语言，依赖解释器，效率较低，但跨平台性能好。如java、python等。

### 3、高级语言

高级语言相对于机器语言，是一种指令集的体系；不需要对硬件知识了解太多；是高度封装了的编程语言；并以人类日常语言为基础、并便于接收的文字\(英语\)来表示，具有较高的程序可读性。如Fortran、C、C++、JAVA、python等。

之所以称为高级语言，是因为刚开始发展的程序语言，如汇编语言，涉及太多物理层面上和硬件上的实现细节，不利于一般人去理解和学习并掌握，属于低级语言。20世纪80年代，东亚地区曾掀起一股常数开发用各自地方语言编写的高级语言，主要是改变BASIC或专用于数据库数据访问的语言，但随着编程人员的英语水平提高，现在有关开发很少。

### 4、面向对象语言

目前主要使用的高级程序语言分两种：面向过程语言和面向对象语言。

**面向过程语言：**在早期的单片机开发中，由于存储极小（几K大小），一般只能实现很少的功能。因此一般均是源码顺序执行（顶多也就是中断）。由于程序量较小，所以不需抽象实际物理参数，即可编写并实现功能调用等。这种一般只有函数调用数据形式的处理程序属于面向过程语言。当需要修改时，一般需要寻找并修改一大堆数据，易于出错，非常不利于系统复杂化。后来随着硬件的发展，在单片机及嵌入式开发中，由于存储不再是瓶颈，大量的功能集成，需要运用面向对象语言来编写以实现各自复杂的实际实例。如C51等。

**面向对象语言：**是指在语言设计时，语言本身的基本元素是以对象的方式设计的，而不同的对象之间的交互则成为整个程序运行的主要表现形式。以万物皆对象的思路将现实中的物体、概念、逻辑的整体等内容实现与语言元素意义对应。由于程序员用此方式设计程序时更直观和理解，更易建华处理逻辑，因此降低了用语言解决实际问题的负责度，提高了处理事情的效率。

Python语言也是基于对象的，属于面向对象的编程语言。

**“面向对象”的解释：**  
现实世界中任何事物都具有自己的属性或能力，比如一种桌子有长宽高、材质、颜色等属性；但它没有生命，没有自己移动的能力。一只狗有年龄、颜色、体重等属性；也有生命，有自己走路、叫唤的能力。

那么，在程序中，我们可以模仿现实世界，并对其进行有目的的抽象：将实际事物在我们设计时有用的属性和能力抽象出来并建立一个关联的模型。对现实世界中事物不论属性或能力的，而程序需要的，可以直接在程序中添加；对现实世界中事物具有属性或者能力的，但程序不需要的，在程序中不进行表达。这种抽象出来的模型就叫做对象或类。例如，上文中的桌子可以是一个类对象；若是小明家的桌子则可以是一个属于桌子类的实例对象。

# 1.2 python的软件知识

本节分三部分进行说明：python语言自身的软件版本、开发中经常用到的IDE和程序员需要用到的一些小工具基础。

# 1.3python的硬件知识


