# Hunter

[README](/README.md)

Hunter主题由 [Jacman](https://github.com/wuchong/jacman) 主题修改而来，主要修改了以下内容：
* 为了更便于搜索引擎爬到，添加了网站的keywords，您可以在hexo主配置文件subtitle后面添加keywords关键字，比如：keywords: word1, word2
* 添加了网站地图widget
* 修改了Jacman主题的字体
* 修改了Jacman主题整体色调
* 删除了Jacman主题中页面底部的个人简介
* 其他一些细微的修改

###添加RSS
- hexo提供了RSS的生成插件，需要手动安装和设置。步骤如下：
- 安装RSS插件到本地：npm install hexo-generator-feed
- 开启RSS功能：编辑hexo/_config.yml，添加如下代码：
```
plugins:
- hexo-generator-feed
```
- 然后在主题的配置文件中添加rss的widget即可

###添加sitemap
- hexo提供了sitemap的生成插件，需要手动安装和设置。步骤如下：
- 安装RSS插件到本地：npm install hexo-generator-sitemap
- 开启RSS功能：编辑hexo/_config.yml，添加如下代码：
```
plugins:
- hexo-generator-sitemap
```
- 然后在主题的配置文件中添加sitemap的widget即可

[主题演示](http://www.ihunter.me) | [Hunter的时光机器](http://www.ihunter.me)

---
以下是Jacman主题中原有的内容。

[如何使用 Hunter 主题](http://www.ihunter.me/%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8Hexo%E4%B8%BB%E9%A2%98Hunter.html)

##安装教程
###安装
```
$ git clone https://github.com/hunterzhang86/hunter.git themes/hunter
```
**Hunter 需要 Hexo 2.7 及以上版本** 
###启用
修改博客根目录下的配置文件 `_config.yml`，把`theme`的值修改为 `hunter`.
###更新
```
cd themes/hunter
git pull origin master
```
**请先备份您主题目录下的 `_config.yml` 文件后再升级。**

##配置指南

修改  `/themes/hunter/_config.yml` 中的配置。通过[配置指南wiki](https://github.com/wuchong/jacman/wiki/%E9%85%8D%E7%BD%AE%E6%8C%87%E5%8D%97)了解更多

##功能
- **菜单 menu**  
 主导航菜单
- **控件 widget**  
 侧边栏的控件。包括：分类、标签、RSS、归档、标签云、友情链接、微博秀。
- **图片相关 Image**  
 设置网站图标、网站logo、作者头像等。
- **首页模式 index**  
 首页的展示模式可以通过[Hunter的时光机器](http://ihunter.me) 来了解其内容。
- **作者 author**  
 作者信息，主要用于展示网站右下角的社交网络链接。包括：微博、豆瓣、知乎、邮箱、GitHub、StackOverflow、Twitter、Facebook、Linkedin、Google+。
- **目录 toc**  
 在文章中和侧边栏可以显示目录。
- **评论 comments**  
 支持 [多说](http://duoshuo.com/) & [disqus](https://disqus.com/) 评论。
- **分享 jiathis**  
 启用 内建分享工具 或 [加网](http://www.jiathis.com/) 分享系统。
- **网站统计 Analytiscs**  
 支持 [谷歌统计](http://www.google.com/analytics/) & [百度统计](http://tongji.baidu.com/) & [CNZZ站长统计](http://www.cnzz.com/)。
- **Search**  
 支持 [谷歌自定义搜索](https://www.google.com/cse/ ) & [百度站内搜索](http://zn.baidu.com/) 。
 * 注意：在设置百度站内搜索的时候，id号务必打上双引号，否则不能设置成功。
- **totop**  
 回到顶部。
- **rss**  
 RSS 订阅链接。
- **fancybox**  
 图片查看的 [Fancybox](http://fancyapps.com/fancybox/) 工具。

##网站列表
- [Hunter的时光机器](http://www.ihunter.me) - Hunter
- [Jack's Blog](http://wuchong.me) - WuChong

##协议
[MIT](/LICENSE)
