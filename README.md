# DesignPatternsDemo
23种设计模式的DEMO分享（持续更新）

开发工具：
Visual Studio Code (官网：https://code.visualstudio.com/)

<br>

## 什么是设计模式？

通俗来讲，设计模式就是针对某一种特殊场景而给出的标准解决方案，它是前辈们的经验性总结，也是实现软件工程化的基础，良好的设计模式应用 可以是我们的软件变得更加健壮可维护。

设计模式按照类型划分可以分为三大类，如下所示：

创建型设计模式：如同它的名字那样，它是用来解耦对象的实例化过程。<br>
结构型设计模式：将类和对象按照一定规则组合成一个更加强大的结构体。<br>
行为型设计模式：定义类和对象的交互行为。


<br>

# 目录
- 创建型设计模式
    - [单例模式](./SingletonPattern/README.md)&nbsp;&nbsp;(某个类只有一个实例，提供一个全局访问点)
    - 建造者模式&nbsp;&nbsp;(封装一个复杂对象的构建过程,按照步骤构造对象)
    - 原型模式&nbsp;&nbsp;(通过复制现有的实例来构建新的实例)
    - 简单工厂模式&nbsp;&nbsp;(一个工厂类根据传入的参数决定创建哪一种产品类的实例)
    - 工厂模式&nbsp;&nbsp;(定义一个创建对象的接口，让子类决定实例化哪个类)
    - 抽象工厂模式&nbsp;&nbsp;(创建相关依赖对象的家族，而无需指定具体类。)  

- 结构型设计模式
    - 适配器模式&nbsp;&nbsp;(将一个类的方法或者接口转换成客户希望的另一个接口)
    - 组合模式&nbsp;&nbsp;(将对象组合成树形结构以表示整体和部分的层次结构)
    - 装饰模式 &nbsp;&nbsp;(动态的给对象添加新的功能) 
    - 外观模式&nbsp;&nbsp;(对外提供一个统-的方法，用来访问子系统中的一群接口)
    - 桥接模式&nbsp;&nbsp;(将抽象部分和它的实现部分相互分离，是它们都可以独立变化)
    - 享元模式&nbsp;&nbsp;(通过共享技术来有效的支持大量细粒度的对象)
    - 代理模式&nbsp;&nbsp;(为其他对象提供一个代理以便可以控制这个对象的访问)    

- 行为型设计模式
    - 模板模式&nbsp;&nbsp;(定义一个算法结构，而将-些步骤延迟到子类实现)
    - 解释器模式  &nbsp;&nbsp;(给定一个语音，定义它的文法的一种表示，并定义一个解释器)
    - 策略模式&nbsp;&nbsp;(定义一系列算法，把他们封装起来，并且使他们可以互相替换)
    - 状态模式&nbsp;&nbsp;(允许一个对象在其内部对象状态改变时改变它的行为)
    - 观察者模式&nbsp;&nbsp;(对象间一对多 的依赖关系)
    - 备忘录模式&nbsp;&nbsp;(在不破坏封装的前提下，保持对象的内部状态)
    - 中介者模式&nbsp;&nbsp;(用一个中介对象来封装一系列对象的交互)
    - 命令模式&nbsp;&nbsp;(将命令请求封装称为一个对象，可以将不同的请求来进行参数化)
    - 访问者模式&nbsp;&nbsp;(在不改变数据结构的前提下，增加作用于-组对象元素的新功能 
    - 责任链模式&nbsp;&nbsp;(将请求的发送者和接受者解耦， 使得多个对象都有处理这个请求的机会)
    - 迭代器模式&nbsp;&nbsp;(一种遍历访问聚合对象各个元素的方法，不暴露给对象的内部结构)



