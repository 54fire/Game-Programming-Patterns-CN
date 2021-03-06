解耦模式
============================

当你掌握了一门编程语言，你会发现写代码来实现某个你想要实现的功能是件相当容易的事情。难的是编写能够容易应对需求*变更*的代码。因为我们几乎没有可能不更改程序的功能或者特性。

我们有一个能让变化变得简单点的强大的工具--*解耦*。当我们提到两块代码是”解耦“时，我们的意思是一块代码中的变化通常不会影响到另一块代码。当你在更改游戏的一些功能时，代码更改的地方越少就会越简单。

[组件](05.1-Component.md)将游戏的不同方面互相分离开却仍然具备它们的特性。[事件队列](05.2-Event Queue.md)能够静态而且及时的将两个对象通信分离开。[服务定位器](05.3-Service Locator.md)让代码能够访问到设备却不需要被绑定到提供服务的代码上。

## 本章模式

* [组件](05.1-Component.md)
* [事件队列](05.2-Event Queue.md)
* [服务定位器](05.3-Service Locator.md)