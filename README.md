# Spring-IoC-Container-Basics-
Spring IoC Container Basics 课程课后作业。
@Bean 和 @Component
1:在自动配置的方式中，使用@Component去告诉Spring，我是一个bean，你要来管理我，然后使用@AutoWired注解去装配Bean。
然后在JavaConfig中，@Configuration其实就是告诉spring，spring容器要怎么配置（怎么去注册bean，怎么去处理bean之间的关系（装配））。
那么久很好理解了，@Bean的意思就是，我要获取这个bean的时候，你spring要按照这种方式去帮我获取到这个bean。
2:有一些类我们获取不到所以只能用@bean去注解，比如在一些lib中的类

