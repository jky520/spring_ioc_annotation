# spring的IOC基于annotation方式
	该java项目主要是帮助我们快速的掌握springd的IOC基于annotation的实现方式，IOC（控制反转）也称为DI（依赖注入），IOC:Inversion of Control控制反转，也叫（Dependency Injection）依赖注入，dao接口的实现不再是业务逻辑层调用工厂类去获取，而是通过容器（spring）来自动的为我们的业务层设置Dao的实现类，这样整个过程就反过来，以前是我们业务层主动去获取dao，而现在是dao主动被设置到业务逻辑层中来了，这个也就是反转控制的由来。通过IOC，我们就可以在不修改任何代码的情况下，无缝地实现数据库的换库迁移。

# 简单一点说：
	IOC就是一个生产和管理bean的容器就行了，原来需要在调用类中new的东西，现在都是通过容器生成，同时，要是产生的是单例的bean，他还可以给管理bean的生命周期。
	