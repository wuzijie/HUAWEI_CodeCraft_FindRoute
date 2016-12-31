题目链接 http://codecraft.huawei.com/home/detail
##概述
对于NP完全问题，是根本不能去精确求解的，所以我们只能去求近似解，我们选择的是遗传算法，因为题目数据规模较大，故又需要进行使用dijkstra算法对图进行降解
主要代码在SDK-gcc下的route.cpp文件，其他为官方提供的。
SDK-gcc目录下为c/c++版本的SDK，具体使用方法参看该路径下的readme。
SDK-java目录下为java版本的SDK，具体使用方法参看该路径下的readme。
case0目录下为一套测试例，其中topo.csv为图的信息文件，demand.csv为路径信息文件。
大赛提供的SDK为必选开发平台，提交时是提交自己修改或新增的源文件，由官方统一编译。SDK中源码文件分为可修改和不可修改两部分，官方编译时会使用官方标准文件覆盖所有不可修改的文件。
