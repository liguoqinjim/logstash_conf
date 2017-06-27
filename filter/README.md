### filter

### grok1.conf运行结果
![Imgur](http://i.imgur.com/ukRXNLV.png)

### grok2.conf运行结果
grok2和grok1的区别是用了不一样的正则表达式，grok2里面会把request_time直接转换为数字，而grok1里面匹配完之后就是字符串

![Imgur](http://i.imgur.com/eaVqaXt.png)

### geoip.conf
![Imgur](http://i.imgur.com/Rcxax4b.png)

### json1.conf
![Imgur](http://i.imgur.com/2MUzIEe.png)

### json2.conf
如果不打算使用多层结构的话，删掉 target 配置即可。和json1.conf的输出比较
![Imgur](http://i.imgur.com/4Br8qAX.png)