# 协作开发使用规范流程

### 第一步: fork 当前工程到自己的 github 账户下

fork 的过程相当于创建了一个新的分支

### 第二步: 在自己名下的 github 中的仓库下进行自己的提交

新加入用户请按照以下格式进行第一步提交:

新增加一个文件在 user 目录下, 在 user 目录下执行以下命令

	echo "[班级 - 姓名] 加入协作开发" >> [姓名拼音].txt
	eg. echo "电线132班 - 王兵 加入协作开发" >> wangbing.txt

然后提交信息填写:

	git commit -m "user: wangbing joined develop"

### 第三步: 申请一个 pull request

将自己账户名下的代码推送到主账户中
