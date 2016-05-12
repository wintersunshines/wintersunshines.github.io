# wintersunshines.github.io
我的个人博客

## 技术
采用github pages+hexo构建,markdown书写blog

## 环境
- node
- hexo
- git

## 第一次克隆到本地

```
$
$ git clone https://github.com/wintersunshines/wintersunshines.github.io.git
$ npm install hexo-cli -g
$ cd wintersunshines
$ hexo init
$ npm install
```

## 本地预览
```
$ hexo s
```

## 部署
```
$ hexo g
$ hexo d
```

## git远程仓库出问题
`hexo init`会删除项目里的`.git`.因此当出现此问题后，执行以下命令：
```
$ cd wintersunshines
$ git init
$ git config user.name "__name__"            # __name__ 例如 one
$ git config user.email "__email__"          # __email__ 例如 one@126.com
$ git remote rm origin
$ git remote add origin git@github.com:wintersunshines/wintersunshines.github.io
```
然后就可以正常提交了。

## 一个客户端设置多个github账号
如果有需要，可以看这篇文章：[一个客户端设置多个github账号][multiple-github-id]

[multiple-github-id]: http://tmyam.github.io/blog/2014/05/07/duo-githubzhang-hu-she-zhi/
