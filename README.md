### 服务管理
> 启动服务 => docker compose -f ./nginx_compose.yml up -d

> 停止服务 => docker compose -f ./nginx_compose.yml down
 

### 如何测试
可以使用curl http://127.0.0.1:8088/ 去测试upstream的轮训策略

### 如何更改虚拟主机的配置
在config目录下，有三个config，
> 分别是upstream.conf => 对应代理的配置

> node1.conf => 对应node1的配置

> node2.con => 对应node2的配置
