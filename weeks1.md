### 4.1~4.7
---
#### Algorithm
<a href="https://leetcode-cn.com/problems/jewels-and-stones/">宝石与石头</a>：
<a href="https://github.com/darkmanno6/JavaStudy/blob/master/src/main/java/com/darkman/leetcode/NumJewelsInStones.java">解</a>

#### Review
最近看了设计模式之一的模板方法模式，整理如下：
模板方法：定义了算法的步骤，把这些步骤的实现延迟到子类。
模板方法模式：在一个方法中定义一个算法的骨架，而将一些步骤延迟到子类中。模板方法使得子类再不改变算法结构的情况下，重新定义算法中的某些步骤。
模板方法模式的使用：创建一个父类抽象类，将部分逻辑以具体方法以及具体构造函数的形式实现，然后声明一些抽象方法来让子类实现剩余的逻辑。不同的子类可以以不同的方式实现这些抽象方法，从而对剩余的逻辑有不同的实现。


#### Tip
最近测试过程中经常发现多条目的计算问题，往往多条目的循环计算问题出现较多，以后测试过程中要注意多条目case的覆盖；

#### Share


