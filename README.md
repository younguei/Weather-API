## Welcome to GitHub Pages

需要用到的网站：

1. [由IP地址获取当前位置](http://freegeoip.net/?q=45.63.31.5)
2. [OpenWeatherMap文档](http://openweathermap.org/current)
3. [OpenWeatherMap各种参数介绍,当初也是在网站上找了半天，很费劲，特意贴出来)](http://openweathermap.org/weather-conditions)

OpenWeatherMap介绍：

​	一定要把这部分的文档看全，尤其是请求时用到的参数。自己在请求数据的时候获得的当前温度太高，原来还有一个默认参数未填写，units ，该参数值可以有imperial metric 表示华氏温度、摄氏温度，当然默认不写的话表示开尔文温度，所以自己立刻就明白了为什么获取的温度高达数百度的错误原因。

在github上跨域请求数据的方法：

​	一定要使用https协议

疑问：什么时候需要向url后添加"&callback=?"
