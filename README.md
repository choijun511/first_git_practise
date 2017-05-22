# first_git_practise

## practise

this is a practise of git.

初始化一个git库，注意git库不要太大，便于分拆

```
git init
```

添加一个文档到缓存区

```
git add README.md
```

提交到本地版本库

```
git commit -m "some reason"
```

添加远端地址，最好是ssh地址，每个代码库只需要添加一次

```
git remote add origin git@github.com:choijun511/first_git_practise.git
```

查看未提交的文件

```
git status
```

查看曾经的提交

```
git log
```

查看修改

```
git diff
```

克隆远端代码库，如果是别人的库，要fork到自己到github上，然后克隆下来

```
git clone git@github.com:choijun511/douban_crawler.git
```

不把一些文件提交到版本库，要在根目录创建.gitignore文件，然后把[链接](https://github.com/github/gitignore/blob/master/Python.gitignore)加入到文件中
```
touch .gitignore
```
