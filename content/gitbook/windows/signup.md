# 四、创建书并关联GitHub仓库

---

1.首先，你需要登陆[http://github.com/](https://github.com/)， 注册一个Github账号,点击sign up按照提示一步步注册即可。

![picture112](/assets/图片2.png)
2.有了Github账号后你可以不用再去单独注册Gitbook了。登陆[https://www.gitbook.com/](http://www.gitbook.com/)， 点击右上角sign in。
![picture113](/assets/图片3.png)
选择sign in with Github
![picture114](/assets/图片4.png)
3.我们进入Gitbook中，创建一本书，书的名字为test_book，Description里面写这本书的描述，填好后点击右下角的Create Book按钮
![picture115](/assets/图片5.png)
    
4.这样一本书就创建好了，下面我们要连接Github来实现协同合作的功能。先进入这本书中，选中settings，然后复制下图中的Gitbook中的地址，这个地址用于将这本书的URL传给Github中的某个仓库中。
![picture116](/assets/图片6.png)

5.进入网址[https://github.com/new/import](https://github.com/new/import)中,将刚才复制的地址复制到URL中，并创建一个Github仓库，这样Github就可以通过这个地址与Gitbook进行同步。
![picture117](/assets/图片7.png)

6.点击上图的Begin import后，要输入你的github的账号和密码。

![test4](/assets/test4.png)

7.导入成功后，gitbook这本书的地址就给了github中对应的仓库了。
![picture118](/assets/图片8.png)

8.完成Gitbook的导入后，只是将Gitbook中的地址给了Github，还需将Github的仓库地址给Gitbook，此时我们就需要回到Gitbook中，添加一下Github对应的仓库，即我们第5步创建的test_repository仓库，这样才完成了Gitbook与Github之间的双向通信。
![picture119](/assets/图片9.png)

9.(此步非必需)这样就完成了gitbook与github的关联，但是大家有没有想过，光用gitbook写书就可以了，为什么要把它和github关联起来呢？这是因为首先github中可以进行协同合作，比如一本书需要由多个人同时编写，小辉要写这本书，小强也在同时编辑这本书，这时候在github上就能清楚的看到是谁在什么时间编辑了这本书，进行了哪些修改，其次，就是github可以设置权限，比如小辉是这本书的创建者，他想邀请小强一起编辑这本书，这时就可以给小强赋予权限，这样小强也能编辑这本书了，具体如图：

每个仓库都可以选择合作人：

![picture122](/assets/图片12.png)
10.建立了github与gitbook的联系以后，我们就可以安静的写书了，首先我们需要下载Gitbook客户端，在客户端中用markdown编辑既方便又快捷，我们首先需要将我们在云端的test_book这本书下载到本地，编辑后再将test_book上传到云端，下载如下图所示：
![picture120](/assets/图片10.png)
11.进入这本书以后，就可以编辑了：
![test8](/assets/test8.png)
12.写完后同步到云端：
![test9](/assets/test9.png)
13.同步后，就可以登陆gitbook和github上，发现仓库中的内容发生了变化，所以我们以后就可以在Gitbook客户端上编写，然后上传到云端以网页的形式显示出来。
![picture121](/assets/图片11.png)
**现在已经将GitBook上书的仓库和GitHub上书的仓库关联起来了，以后既可以通过GitBook写书，也可以将更新提交到GitHub，极大的方便了多人协作撰写一本课本。**

**以后就可以通过**[**https:\/\/username.gitbook.io\/仓库名\/**](https://username.gitbook.io/仓库名/)** 在线阅读或下载图书。**

_下面介绍通过GitBook客户端撰写的方法。_

