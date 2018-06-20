# CMD
1. 清空静态页面 
    - hexo clean
2. 生成静态页面 
    - hexo generate
3. 部署 
    - hexo deploy
4. 缩写
    - hexo g：hexo generate
    - hexo c：hexo clean
    - hexo s：hexo server
    - hexo d：hexo deploy
5. 组合
    - 清除、生成、启动
        hexo clean && hexo g -s
    - 清除、生成、部署
        hexo clean && hexo g -d
# 常见问题
1. hexo deploy没有反应
    - 修改配置文件：_config.yml时，冒号后面没加空格。
2. hexo s 网站打不开？
    - 端口占用，换个端口就好了。执行命令hexo s -p 5000，并在浏览器地址栏输入http://localhost:5000，回车访问。
3. 如何换主题？
    - 将主题下载后，放到themes文件夹中即可。例如，下面命令安装next主题：git clone https://github.com/iissnan/hexo-theme-next themes/next。

# 参考资料
1. [hexo官方文档]: https://hexo.io/zh-cn/
2. [NexT主题官方文档]: http://theme-next.iissnan.com/getting-started.html
3. [hexo 下的分类和表签无法显示，怎么解决？]: https://www.zhihu.com/question/29017171
4. [手把手教从零开始在GitHub上使用Hexo搭建博客教程(一)]: http://www.jianshu.com/p/f4cc5866946b
5. [Github上搭建Hexo如何跨电脑写作部署方便？]: https://segmentfault.com/q/1010000004593371
6. [Continuous Integration Your Hexo Blog With Travis CI]: http://blog.bigruan.com/2015-03-09-Continuous-Integration-Your-Hexo-Blog-With-TravisCI/
7. [【Hexo+Github】域名和github绑定的问题]: http://www.jianshu.com/p/1d427e888dda
8. [万网域名+GitHub平台搭建的博客]: http://www.jianshu.com/p/3cb4c9ff5b58
