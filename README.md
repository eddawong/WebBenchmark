# WebBenchmark

实现一个简单的http加压工具, 并提供相应的rpc方法供调用.

基本的API有:

1. create
	建立测试条目, 初始化参数, 包括并发数, 总请求数, 访问的url范围等;
2. start
	启动测试;
3. state
	返回测试条目当前状态, 可能的状态有 pending, running, done, error等;
4. stat
	返回测试统计信息


