
---
title: Hello World
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start
1. 新建目录blog
2. 新建一个仓库，啥也不干
3. cd blog，git lone 生成目录 xxxxx.github.io
4. touch README.md
5. *重点：* 新建一个两个新分支master，hexo `git checkout -b hexo`，并同步到远程仓库`git push origin hexo:hexo`
5. 新建一个空文件夹hexo，hexo init
6. `hexo -g`产生public，这个目录是hexo生成的html静态文件。 将public目录复制到目录xxxxx.github.io
7. 切换到master分支， git add; git commit; git push
8. 将hexo目录复制到blog，将xxxxx.github.io 中的.git目录复制到blog/hexo中
9. git checkout hexo ， git add; git commit; git push
10. 写文章

- 创建一篇新文章

 `hexo new [post | draft] <title>`

-




More info: [Deployment](https://blog.csdn.net/qq_37210523/article/details/80909983)

## Quick recovery
1. `git clone`
2. `git chekout hexo`
3. `npm install`
4. `hexo g`
5. `hexo s`
