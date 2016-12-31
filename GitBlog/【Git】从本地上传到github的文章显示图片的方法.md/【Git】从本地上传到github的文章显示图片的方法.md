
虽然这段时间一直在git上上传代码或者是文章，但是还没有试过在github上面上传图片，前两天写了一篇博客，里面有很多插图，就想着是不是可以一块上传到github上面去呢？

中间失败的各种方法就不赘述，下面说一下成功的两种方法：

**方法一 ：**

将图片单独上传到github上，然后在编辑框中将图片在github中的链接加进去即可显示，这种方法一般适合在github上在线编辑文章时导入图片，因为比较麻烦；

在makedown中插入图片的语法如下：

```
//  ![图片描述]（图片链接）
```

如：我现在正在github上面编写文档，现在需要一张本地的图片；

![这里写图片描述](http://img.blog.csdn.net/20161231092851967?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYml0Ym9zcw==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

我们可以这样做；

将本地的图片上传到github,然后复制图片的链接，按照markdown的格式加入到编辑中：

![这里写图片描述](http://img.blog.csdn.net/20161231094546561?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYml0Ym9zcw==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

保存退出，看看展示效果：

![这里写图片描述](http://img.blog.csdn.net/20161231094906775?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvYml0Ym9zcw==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

（恩，图片内容不重要）；

**方法二：**

我么在github上面创建一个仓库的时候都会问你要不要创建一个 .md文件，你了解过这个 .md 文件的含义吗？

经常在写博客的话，你就会知道markdown编辑器，而github的一般文件也是md文件，即就是markdown文件，你会发现上面的加入图片的方式和写博客时是一样的；

那就是你在本地的一个markdown编辑器中写好东西，插好图片，然后就在markdown的编辑页面把内容全部复制（包括图片），新建一个 **.md** 后缀的文件，把内容黏贴进去，然后上传到github就好了，这会将本地图片一块上传的！！！

（这种方法，其实也看个人喜好，毕竟还不如直接在github上面进行编辑）

效果嘛！ 

如果你在github上看这篇文章，那么下面就是博客链接，否则就是gthub的效果展示链接：

http://blog.csdn.net/bitboss/article/details/53954046
