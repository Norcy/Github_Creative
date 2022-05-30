## Github 创意项目

数据来源：[Hello Github](https://github.com/521xueweihan/HelloGitHub) 中挑选，目前数据整理从 38-62 期

## 创意项目列表

+ [Github Profile Page Creator](https://github.com/iamsatyajit05/GitHub-Profile-Page-Creator)：根据你的 Github 名字（无需登录）就能生成对应的 H5 页面，包括简历、徽章、提交数、Star 数、粉丝数等等

+ [bubbletea](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/charmbracelet/bubbletea)：一个强大的 TUI（文本用户界面）框架。Bubble Tea 非常适合构建复杂交互的终端应用程序，同时还能让命令行程序变得多彩和炫酷

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img2/master/hellogithub/62/img/bubbletea.gif' style="max-width:80%; max-height=80%;"></img></p>

+ [AntennaPod](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/AntennaPod/AntennaPod)：一款免费、开源、没有广告的播客应用（Android 和 iOS）。由播客爱好者用爱开发和维护，支持在线播放和音频下载等功能，同时内置数以百万计的免费和付费播客源，从独立播主到大型新闻机构出版社，如 BBC、NPR 和 CNN 应有尽有，也可自行导入播客源

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img2/master/hellogithub/62/img/AntennaPod.png' style="max-width:80%; max-height=80%;"></img></p>

+ [npkill](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/voidcosmos/npkill)：快速查找和轻松删除 node_modules 文件夹的工具。还在为 node_modules 占了很多磁盘空间而烦恼吗？还在手动找用不到的 node_modules 目录吗？快来试试 npkill 吧！轻松地删除 node_modules 目录

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img2/master/hellogithub/61/img/npkill.gif' style="max-width:80%; max-height=80%;"></img></p>

+ [ChatUI](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/alibaba/ChatUI)：专注于对话领域的 UI 开源项目。可以帮助用户快速搭建体验友好的机器人对话界面，特性：
    
    - 最佳实践：基于阿里小蜜业务积累和打磨的对话式交互最佳实践
    - TypeScript：使用 TypeScript 开发，提供完整的类型定义文件
    - 响应式：响应式布局，在无线和 PC 端都可以友好展现
    - 主题：支持灵活的样式定制，以满足业务和品牌上多样化的视觉需求
    - 国际化：支持多语言和本土化特性

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img2/master/hellogithub/60/img/ChatUI.jpeg' style="max-width:80%; max-height=80%;"></img></p>

+ [video_spider](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/5ime/video_spider)：视频去水印工具。原理很简单就是根据输入的视频的地址，返回原平台无水印的视频源地址。目前支持 15 个视频平台，[在线尝试](https://lab.5ime.cn/video/)

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img2/master/hellogithub/60/img/video_spider.png' style="max-width:80%; max-height=80%;"></img></p>


+ [requests-html](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/psf/requests-html)：好用的 Python 解析 HTML 库。写爬虫的小伙伴都感受过解析 HTML 的痛苦，常用工具 BeautifulSoup、lxml、Scrapy 的 selector 等。今天你有了新的选择 requests-html，支持 XPath、CSS 选择器、动态页面、过滤指定内容等。上手特别简单和迅速，我的爬虫项目 [Hydra](https://github.com/HelloGitHub-Team/Hydra) 中就用了它，解析 HTML 变得轻松了许多。下面是我觉得好用的函数示例：

    ```python
    # 找出元素下的所有链接
    about.absolute_links
    {'http://brochure.getpython.info/', 'https://www.python.org/about/quotes/', 'https://www.python.org/about/help/'}
    # 匹配内容
    >>> r.html.search('Python is a {} language')[0]
    programming
    # 直接提取属性的值
    >>> about.attrs
    {'id': 'about', 'class': ('tier-1', 'element-1'), 'aria-haspopup': 'true'}
    # 呈现加载 JS 后的动态内容
    r.html.render()
    ```


+ [alive-progress](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/rsalmei/alive-progress)：新！Python 炫酷进度条项目。支持 Python2.7-3.8 示例代码：

    ```python
    # 安装：pip install alive-progress
    from alive_progress import alive_bar

    with alive_bar(total) as bar:  # declare your expected total
        for item in items:         # iterate as usual over your items
            ...                    # process each item
            bar()                  # call after consuming one item
    ```

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img2/master/hellogithub/59/img/alive-progress.gif' style="max-width:80%; max-height=80%;"></img></p>


+ [python-cheatsheet](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/gto76/python-cheatsheet)：全面且实用的 Python 备忘录。这个东西特别适合我这个上了年纪的人，比如：忘记怎么用 Python 写正则、要搞个进度条忘记库的名字和基本用法、用 pandas 处理数据忘记方法需要的参数等等。正当我觉得自己需要“回炉重学”的时候发现了这个项目，有了它上面的问题都可以找到拿来即用的代码片段。

+ [ZY-Player](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/cuiocean/ZY-Player)：免费无广告、高颜值+多平台的桌面视频资源播放器。功能如下：
- 全平台支持 Windows、Mac、Linux
- 视频源支持自定义, 支持导入/导出
- 播放历史, 自动跳转历史进度
- 支持精简模式, 摸鱼划水
- 显示豆瓣评分

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img2/master/hellogithub/55/img/ZY-Player.png' style="max-width:80%; max-height=80%;"></img></p>

+ [tabler-icons](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/tabler/tabler-icons)：一组免费开源的图标。目前共有 850+ 个图标，我觉得都挺好看的，您觉得呢？

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img2/master/hellogithub/55/img/tabler-icons.png' style="max-width:80%; max-height=80%;"></img></p>

+ [socialify](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/wei/socialify)：一键自动生成 GitHub 仓库头图。很多 GitHub 开源项目的作者不会用 PS，想要制作一张项目推广图就很困难，Socialify 就是帮你解决这个头疼的问题。[在线尝试](https://socialify.git.ci/)

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img2/master/hellogithub/55/img/socialify.png' style="max-width:80%; max-height=80%;"></img></p>

+ [IconPark](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/bytedance/IconPark)：该开源库提供了 1200+ 高质量图标，还有一个界面便于定制图标。强大之处是可以通过改变一个 SVG 文件的属性来变换出多种主题，支持导出 SVG、PNG、Vue 和 React 图标组件等。极大的方便了设计师和开发者，让他们有更多时间逛 HG 了

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img2/master/hellogithub/54/img/IconPark.gif' style="max-width:80%; max-height=80%;"></img></p>

+ [papercss](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/papercss/papercss)：手绘风格的 CSS 库

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img2/master/hellogithub/53/img/papercss.png' style="max-width:80%; max-height=80%;"></img></p>

+ [jizhi](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/unicar9/jizhi)：中国风新标签页的 Chrome/Firefox 插件。它将在新标签页上展示中国传统色的层叠波浪动画效果，搭配经典诗词

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img2/master/hellogithub/53/img/jizhi.gif' style="max-width:80%; max-height=80%;"></img></p>


+ [avataaars-generator](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/fangpenlin/avataaars-generator)：基于 React 实现的卡通头像生成工具。[在线尝试](https://getavataaars.com/)

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/50/img/avataaars-generator.png' style="max-width:80%; max-height=80%;"></img></p>

+ [SpinKit](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/tobiasahlin/SpinKit)：纯 CSS 实现加载动画的项目

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/49/img/SpinKit.gif' style="max-width:80%; max-height=80%;"></img></p>

+ [word_cloud](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/amueller/word_cloud)：Python 的词云生成工具。示例代码：

    ```python
    # 加载内容
    text = open(path.join(d, 'constitution.txt')).read()
    # 生成词云图片
    wordcloud = WordCloud().generate(text)
    # 展示生成的图片
    image = wordcloud.to_image()
    image.show()
    ```

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/46/img/word_cloud.png' style="max-width:80%; max-height=80%;"></img></p>

+ [iptv](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/iptv-org/iptv)：全球各地 8 千多个公开、可用的网络电视频道集合。随着网络的日益发展，电视节目离我们越来越远。不用电视盒子，不用下载电视软件，直接使用流媒体软件看网络电视是一个不错的选择。操作步骤:
- 打开任何支持流媒体协议的播放器
- 然后粘贴流媒体地址：https://iptv-org.github.io/iptv/index.m3u
- 播放器推荐：IINA（Mac）、VLC（Linux）、Potplayer（Windows）

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/46/img/iptv.png' style="max-width:80%; max-height=80%;"></img></p>

+ [formily](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/alibaba/formily)：一款面向企业级复杂场景的高性能表单解决方案。特性：
- 🚀 高性能，字段分布式渲染，大大减轻 React 渲染压力
- 💡 支持 Ant Design/Fusion Next 组件体系
- 🎨 JSX 标签化写法/JSON Schema 数据驱动方案无缝迁移过渡
- 🏅 副作用逻辑独立管理，涵盖各种复杂联动校验逻辑
- 🌯 支持各种表单复杂布局方案

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/45/img/uform.png' style="max-width:80%; max-height=80%;"></img></p>

+ [DoraemonKit](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/didi/DoraemonKit)：一款功能齐全的 iOS 、Android、微信小程序客户端研发助手。它功能强大、接入方便、便于扩展，能够让每一个 App 快速接入一些常用的辅助开发工具、测试效率工具、视觉辅助工具，而且能够完美在 Doraemon 面板中接入一些定制的辅助工具

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/44/img/DoraemonKit.png' style="max-width:80%; max-height=80%;"></img></p>

+ [scrcpy](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/Genymobile/scrcpy)：一款可以用电脑显示并控制 Android 手机的开源工具。连接方便使用方便，手机无需 root、无需安装任何应用。支持 USB、Wi-Fi 两种方式连接，支持 Windows、macOS、Linux 三种操作系统。注意电脑端需要安装 adb 工具

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/44/img/scrcpy.jpg' style="max-width:80%; max-height=80%;"></img></p>

+ [qier-player](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/vortesnail/qier-player)：一款基于 React 的轻量级在线视频播放器组件，界面简洁、操作流畅具有视频播放器的基础功能。方便你在项目中轻松添加播放器组件，实现视频播放功能。如果你嫌原生 video 功能太少、操作太傻、界面太简陋，那这个播放器就是你的菜。你还能够通过阅读源码学习到关于生命周期执行顺序、父子组件传值的方式、以及如何利用定时器进行一些实时的状态更新的技巧。示例代码：

    ```javascript
    import React from 'react';
    import ReactDOM from 'react-dom';
    import QierPlayer from 'qier-player';

    ReactDOM.render(<QierPlayer srcOrigin="你的视频地址"/>, document.getElementById('root'));
    ```

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/44/img/qier-player.png' style="max-width:80%; max-height=80%;"></img></p>

+ [pacgo](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/danicat/pacgo)：基于 Go 实现的终端吃豆人游戏

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/43/img/pacgo.jpg' style="max-width:80%; max-height=80%;"></img></p>

+ [chart-race-react](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/bchao1/chart-race-react)：一个简单易用的 Bar Chart Race（长条图赛跑动画） React 组件。示例代码：

    ```javascript
    import ReactDOM from 'react-dom';
    import BarChart from 'chart-race-react';

    ReactDOM.render(<BarChart />, document.getElementById('root'));
    ```

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/43/img/chart-race-react.gif' style="max-width:80%; max-height=80%;"></img></p>

+ [Administrative-divisions-of-China](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/modood/Administrative-divisions-of-China)：中国行政区划（五级）：省级、地级、县级、乡级和村级的数据集和爬虫程序

+ [starcharts](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/caarlos0/starcharts)：生成 GitHub 星图的项目

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/42/img/starcharts.png' style="max-width:80%; max-height=80%;"></img></p>

+ [navi](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/denisidoro/navi)：命令行辅助工具，有了它再也不用担心找不到历史输入过的命令、忘记命令等诸多烦恼

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/42/img/navi.gif' style="max-width:80%; max-height=80%;"></img></p>

+ [chart.xkcd](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/timqian/chart.xkcd)：手绘风格的 JS 图表库。手绘风格的设计给人一种很可爱的感觉，看了这些图表你会发现数据也可以以萌萌哒的形式展示

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/41/img/chart.xkcd.gif' style="max-width:80%; max-height=80%;"></img></p>

+ [fullPage.js](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/alvarotrigo/fullPage.js)：通过调用 fullPage 可轻易创建全屏滚动网站（也称为单页网站）。 fullPage 可创建全屏滚动网站，同时也可在网站中添加横向滚动条。适合快速搭建全屏滚动或者拥有视觉差的站点，使得网站看上去更加高端、大气、上档次，示例代码：

    ```javascript
    <div id="fullpage">
      <div class="section">Some section</div>
      <div class="section">Some section</div>
      <div class="section">Some section</div>
      <div class="section">Some section</div>
    </div>
    ```

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/41/img/fullPage.png' style="max-width:80%; max-height=80%;"></img></p>

+ [overcommit](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/sds/overcommit)：一款可配置的 git hook 管理工具。git hook 是 git 的强大功能，当触发某一个 git 的事件，例如：add、commit、push 等操作时，会触发执行对应事件的附加操作（hook）。可以用来检测代码质量、commit 描述风格、控制代码质量等。overcommit 就是能让你不写一行代码（配置不算代码），来自定义 hook 要执行的操作。它使用简单、文档详尽、例子众多、社区活跃，值得一试

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/41/img/overcommit.png' style="max-width:80%; max-height=80%;"></img></p>

+ [git-tips](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/521xueweihan/git-tips)：Git 常用命令集合

+ [git-open](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/paulirish/git-open)：用 git 命令 push 完代码，想看仓库网页内容是否更新成功还需要再去打开网页查看。有了这个项目，直接输入 git open 命令浏览器就能自动打开对应的仓库的网页，支持 GitHub、GitLab、Bitbucket。是不是很方便？还等什么快去试试

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/40/img/git-open.gif' style="max-width:80%; max-height=80%;"></img></p>

+ [getAwayBSG](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/Jinnrry/getAwayBSG)：项目名为“逃离北上广”，该项目通过爬取的招聘和房价数据。给准备逃离北上广等一线城市，却又找不到去处的 IT 人士提供了一些可视化数据作为建议

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/40/img/getAwayBSG.png' style="max-width:80%; max-height=80%;"></img></p>

+ [olivia](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/olivia-ai/olivia)：一个类似 Siri 的开源语音助手，目前只支持英文。开源的语音助手并不多，而且涉及的问题很复杂，现在有了它就可以基于这个项目做一些有趣的小应用

<p align="center"><img src='https://raw.githubusercontent.com/521xueweihan/img/master/hellogithub/39/img/olivia.png' style="max-width:80%; max-height=80%;"></img></p>


+ [you-get](https://hellogithub.com/periodical/statistics/click/?target=https://github.com/soimort/you-get)：一个 Python 写的视频下载工具，下载工具千万个但我仅仅推荐了这个工具。是因为正常情况下载不了视频的网站，用它你就可以方便地下载下来。剩下的要自己去看介绍，不能再多说了🙊
    
    ```sh
    (env) ➜  ~ you-get 'https://v.ifeng.com/c/7msWmwppMPC'
    Site:       ifeng.com
    Title:      完整版第五期：陈晓卿 中国有俩行当门槛极低——美食圈和摄影圈
    Type:       MPEG-4 video (video/mp4)
    Size:       0.01 MiB (8578 Bytes)

    Downloading 完整版第五期：陈晓卿 中国有俩行当门槛极低——美食圈和摄影圈.mp4
     100% (  0.0/  0.0MB) ├████████████████████┤[1/1]   71 kB/s

    ```
