为了尽量贴近真实，我们假设以下场景

> 有两个账号，一个是alphaCentauriBF，这个账号发起一个项目，但是项目有未完善的地方，为了方便，代码尽量简单
>
> RAINLFF，这个账号加入上面的项目的开发
>
> 程序是一个简单的C语言程序，计算一个整数的绝对值，在alphaCentauriBF给出的程序中，定义了这个函数，但是并没有写有关这个函数的代码，这个代码由其他人完善。
>
> 下面是C语言代码
>
> ```c
> #include<stdio.h>
> int abs(int num);
> int main()
> {
>     printf("%d",abs(-7));
>     return 0;
> }
> ```

首先是alphaCentauriBF视角

alphaCentauriBF在github上创建了一个仓库，并包含上面的C语言代码。

> ![](/assets/import3.png)项目仅包含C语言代码和一个README文件

接下来切换到RAINLFF\(我的另外一个GitHub的用户名\)视角。

要想参与一个项目的开发，现在**对应的作者的主页**Fork他的项目

然后进入**自己的项目的列表**，可以看到自己fork的项目，点击进自己fork的项目

登陆GitHubDesktop

> ![](/assets/import00.png)
>
> 找到想要克隆的项目的网址，可以点击蓝色的按钮直接在desktop打开

> ![](/assets/import0.png)若是点击上面的蓝色按钮没有反应，可以自己手动填写，具体的打开方式为file-&gt;clone respository-&gt;URL
>
> 在下面的Local path选择需要存放在本地的地址

clone下来后即可进行一顿操作，在这里我用记事本对代码做了修改

![](/assets/import7.png)

再次打开GitHubDesktop，发现提示文件发生了修改

> ![](/assets/import9.png)在左上角的Current respository可以选择当前操作的仓库，文本框中绿色部分显示出了做了什么修改。
>
> 在左下角填写信息后即可commit

> ![](/assets/import10.png)提交commit后即可push orgin，即推送到远程\(github.com\)
>
> 正常情况下会推送成功

> ![](/assets/import11.png)直接推送发现有这个提示，因为自己没有权限，所以我们应该发起pull request
>
> 如果推送不成功，出现这个提示，请确认自己的项目是从作者处fork了一个副本，然后clone的是在自己的主页中fork的版本的链接。否则权限不满足\(因为此时没有直接合并到作者的仓库的权限,只能推送到自己fork的仓库上\)。

接下来就是在网页上发起pull request

然后等项目管理者接受

具体步骤参照上文，这里不再给出

项目管理者确认合并请求后，文件即发生改变

> ![](/assets/import02.png)这是项目管理者处的代码，可以看到已经发生了改变。



