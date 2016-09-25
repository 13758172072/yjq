# 亿街区注意事项
## 文件夹说明

### 1. html文件:
存放在yjq目录下
### 2. js文件：

页面单独使用的js：

	先在script文件夹下创建一个以文件名命名的文件夹，再在其下面创建文件，例如”平台介绍“页面，应该按以下格式创建js

	`yjq/script/ptjs/ptjs.js`

公用的框架和仓库：

	在script的lib文件夹下创建，以jQuery为例，应该如下创建

	`yjq/script/lib/jQuery.js`


	注意:css和image依次类推

### 3. 分支切换

项目目录下，右键，选择最上侧第2项`“fetch”`

然后选择`“Switch/Checkout”`

然后在弹窗中选择`“remote/origin/branch”`这个分支，在这个分支上开发

如果选择成功，在项目目录下右键，会显示`Git Commit -> "branch"`

### 4. 冲突处理

个人修改个人的代码，轻易不要修改别人的代码，如果要修改，提前沟通好，不要同时修改

操作步骤严格按照先更新（pull）再提交（commit+push）的流程来

但是，这样还是不可避免的会产生冲突，冲突发生之后，项目文件夹下，`右键-》TortoiseGit-》Diff`会显示冲突的地方，具体操作等发生了冲突再说
