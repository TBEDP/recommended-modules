推荐模块列表
======
看官方的[模块列表](https://github.com/joyent/node/wiki/modules)也会让你眼花缭乱，所以我们整理一份我们推荐的模块列表。按解决方案分类。

- Web框架
    - connect
        - [connect-mredis](https://github.com/dead-horse/connect-mredis),基于mredis的session存储   
        - connect-render
        - response-cookie
        - response-patch
    - express
- 模版
    - ejs
- 流程控制
    - eventproxy
- 数据访问
    - mongoskin
    - redis
    - [mredis](https://github.com/dead-horse/multi_redis),管理连接多个redis服务，消除redis的单点问题。多写单读，提供请求超时处理
    - MySQL: [easymysql](https://github.com/aleafs/easymysql)，主从自动判断，异常支持相当完备
- 日志
    - logfilestream 
- 测试
    - 测试框架
        - mocha
    - 断言库
        - should
    - HTTP服务辅助库
        - supertest
    - Mock工具
        - rewire
    - 覆盖率
        - visionmedia-jscoverage 
    - 性能测试
        - benchmark
    - 自动化测试
        - webghost
    - 网络异常，服务模拟
        - [interceptor](https://github.com/dead-horse/interceptor)，提供真实服务与客户端之间的代理，模拟网络阻塞和请求截断。
- 多进程管理
    - [pm(node-cluster)](https://github.com/aleafs/pm)，大家都在用，不细说
- 并发流控
    - bagpipe
- 时间处理
    - moment
- 静态文件处理
    - loader
    - clean-css
    - uglify-js
- 邮件处理
    - nodemailer
- 编码转换
    - iconv-lite
    
     
     
