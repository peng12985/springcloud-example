#Spring Cloud Sleuth
Spring Cloud Sleuth集成了zipkin组件
微服务架构上通过业务来划分服务的，通过REST调用，对外暴露的一个接口，能需要很多个服务协同才能
完成这个接口功能，如果链路上任何一个服务出现问题或者网络超时，都会形成导致接口调用失败。随着
业务的不断扩张，服务之间互相调用会越来越复杂。