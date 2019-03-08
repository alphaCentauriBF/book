---
description: >-
  这篇向导是从官网找到的英文向导，为了方便阅读我翻译成了中文的形式(因为GitHub本身为英文的网站，所以为了方便使用部分名词不翻译)，并更改和省略一部分内容，加括号的为冯同学自己加上的内容。如果想要详细了解，请点击下面的链接。
---

# GitHub向导

> https://guides.github.com/activities/hello-world/

## Hello World 项目

与学习很多语言相同，我们从一个Hello，World项目开始。

**在这个项目你将会学到:**

* 创建和使用仓库
* 开始和管理分支
* 更改文件并推送到Github
* 发起和合并pull request

## 第一步 创建仓库

仓库\( **repository**\)通常用来管理单个项目，仓库可以包含目录\(folder\)和文件、图片、视频、电子表格、数据集等等你项目所需要的所有东西，我们建议包含README文件\(可以理解成备注，当其他人获取你的项目后，一般是先看README文件\)，或者一个包含项目信息文件，GitHub可以在创建新存储库的同时轻松地添加一个README文件。 它还提供其他常见选项，例如许可证\(license\)文件。

你的Hello，World仓库可以成为一个你存放灵感、源码或者与别人进行分享和交流的地方。



#### 创建仓库的步骤

1. 在右上角的头像旁有一个＋号，点击＋号并选择 **New repository**
2. 给项目取名为 HelloWorld
3. 写下简短的描述
4. 选择 **Initialize this repository with a README**.

 下面给出图片以及说明

