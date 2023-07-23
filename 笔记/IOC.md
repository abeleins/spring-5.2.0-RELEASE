## IOC
1. BeanFactory.interface
``` 
BeanFactory-->getBean()  
    HierarchicalBeanFactory-->getParentBeanFactory() 双亲Ioc    
        ConfigurableBeanFactory-->setParentBeanFactory()设置双亲Ioc容器  
                                -->addBeanPostProcessor()配置Bean后置处理器 
```
2. ApplicationContext
```
ApplicationContext-->
```
3. 接口体系？？？