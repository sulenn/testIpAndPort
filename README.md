# 测试服务器端口号是否开放

```shell
# 拉取
git clone https://github.com/sulenn/testIpAndPort.git

# 编译
go build main.go

# 运行（默认监听端口为9090）
./main

# 浏览器检验（梯子可能会导致失败）
http://ip:9090/index.do

# 命令行检验（代理会导致失败）
curl http://ip:9090/index.do
```

**浏览器检验**:

![image.png](http://ww1.sinaimg.cn/large/006alGmrgy1gghb8dq477j30dx06baa4.jpg)

**命令行检验**:

![image.png](http://ww1.sinaimg.cn/large/006alGmrgy1gghbc1vt2kj30w504it9n.jpg)