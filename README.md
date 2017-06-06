必须要生成SSH公钥，上传到github上去，才能将代码上传到github上
# 生成SSH公钥并添加到github上去!
1. 打开 git bash 输入: `ssh-keygen -t rsa` 命令用于生成公钥和私钥。
> 一直按回车，就会在 [/c/Users/[用户名]/.ssh]  目录中生成两个文件 `id_rsa`和 `id_rsa.pub`  
> 他们分别是私钥和公钥

操作如图:
![生成公钥和私钥](./images/生成公钥私钥.gif)

生成的文件: 
![公钥私钥位置](./images/公钥,私钥.png)

2.复制公钥文件中的内容。
> 用编辑打开 id_rsa.pub 文件，并复制其中的内容

![复制公钥](./images/复制公钥.png)

3.添加到github中去
> 打开github 网站并登陆,如何所示操作

![Settings](./images/点开Settings.jpg)
继续:
![SSH-GPG-keys](./images/SSH-GPK-keys.jpg)
继续  
![New-SSH-keys](./images/New-SSH-keys.jpg)
继续  
![Add-SSH-keys](./images/Add-SSH-keys.jpg)
继续
![Confirm-PWD](./images/Confirm-PWD.jpg)