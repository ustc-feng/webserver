校验 & 数据库连接池
===============
数据库连接池
    池是一组资源的集合，在服务器启动之初就被完全创建好并初始化。连接池中的资源为一组数据库连接，由程序动态地对数据库连接进行使用、释放。当系统需要频繁访问数据库时，需要频繁创建和断开数据库连接，可直接对连接池中的数据进行操作。
> * 单例模式，保证唯一
> * list实现连接池
> * 连接池为静态大小
> * 互斥锁实现线程安全

校验  
> * HTTP请求采用POST方式
> * 登录用户名和密码校验
> * 用户注册及多线程注册安全

