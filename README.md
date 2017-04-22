# electron-test

简单体验了一下electron开发桌面应用，把我们公司的后台网络销售后台用electron实现了一下，
上手很容易，开发速度和写网页一样快.

# 运行

electron . 

# 打包

使用 electron-builder 打包

build --win --config=build.json

没有做任何优化的情况下 打包window exe  70M左右

# 截图
<a href="https://github.com/codeAB/electron-test/blob/master/Screenshot0.jpg" target="_blank"><img src="https://raw.githubusercontent.com/codeAB/electron-test/master/Screenshot0.jpg" style="max-width:100%;"></a>
<a href="https://github.com/codeAB/electron-test/blob/master/Screenshot1.jpg" target="_blank"><img src="https://raw.githubusercontent.com/codeAB/electron-test/master/Screenshot1.jpg" style="max-width:100%;"></a>

# 总结

运行速度还行，性能上可以接受，比起Qt来说API少的可怜，功能有限，交互界面 “炫” 不起来.

我觉得特别适合做 互联网+ 软件，  就是把网页应用搬到桌面上来.

直觉告诉我以后会有很多功能型网站都要出 “桌面软件” 了 .
