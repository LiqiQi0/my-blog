#php中 echo-header 函数的实现。
问题的引出：
                           
                           在微信支付中有一个header的函数，它要求的是不能在header函数的前面有任何的echo的东西。
                           
                           而echo是向客户端的页面输出代码，header从道理上来说和客户端是没有任何的交集的。 
                           
                           但是PHP却是逐句执行的，也就是说 echo出代码之后，这是客户端。 header这是服务器。
                           
                           因此本问题的意义在于：\*\*分辨出服务器和客户端的代码的区别\*\*。
                
占坑。test0
