# jscdn

> jsDelivr提供npm，GitHub，WordPress等项目的镜像，全球加速访问！我们完全可以利用它来存一些静态文件了，如JS,CSS,图片等等！

### 使用限制
- 目前GITHUB仓库容量是没有上限的！不过官方推荐在1G以内！
- 仓库单个文件50M会收到警告，大于100M会被拒绝！
- jsDelivr仅能针对50M以下的文件CDN加速！
 


自建脚本/图片文件

1. 文件不想带版本号？将版本号换成latest即可！
2. 或者直接@master(或者其他分支名称)！

示例：
https://yuwengeng.github.io/jscdn/mybks.html
https://cdn.jsdelivr.net/gh/yuwengeng/jscdn@latest/pic.png

https://cdn.jsdelivr.net/gh/yuwengeng/jscdn/pic.png

https://cdn.jsdelivr.net/gh/yuwengeng/jscdn@master/pic.png

直接@master，就不用新建releases了！
