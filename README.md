# x82y
某里有感、无感滑块验证教程
此教程只做参考。

/nocaptcha/initialize.jsonp 
/nvc/nvcPrepare.jsonp 
/nocaptcha/analyze.jsonp 
三个路由的包要验证过，

主要是其中W值的生成算法逆向、也称UA值。 
无感UA值的生成采集了本地的环境各项指纹信息。 
第二次采集鼠标的移动轨迹信息。 



主要流程：
1.通过AST树反混淆conllina.js文件。 
2.动态调试抠出UA值的生成算法逻辑。 
3.补环境参数、补鼠标轨迹参数。 
4.可以在node环境跑起来，自动生成UA值，优点是直接调用conllina.js文件中的核心函数，避免重写减少大部分工作量。 



总结：
  需要接口的 加Q: 3449553932 
  





