![&#x6B65;&#x9AA4;1](.gitbook/assets/image%20%2815%29.png)

![&#x6B65;&#x9AA4;2&#x3001;3&#x3001;4](.gitbook/assets/image%20%2819%29.png)

## 第二步 创建分支

分支是一种能让我们在不同版本的存储库上工作的方式\(例如在实际开发中，有稳定版本和测试版本，可以通过设置不同的分支来实现\)。

默认的，你的仓库只有一个名为master的分支，这个分支被认为是主干分支，也就是最终的分支。在将新的修改合并到主干分支之前，我们利用其他分支来进行测试。

当你创建一个新的分支时，你会得到一份副本\(making a copy,or snapshot\)，当你在自己的分支进行工作而其他人对主干进行修改时，你可以拉取\(pull\)这些更新。

![](.gitbook/assets/image%20%2829%29.png)

上述的图片表示了

* 主干分支
* 一个名为feature的分支
* feature分支在合并到主干分支时所经历的旅程\(在测试通过后提交Pull Request，项目的管理者可以决定要不要合并到主干分支\)。

在GitHub，开发者、作者和设计师可以使用分支的方式来修复BUG或者提交新功能,而在修改的过程中不影响主干。当一次修改做好时，可以与主干合并\(merge\)。

**创建分支**

1. 前往你创建的仓库
2. 点击文件顶的名为branch:master的下拉框
3. 在输入框Find or create branch中输入分支名readme-edits以创建新的分支
4. 点击Create Branch

![&#x6B65;&#x9AA4;2&#x3001;3&#x3001;4](.gitbook/assets/image%20%284%29.png)

现在，你拥有两个分支了，他们看起来一样，但接下来我们会对新分支进行改变。

## 第三步 修改和提交修改

现在，你已经处于readme-edits分支\(master分支的复制\)了，如下图。

![&#x5728;&#x5DE6;&#x4E0A;&#x89D2;&#x7684;Branch&#x6807;&#x7B7E;&#x4E2D;&#x6807;&#x8BC6;&#x4E86;&#x76EE;&#x524D;&#x6240;&#x5904;&#x4E8E;&#x7684;&#x5206;&#x652F;&#x3002;&#x4E5F;&#x53EF;&#x4EE5;&#x70B9;&#x51FB;&#x90A3;&#x4E2A;&#x6807;&#x7B7E;&#x4FEE;&#x6539;&#x76EE;&#x524D;&#x6240;&#x5904;&#x7684;&#x5206;&#x652F;&#x3002;](.gitbook/assets/image%20%2811%29.png)

在GitHub中，保存修改被称为Commits，每个commit都有一个与之关联的commit信息\(message\)，用来解释为什么做这个修改等。从提交消息中，你和其他人都可以知道做出的修改的历史。

**修改与提交\(commit\)修改步骤**

下面以README.md文件为例，在实际使用中可以任意选择文件。

1. 选择README.md文件
2. 点击文件右上的“笔”图标对文件进行编辑
3. 在编辑器中，写入一些文字
4. 对你的修改进行说明
5. 点击Commit changes进行提交

![&#x6B65;&#x9AA4;2](.gitbook/assets/image%20%288%29.png)

![&#x6B65;&#x9AA4;3&#x3001;4&#x3001;5](.gitbook/assets/image%20%2820%29.png)

提交之后，可以看到如下的情况。

![&#x6211;&#x4EEC;&#x4E0A;&#x9762;&#x586B;&#x7684;&#x7B80;&#x77ED;&#x7684;&#x8BF4;&#x660E;&#x76F4;&#x63A5;&#x663E;&#x793A;&#x5728;&#x6587;&#x4EF6;&#x540D;&#x7684;&#x53F3;&#x8FB9;&#xFF0C;&#x800C;&#x8BE6;&#x7EC6;&#x8BF4;&#x660E;&#x9700;&#x8981;&#x5C06;&#x9F20;&#x6807;&#x79FB;&#x8FC7;&#x53BB;&#x6216;&#x8005;&#x70B9;&#x51FB;&#x540E;&#x624D;&#x80FD;&#x663E;&#x793A;&#x3002;](.gitbook/assets/image%20%2823%29.png)

## 第四步 发起Pull Request

漂亮的修改嗷。但是现在主干\(master\)分支并没有发生修改，如果你想要将这个修改合并到master分支中华，你可以发起一个Pull Request。

Pull Request是GitHub中协作开发的核心，当你发起一个Pull Request，意味着你想让你的修改被别人审核并合并到他们的分支中，Pull Request会显示分支的不同，增加的部分显示为绿色，减少的部分显示为红色。当你提交\(commit\)的时候，即使代码并未完成，你可以发起一个Pull Request并展开讨论。

通过Github在Pull Request的 [@mention system](https://help.github.com/articles/about-writing-and-formatting-on-github/#text-formatting-toolbar)，你可以得到他人或者其他团队的反馈。你也可以在自己的仓库中发起Pull Request并自己合并，这样子你可以在参与大项目的开发之前。 学习到使用Github的工作流。

**对对README文件的修改发起一个Pull Request（并不是病句）**

![&#x53D1;&#x8D77;&#x4E00;&#x4E2A;&#x65B0;&#x7684;pull request](.gitbook/assets/image%20%2821%29.png)

![&#x9009;&#x62E9;&#x4F60;&#x505A;&#x51FA;&#x4FEE;&#x6539;&#x7684;&#x5206;&#x652F;&#xFF0C;&#x5E76;&#x4E0E;master\(&#x4E3B;&#x5E72;\)&#x505A;&#x51FA;&#x6BD4;&#x8F83;](.gitbook/assets/image%20%2832%29.png)

![&#x89C2;&#x5BDF;&#x4FEE;&#x6539;&#x7684;&#x90E8;&#x5206;&#xFF0C;&#x786E;&#x5B9A;&#x8FD9;&#x4E2A;&#x662F;&#x4F60;&#x60F3;&#x8981;&#x7684;&#x4FEE;&#x6539;\(&#x7EFF;&#x8272;&#x4E3A;&#x6DFB;&#x52A0;&#xFF0C;&#x7EA2;&#x8272;&#x4E3A;&#x5220;&#x9664;\)](.gitbook/assets/image%20%2814%29.png)

![&#x786E;&#x8BA4;&#x4E4B;&#x540E;&#x70B9;&#x51FB;Create pull request&#x6309;&#x94AE;&#x53D1;&#x8D77;pull request&#x8BF7;&#x6C42;](.gitbook/assets/image%20%2816%29.png)

![&#x586B;&#x5199;pull request&#x7684;&#x6807;&#x9898;&#x4EE5;&#x53CA;&#x63CF;&#x8FF0;&#xFF0C;&#x70B9;&#x51FB;&#x53F3;&#x4E0B;&#x89D2;&#x7EFF;&#x8272;&#x6309;&#x94AE;&#x8FDB;&#x884C;&#x63D0;&#x4EA4;](.gitbook/assets/image%20%2818%29.png)

## 第五步 合并Pull Request

在这一步中，你可以将Pull Request合并到主干分支中。因为这个项目我们自己就是管理员，所以可以直接merge。

1. 点击绿色的 **Merge pull request**按钮将你的分支合并到master
2. 点击 **Confirm merge**.
3. 删除readme-edit分支，因为它的更改已合并，点击紫色框中的删除分支按钮

![&#x6B65;&#x9AA4;1&#x4E2D;&#x7684;Merge pull request&#x6309;&#x94AE;&#x53EF;&#x4EE5;&#x5BF9;&#x5206;&#x652F;&#x8FDB;&#x884C;&#x5408;&#x5E76;&#xFF0C;&#x4E0B;&#x9762;&#x7684;&#x8F93;&#x5165;&#x6846;&#x53EF;&#x4EE5;&#x5BF9;&#x8FD9;&#x4E2A;pull request&#x8FDB;&#x884C;&#x8BC4;&#x8BBA;](.gitbook/assets/image%20%287%29.png)

![&#x6B65;&#x9AA4;2](.gitbook/assets/image%20%2827%29.png)

![&#x6B65;&#x9AA4;3 &#x8FC7;&#x6CB3;&#x62C6;&#x6865;](.gitbook/assets/image%20%281%29.png)

关于GitHub使用的简单教程就到这里，在其他部分会有更加高级的用法，比如实战等等。请查看其他部分。

