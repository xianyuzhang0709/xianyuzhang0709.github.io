# xianyuzhang0709.github.io

* hexo分支是一个环境配置分支（目前被设置为默认分支），删掉了`.ignore`，所以文件会比较大，78M。  
但是因此不需要每次在新电脑上运行`npm install`（安装`node_modules`文件夹）。  
* 安装hexo：`npm install -g hexo`  
* 开始写博客。
* `hexo server` + `hexo clean && hexo g && hexo d` 会将改动部署到master分支上，更新http://xianyuzhang0709.github.io 的页面情况。  
`git add *` + `git commit -m ""` + `git push`则将会把整个文件夹（hexo博客环境）全部在hexo分支更新。
  
* 两个分支互不干扰。至于要更新themes，只能更新然后粘贴到本文件夹。
* 记得在更新前git pull再开始写博客。
