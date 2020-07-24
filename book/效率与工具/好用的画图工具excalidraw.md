------------

**背景**
我们是不是每次和别人交流的时候，要用笔和纸，或者在黑板上画呀画。
推荐一个工具excalidraw
**安装**
安装方式很多种，我就用一种比较简单，也比较快的方式`docker`安装excalidraw，安装dokcer，不介绍网上一堆
首先
```shell
docker pull excalidraw/excalidraw
```
然后
```shell
docker run -itd --restart=always -p 4000:80 --name excalidraw excalidraw/excalidraw:latest
```

最后我们看效果吧

![一个好用的画图工具 excalidraw](https://cdn.learnku.com/uploads/images/202007/24/30046/svqaalA5VB.png!large)

效果很奈斯


