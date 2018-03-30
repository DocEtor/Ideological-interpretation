# 面向对象子思想集合

#### IOC/DI 控制反转/依赖注入

> 凡是需要程序主动操作的动作，转换为由第三方操作，达到类与类之间松耦合的效果。
>
> 举例：对象创建。若是在方法内需要一个对象，然后使用new 关键字去创建，这样会造成类与类之间极其大的耦合，也不利于资源重复使用。若是把创建对象的权限交于第三方，由第三方统一管理对象资源，使得类与类之间松耦合，也利于资源重复使用，也方便单元测试。
>
> 文章名称：《Inversion of Control Containers and the Dependency Injection pattern》
>
> 思想文章：http://www.martinfowler.com/articles/injection.html
>
> 具体实现：Springframework:BeanFactory
>
> 特别提醒：IOC思想可以不仅仅局限在创建对象的层面，只不过Spring通过这种思想在创建对象上有具体实现