四、部署

在_config.yml文件，找到deploy，进行以下配置：
deploy:
  type: git
  repo: https://github.com/username/username.github.io.git
  branch: master
安装部署工具

npm install hexo-deployer-git --save
新建一篇博客文章，在hexo/source/_posts文件夹下新建md文件(不用加.md后缀）

hexo new 文件名
最后输入以下命令生成网站文件并部署：

hexo g //生成网页文件
hexo s //localhost:4000本地预览效果
hexo d //部署
在浏览器输入https://username.github.io/就能看到博客网站了。
