### 现象
- Agent和Collector的日志中没有异常
- UI除Trace查询页面外，其它页面无数据

### 原因
Collector和被监控应用的系统主机时间，没有同步。

### 解决方法
同步各主机操作系统时间。
