# 用例
## 计算需要告警的事件列表
执行者：定时器
## 设置事件阈值、持续时长

# 基础
告警阈值的路由和下面讲的路基很类似。
alertmanager 的功能是路由告警信息给指定的接受者。路由规则是，查找最匹配的子节点路由。
https://yunlzheng.gitbook.io/prometheus-book/parti-prometheus-ji-chu/alert/alert-manager-route
