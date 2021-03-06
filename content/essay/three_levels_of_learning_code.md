Title: 学习开源代码的三个层次
Date: 2015-01-16 23:20
Modified: 2015-01-16 23:20
Tags: thought
Slug: three-levels-of-learning-code
Authors: Joey Huang
Summary: 网络上有很多优秀的开源代码，学习这些代码是提高自己编程水平的最佳途径。

网络上有很多优秀的开源代码，学习这些代码是提高自己编程水平的最佳途径。我们在实际项目开发的过程中也会使用很多优秀的开源代码来加快开发速度，避免重复造轮子。优秀开源代码至少可以给我们提供三个层次的学习资料。

**第一层次：使用开源代码**
这一步相对简单，也是大部分人在项目开发过程中最常用的方式。优秀的开源代码一般文档齐全，示例代码丰富。通过简单地学习这些资料，可以较容易地掌握开源代码的用法。

**第二层次：阅读开源代码，理解其实现原理**
做到这一步的人就比较少了。这一步需要花很多时间，而且还需要一些必要的基础知识储备。但如果能达到这个层次，能掌握的技能也会比较多，不单单是开源代码本身的核心逻辑及其架构设计，还能掌握软件开发过程中的一些最佳实践法则。比如单元测试，利用[travis](https://travis-ci.org)进行自动编译测试等等。

**第三个层次：吸收并应用开源代码的设计理念到自己的软件开发过程中去**
看得懂和懂得灵活应用是两个层次的东西。从看得懂到会灵活应用中间还需要大量的时间去思考，去实践。面试过不少人，讲起来头头是道，真要让他写出来时，却卡壳了。要么类名方法名忘记了（IDE惹的祸），要么写出来的完全变味。要真正掌握一个技能，除了多看，还要多写，更要多总结，多思考。大道至简，总结多了，无非都是那些模式。面向测试的编程，面向对象编程，设计模式，函数式编程，宏等等这些抽象的概念，通过一些优秀的开源代码去总结思考，才能真正地理解这些抽象概念，最终把这些设计理念应用到自己的代码中去。

**今日推荐**

今天推荐一个Android开源库[EventBus][1]。
> EventBus is publish/subscribe event bus optimized for Android.

1. 它和Android的广播通信方式有什么区别？
2. 它和另外一个开源库[Otto][2]有什么区别？

答案都在其官方文档里。关于这个库，还有两个很好的学习资源：

1. [event-bus-demo][3]
   这是一个DEMO程序。
2. [EventBus 源码解析][4]
   这个分析了其原理和实现。
   
网络上的那些XXX源码解析，XXX源码情景分析之类的文章质量还是比较高的，但这些文档不能代替对源码的阅读。这些文档的作用是帮助初学者更好的理解源码，降低学习成本。需要深刻理解设计精髓，还是需要通过阅读源码去深刻领会。阅读一些设计优秀的源码和青春期时阅读汪国真的蒙珑诗一样美。与其走马观花，不如花一些时间深入去学习几个开源代码，自己偿试通过阅读代码总结出其架构和设计的精髓。通过这样的训练，几个月后就会发现编程水平会有长足的进步。

[1]: https://github.com/greenrobot/EventBus
[2]: https://github.com/square/otto
[3]: https://github.com/android-cn/android-open-project-demo/tree/master/event-bus-demo
[4]: https://github.com/android-cn/android-open-project-analysis/tree/master/event-bus
 																																																																
