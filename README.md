# Java-Experiment4
**Java课程作业项目仓库**
## 实验目的
* 掌握字符串String及其方法的使用；  
* 掌握文件的读取/写入方法；  
* 掌握异常处理结构；  
## 实验内容
### 说明
***在某课上，学生要提交实验结果，该结果存储在一个文本文件A中。***  
    `文件A包括两部分内容：    
        一是学生的基本信息；    
        二是学生处理后的作业信息；`    
>该作业的业务逻辑内容是：  
>利用已学的字符串处理知识编程完成《长恨歌》古诗的整理对齐工作，写出功能方法，实现以下功能；  
### 功能
>>* 每7个汉字加入一个标点符号，奇数时加“，”，偶数时加“。”；  
>>* 允许提供输入参数，统计古诗中某个字或词出现的次数；  
>>* 输入的文本来源于文本文件B读取，把处理好的结果写入到文本文件A；  
>>* 考虑操作中可能出现的异常，在程序中设计异常处理程序；  
## 实验要求
⚪设计学生类（***可利用之前的***）；  
⚪采用交互式方式实例化某学生；  
⚪设计程序完成上述的业务逻辑处理，并且把“***古诗处理后的输出***”结果存储到学生基本信息所在的***文本文件A***中；  
## 实验过程
>* TextHandling接口（*文本处理*）声明文本处理（*Deal*）的抽象方法；
>* TextStatistics接口（*词频统计*）声明词频统计（*Count*）的抽象方法；
>* Person类下定义三个基本属性（*Age、Name、Sex*），利用Scanner类交互式输入为属性赋值;
>* Student类继承Person类，获得父类属性；
>* TextB类下定义两个基本属性（*content、word*），便于文本处理及词频统计两接口的方法使用；
>* TextA类下定义学生属性（*student*）与传递学生信息的构造方法（*TextA （Student st）*），重写toString方法，将学生信息在文本A中呈现，同时将TextHandling、TextStatistics两接口的抽象方法实现;
## 核心代码
## 系统运行截图
![image](https://github.com/daladida/Java-Experiment4/blob/main/images/%E5%AE%9E%E9%AA%8C%EF%BC%88%E5%9B%9B%EF%BC%89%E8%BF%90%E8%A1%8C%E7%BB%93%E6%9E%9C.png)
![image](https://github.com/daladida/Java-Experiment4/blob/main/images/%E7%A8%8B%E5%BA%8F%E8%BF%90%E8%A1%8C%E6%95%88%E6%9E%9C.png)
## 实验感想
