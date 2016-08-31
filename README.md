# lua http_build_query实现

最近研究api网关, 需要用到lua做签名,
其中需要用到类似于http_build_query的方法, 找了下没有现成的实现
或者大部分只针对一维数组(table), 并没有针对多维数组(table)的实现
于是动手写了个,还是初次写lua.
