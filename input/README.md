### input

|实验|简介|
|---|---|
|stdin.conf|标准输入，控制台输入|
|file.conf|读取文件|
|tcp.conf|通过tcp或者udp读取数据|

#### tcp.conf
##### 测试环境中可以使用nc作为客户端
`nc 127.0.0.1 8888` 连接之后可以输入要传输的内容

##### 运行结果
![Imgur](http://i.imgur.com/MH4bO35.png)

![Imgur](http://i.imgur.com/uSZR7eA.png)



#### 参考资料
https://kibana.logstash.es/content/logstash/plugins/input/