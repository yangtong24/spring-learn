## Bean启动过程分析

### ClassPathXmlApplicationContext学习
#### refresh()


我们可以理解为ApplicationContext内部持有了BeanFactory的一个实例对象(DefaultListableBeanFactory), 所有的BeanFactory相关操作都委托
给这个实例对象来处理。
