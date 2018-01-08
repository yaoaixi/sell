# sell
- Spring Boot企业微信点餐系统

- 买家端类目模块的开发，按照dao->service->api的顺序开发。贯穿单元测试。

- 买家端商品模块的开发，按照dao->service->api的顺序开发。贯穿单元测试。

- 买家端订单模块的开发，按照dao->service->api的顺序开发。贯穿单元测试。

- 演示开发微信中的相关调试技巧，如内网穿透，就实现微信授权，获取OpenID的关键步骤逐一讲解

- 演示开发微信中的相关调试技巧，如移动端抓包工具charles使用，就实现微信支付和退款的关键步骤逐一讲解

- 卖家端订单模块的开发，详细演示利用Freemarker和iBootstrap简化实现后台功能的技巧。

- 实现后台管理中卖家端商品管理的通用功能和上下架功能的实现

- 实现后台管理中卖家端新增商品和类目管理的相关功能。

- 实现了微信扫码登录卖家端，登出等功能。以AOP的方式实现身份验证。同时介绍了微信模版消息，WebSocket消息推送的实现

- 异常处理。集成MyBatis的使用方法。并对JPA和MyBatis如何选择做了阐述。然后从浅入深，用压测工具模拟了并发较高的情况下会遇到的问题。演示了单点多线程情况利用synchronized应对的方法并分析了不足。再引出基于Reids分布式锁，解析了Redis分布式锁的原理。本章最后是Reids作为缓存的相关内容。...