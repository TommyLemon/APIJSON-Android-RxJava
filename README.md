# APIJSON-Android-RxJava

全面使用RxJava。<br />

两个优化明显的代码段都在setList方法内。使用到RxJava的地方做了 “使用RxJava” 的标记。
![](http://www.cnblogs.com/tommylemon/gallery/image/184932.html) 

##  总结
1.对MomentActivity,MomentListFragment等逻辑比较复杂、缩进层级多的代码段 逻辑简化和减少缩进层级的效果明显，其它地方逻辑简单用起来反而更麻烦。<br />

2.RxJava的优势在于线程管理(提供IO,AndroidMainThread等线程)、集合与数组的处理(map,flatMap,filter)、层级和逻辑简化。
