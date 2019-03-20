# Git基本教程

官方的可以参考[Github](https://guides.github.com/activities/hello-world/)，太长了可以不看。

针对这个项目，

1.去[git](https://git-scm.com/)的网站下载git。 Download XXXX for windows即可。

2.安装git。

3.使用快捷键WIN+R打开运行程序，输入cmd启动命令提示符:

> C:\Users\Insom>

使用cd指令可移动当前目录(即change directory)：

> cd ..
> C:\Users>

cd ..表示向上一级移动。 

可以键入dir指令来罗列当前路径下的文件：

>C:\Users>dir
>
> Directory of C:\Users
>
>12/29/2018  01:22 PM    <DIR>          .

>12/29/2018  01:22 PM    <DIR>          ..

>03/18/2019  11:20 PM    <DIR>          Insom

>12/30/2018  05:18 AM    <DIR>          Public

>               0 File(s)              0 bytes

>               4 Dir(s)  326,636,441,600 bytes free

输入cd [文件夹名]移动到想去的文件夹

>C:\Users>cd Insom

如果不想打全可以按tab，会自动补全文件名字。

接下来进入到github部分。使用上述方发移动到你想去的文件位置，键入

>git clone https://github.com/cau-sky/place_holder.git

来克隆这个项目的文档和代码。进入到这个文件夹内，修改你想修改的文件，保存。

如果你是第一次使用git，你需要设置你的账号:

> git config --global user.name "John Doe"
> git config --global user.email johndoe@example.com

邮箱替换成你注册github的邮箱。

在place_holder根目录输入:

> git add --all

来加入你修改的文件

> git commit -m "commit info"

来上交你的文件，commit info部分替换为你对此次更改的描述。最后，使用

> git push

将你的文件推送至服务器端。

**每次**使用 git push前，**一定**要使用

> git pull

同步你的本地文件和服务器端文件，避免有他人改动。

日后我们经常使用的也只有这几个命令，如果过于繁复，那也可以不用，直接去https://github.com/cau-sky/place_holder.git 下载压缩包，解压缩后在文件夹内右键点选git bash here，重复git add --all之后的步骤即可。