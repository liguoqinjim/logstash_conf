### apache_log

|文件名|简介|
|---|---|
|test1.conf|读取日志文件并输出|
|test2.conf|grok|
|test3.conf|geoip|
|test4.conf|测试windows下读取文件的路径|
|test5.conf|测试windows下的stdin,stdout|
|test6.conf|windows下grok|
|test7.conf|geoip|
|test8.conf|date|
|test9.conf|useragent|
|test10.conf|output到elasticsearch|

### test2.conf运行结果
![Imgur](http://i.imgur.com/awcVexe.png)

### test5.conf运行结果
![Imgur](http://i.imgur.com/wwWLJ93.png)

### test6.conf运行结果
![Imgur](http://i.imgur.com/J5kns47.png)

### 遇到的问题
#### 文件的读取
文件的读取好像有些问题，为了测试方便，只在文件里面放了一行数据。但是大部分时候logstash是不会读这个文件的。所以为了测试只能用stdin来代替了。