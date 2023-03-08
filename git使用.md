# git使用

[toc]

## 一、配置全局

1. 配置用户名

```shell
git config --global user.name "your name"
```

2. 配置邮箱

```shell
git config --global user.email "your_email@youremail.com"
```

3. 验证结果

```shell
git config --glboal --list
```

4. 生成 ssh key

```shell
ssh-keygen -t ed25519 -C 'your_email@email.com'
```

## 二、基本命令

1. 初始化仓库

```shell
git init
```

2. 上传临时仓库

```shell
git add [file]
```

3. 提交仓库

```shell
git commit -m "informaiton"
```

4. 查看结果

```shell
git status 
```

5. 查看修改内容

```shell
git diff
```

6. 撤销修改

```shell
git checkout -- [file]
```

7. 查看分支

```shell
git branch
```

8. 创建分支

```shell
git branch [要建的分支名]
```

9. 切换分支

```shell
git checkout [要去的分支名]
```

10. 查看提交日志

```shell
git log
```

11. 合并分支

```shell
git merge [要被合并的分支名]
```

12. 最终提交

```shell
git push
```







​        

