## Java设计模式
观察者模式
* 也称发布／订阅模式<br>
* 观察者模式定义了对象之间一对多的关系<br>
* 主题（也就是可观察者）用一个共同的接口来更新观察者<br>
* **观察者**与**可观察者**之间用松耦合方式结合，**可观察者**不知道观察者的细节，只知道**观察者**实现了观察者接口<br>
```
观察者（observer）通过向主题（subject）订阅，一旦主题（subject）发布新消息，就通知相关订阅者的过程
```
UML<br>
![GitHub set up](https://github.com/DarrenChen138/Yogeyiis/blob/master/Observer.png?raw=true)
