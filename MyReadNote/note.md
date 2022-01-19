# Note

## 源码目录结构

* db ：数据库的基本接口操作与内部实现
* table : SSTable的主要实现
* helpers ：底层数据结构完全运行在内存中的实现方法
* utils ：工具库：内存管理,布隆过滤器等
* include ：库函数和对外结接口
* port ：平台移植性的实现接口