# es6 语法学习 - 设计模式

设计模式（Design Pattern）是一种在软件工程中被反复使用的、经过验证的解决方案，它提供了一些通用的、可复用的设计思路，以应对在软件开发中常见的问题。

### 一. 设计模式的目的

- **提高可复用性**：通过使用设计模式，可以创建更具可复用性的代码，因为设计模式通常被抽象为一套通用的解决方案。
- **增强可维护性**：设计模式提供清晰的结构和定义，使得代码更容易理解、修改和扩展。
- **便于沟通**：设计模式为开发者提供一种通用的语言，使得团队成员之间在讨论设计时能够更清晰、更高效地交流。
- **减少复杂性**：使用设计模式可以帮助简化设计，通过将复杂问题拆分成更小、更易管理的部分。

### 二. **设计原则 SOLID **

- **单一职责原则 (ingle Responsibility Principle, SRP)**：每个类应该只有一个职责，只有一个引起变更的原因。
- **开放-闭合原则 (Open/Closed Principle, OCP)**：对扩展开放，对修改关闭。
- **里氏替换原则 (Liskov Substitution Principle, LSP)**：子类对象应该可以替换父类对象而又不影响父类对象。
- **接口隔离原则 (Interface Segregation Principle, ISP)**：不应该强迫客户依赖于它们不使用的接口。
- **依赖倒置原则 (Dependence Inversion Principle, DIP)**：高层模块不应该依赖低层模块，二者都应该依赖于抽象。

### 三. 设计模式的分类

设计模式分为：创建型模式，结构型模式，行为型模式。

**1 创建型模式:** 关注如何实例化对象的过程，强调对象的创建过程

- 单例模式（Singleton）：确保某个类只有一个实例，并提供全局访问点。
- 工厂方法模式（Factory Method）：定义一个接口用于创建对象，但由子类决定实例化哪个类。
- 抽象工厂模式（Abstract Factory）：提供一个接口，用于创建一系列相关或相互依赖的对象，而无需指定具体类。
- 建造者模式（Builder）：将一个复杂对象的构建与它的表示分离，使同样的构建过程可以创建不同的表示。
- 原型模式（Prototype）：通过复制现有对象而不是实例化新的对象来创建对象。

**2 结构型模式:** 关注类或对象的组合，确保它们能够一起工作

- 适配器模式（Adapter）：将一个接口转换成客户端所期望的另一个接口，从而使原本不兼容的接口能够合作。
- 桥接模式（Bridge）：将抽象与实现分离，使它们可以独立变化。
- 组合模式（Composite）：将对象组合成树形结构以表示部分与整体的层次关系。
- 装饰器模式（Decorator）：动态地给对象添加额外的职责或行为。
- 外观模式（Facade）：为子系统中的一组接口提供一个一致的界面。
- 享元模式（Flyweight）：通过共享大量细粒度对象来提高性能。
- 代理模式（Proxy）：为其他对象提供一个代理以控制对这个对象的访问。

**3 行为型模式:** 关注对象之间的交互和职责分配

- 责任链模式（Chain of Responsibility）：将请求的发送者与接收者解耦，使多个对象有机会处理请求。
- 命令模式（Command）：将一个请求封装为一个对象，从而使您可以使用不同的请求、队列或日志请求，支持可撤销操作。
- 解释器模式（Interpreter）：定义一个语言的文法，并建立一个解释器来解释语言中的句子。
- 迭代器模式（Iterator）：提供一种方法访问集合对象中的元素，而无需暴露集合的内部表示。
- 中介者模式（Mediator）：通过一个中介者对象来降低多个对象和类之间的耦合。
- 备忘录模式（Memento）：在不暴露对象实现的情况下，捕获一个对象的内部状态，以后可以恢复这个状态。
- 观察者模式（Observer）：定义一种一对多的依赖关系，当一个对象状态改变时，所有依赖于它的对象都会得到通知并自动更新。
- 状态模式（State）：允许一个对象在其内部状态改变时改变它的行为。
- 策略模式（Strategy）：定义一系列算法，将每一个算法封装起来，并使它们可以互换。
- 模板方法模式（Template Method）：定义一个算法的骨架，而将一些步骤延迟到子类中。
- 访问者模式（Visitor）：表示一个作用于某对象结构中的各元素的操作。

这 23 种设计模式为软件开发提供了通用的解决方案和最佳实践，有助于建立可重用和可维护的代码结构。
