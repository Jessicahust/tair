Tair is a distributed key-value storage system originally developed at www.taobao.com.  
Maybe the best choice to serve as cache or persistent-kv service in credible enviroment as tair provide no security related feature.

* features:

 - simple client configuration thanks to lightweight config server
 - support for atomic counter 
 - data is automatically partitioned and replicated over whole cluster
 - server failure is handled transparently
 - realtime data sync between clusters which may deploy in different areas
 - excellent support multi-appliction scenario
 - flow control base on qps/bandwidth

* get and deploy tair

 - see: http://code.taobao.org/trac/tair/wiki/ZhWikiStart 

* Contribution

 - The source code is available user the GPL version 2.   
   We are avtively looking for contributors so if you have any ideas, bug reports, or patchs you would like to contribute please do not hesitate to do so.

* Roadmap
 - use kiwi as network framework.  
   The original network framework tair uses is [libeasy](https://github.com/alibaba/oceanbase/tree/master/oceanbase_0.4/libeasy_rpm) which is not opensource
