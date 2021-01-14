# simple_mvc

简单模拟mvc框架

一 配置uri与处理方法的映射
1. 读取配置文件信息
2. 通过反射获取处理类中的方法
3. 通过方法注解获取处理请求的uri
4. 使用map存储映射关系

二 拦截并处理请求
1. 在servlet中配置拦截路径
2. 通过request获取请求uri
3. 通过uri获取处理方法
4. 通过反射执行方法
