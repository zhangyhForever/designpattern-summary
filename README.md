# 设计模式总结和对比
## 工厂模式：
#### 将对象的创建工作交给工厂类来完成，屏蔽掉对象具体的创建方式。
## 单例模式：
#### 某个类在整个系统当中只存在一个实例，所有的引用都指向这一个实例。
## 原型模式：
#### 通过复制已有对象来完成该类型新对象的创建工作。
## 代理模式：
#### 在不改变原有类的基础上，通过持有该类的引用对该类的功能进行拓展和增强。
## 模板模式：
#### 抽象父类定义执行的流程和方法，子类重写父类方法完成自己特有的功能，但不	改变程序执行的流程。
## 委派模式：
#### B类持有其他类的方法，A类不与其他类关联，而通过B类来调用其他类的方法
## 策略模式：
#### 在程序运行过程中，针对不同的行为采取与之对应的方法来响应
## 装饰模式：
#### 在不改变原有类的基础上，动态的对原有类的功能进行拓展。
## 观察者模式：
#### 被观察的对象发生行为的同时观察的对象发生相应的行为
## 适配器模式：
#### 适配类继承原有类保留原功能，实现新接口满足新需求
## Spring AOP代码片段
#### @Poincut("@annotation(com.zicms.common.spring.annotation.log)")
#### @Pointcut("execution(* com.zicms.web..*service.*(..)")
#### @AfterReturning(value="accessAspect()", returning="rtv")
#### @AfterThrowing(value="throwingAspect()",throwing="e")
## IOC代码片段
#### @Controller  @Service  @Component
## DI代码片段
#### @Resource  @Autowired
