<h1>Spring Cloud简介</h1>
<p>Spring Cloud是一系列框架的有序集合。它利用Spring Boot的开发便利性巧妙地简化了分布式系统基础设施的开发，如服务发现注册、配置中心、消息总线、负载均衡、断路器、数据监控等，都可以用Spring Boot的开发风格做到一键启动和部署。Spring并没有重复制造轮子，它只是将目前各家公司开发的比较成熟、经得起实际考验的服务框架组合起来，通过Spring Boot风格进行再封装屏蔽掉了复杂的配置和实现原理，最终给开发者留出了一套简单易懂、易部署和易维护的分布式系统开发工具包。
</p>
<p>
Spring Cloud 为开发者提供了在分布式系统（配置管理，服务发现，熔断，路由，微代理，控制总线，一次性token，全居琐，leader选举，分布式session，集群状态）中快速构建的工具，使用Spring Cloud的开发者可以快速的启动服务或构建应用、同时能够快速和云平台资源进行对接。
</p>

<hr>
<h1>Spring Cloud组成</h1>
<ul>

<li>Spring Boot                微服务，自动化配置，简化开发，一切组件以及应用服务的基础</li>
<li>Spring Cloud Eureka 注册中心，服务注册与发现Spring Cloud Ribbon 客户端负载均衡</li>
<li>Spring Cloud Hystrix 服务容错保护，熔断、降级、缓存、请求合并、服务监控</li>
<li>Spring Cloud Feign   声明式服务调用，隐藏调用细节，就像调用本地代码一样</li>
<li>Spring Cloud Zuul     API网关服务，聚合各个微服务的接口，对外提供一个统一的服务</li>
<li>Spring Cloud Config 分布式配置中心</li>
<li>Spring Cloud Bus     分布式消息总线</li>
<li>Spring Cloud Stream 分布式消息驱动服务</li>
</ul>

<hr>
<h1>Spring Cloud架构</h1>
