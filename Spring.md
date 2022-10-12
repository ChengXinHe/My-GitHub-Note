#1.1

* **IOC**
  >inversion of control
  >由外部创捷对象，而非程序内部创建（目的：解耦）
  >IoC  创建的对象叫bean
    >**dependence injection**
    在IoC容器中绑定bean 和 bean之间的关系

    利用反射，可以用私有的构造方法构造对象。构造bean使用的是无参的构造函数。

    如果没有提供无参的构造方法，将报 beanCreationExceptions

  >如何创建bean：
  可以使用1.构造方法 2.静态工厂 3.实例工厂4.使用factorybean实例化
  创建的bean都是单例对象
  >如何销毁bean：在配置中设置init 和 destory  
  或者使用接口：InitializingBean 和DisposalBean。Init发生在PropertiesSet之后
  >如何关闭容器：设置钩子 registerShutDownHook
  或者close
