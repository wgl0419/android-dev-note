## UML
- [uml类图(Class Diagram)中类与类之间的关系及表示方式](http://blog.csdn.net/a19881029/article/details/8957441)

> **1，依赖关系(Dependency) -- 依赖你才可以**  
> 单向，表示一个类依赖于另一个类的定义，其中一个类的变化将影响另外一个类，是一种“**_use a_**”关系   
> 如果A依赖于B，则B表现为A的**局部变量，方法参数，静态方法调用**等   
>  
> **2，关联关系(Association) -- 要有你，平等关系，单向**   
> （通常我们需要避免使用双向关联关系），是一种"**_has a_**"关系，如果A单向关联B，则可以说A has a B，通常表现为**全局变量**   
>  
> **3，聚合关系(Aggregation) -- 整体局部，不平等关系，模块分区共有**    
> 单向，关联关系的一种，与关联关系之间的区别是语义上的，**关联的两个对象通常是平等的，聚合则一般不平等**，有一种整体和局部的 > 感觉，实现上区别不大    
> 
> **4，组合关系(Composition) --  共生共死的整体和局部，类**  
> 单向，是一种强依赖的特殊聚合关系
> （Head，Body，Arm和Leg组合成People，其生命周期相同，如果**整体不存在了，部分也将消亡**）  
>  
>  **5，继承关系(Inheritance) -- 来源**  
> **类实现接口，类继承抽象类，类继承父类**都属于这种关系
>  
> 可以分得更细：  
> 
> **实现（Realization）**：类实现接口属于这种关系  
> **泛化（Generalization）**：即"is a"关系，类继承抽象类，类继承父类都属于这种关系  


