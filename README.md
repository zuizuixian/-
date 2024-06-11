## 标题修饰符\#

# 一级标题
## 二级标题
### 三级标题

## 正文内容
   换行：\<br\>标签

# Github 
## 关键字查询
awesome,去除标签类别中查询项目<br>
python tutorial,查询资料、书籍、文档<br>
socket sample,查询对应计数的代码样本<br>
# Githubs三要素
## Repository 仓库
仓库是github项目管理存储基本单位，一个仓库中存储一个项目，一个用户可以拥有多个仓库，一般仓库分为public、private
## Commit 提交
程序员在整个开发周期，有大量的对代码资源的选代和修改，都可以通过commit的方式进行记录， 便于程序员回溯代码, 即是这些代码被删,提交便于使用者观察整个工程的开发流程以及设计流程
## Branch 分支
在仓库中可以包含多个分支，分支才是代码文件的第一存储单位，默认的仓库主分支为master/main<br>
不仅可以管理代码存储，便于多人协作开发<br>
![笔记图片1](https://i.postimg.cc/zVr2QLvT/1.png)

# 仓库内容
Code,资源存储,代码资源，二进制, 项目管理脚本， 许可证等等<br>
issues，使用时遇到的bug 或 进行提交， 等待反馈<br>
README;使用markdown语言编写，工程自述文件，开发进度，版本更新，使用介绍等等<br>
LICENSE 许可证,GPL2.0，3.0.Apahce 2.0,Mit, 这些许可证， 给使用者最大使用权限以及最少的限制<br>
# Git软件，分布式版本控制系统
仓库管理软件，使用gi管理私人代码或企业代码<br>

# 设备认证
1、如何让网站的账户与设备绑定，后续完成代码的管理, 上传下载<br>
git init   创建本地仓库<br>
git config --list   查看git的配置文件<br>
git config --global user.email"邮箱"<br>
git congig --global user.name"用户名“<br>
ssh.keygen -t rsa -C "注册邮箱"   创建本地密文<br>
ssh -T git@github.com   测试关联是否成功<br>
2、为目标仓库起别名，定位目标仓库，后续上传<br>
git remote add orgin "ssh地址"   为ssh仓库地址起别名为origin<br>
git remote remove origin   删除origin别名<br>
# 本地设备与云端仓库的交互逻辑
git add       添加内容<br>
git rm        删除本地文件并删除仓库数据<br>
git restoe    恢复被删除的（仓库存在）<br>

# 代码更新的依赖关系被破坏
本地内容要比云端新，完成更新替换，但是如果直接修改云端内容,导致本地内容无法再次提交<br>
先拉取 git pul 云端内容 与本地内容合井或操作， 而后再次推即可<br>
git pull --rebase origin master<br>
git rebase --skip   忽略本地内容，保留云端内容<br>
git rebase --abort  忽略云端内容，更新本地后可上传<br>
git rebase --continue  版本合并，解决冲突后可上传<br>
# 下载开源代码
git clone "https仓库地址"   下载开源项目code资源<br>
# 分支Branch
关于分支的相关命令，创建分支、选择分支、合并分支等等<br>
# Markdown语言
Markdown，文本修饰语言，用特殊符号修饰正文效果




