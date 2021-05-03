# hexo主题 bfhui-themes

## 特性 ~~bug~~

1.**轻盈美观** - 使用 Argon Design System 前端框架，细节精致，轻盈美观

2.**高度可定制化** - 可自定义主题色、布局(双栏/单栏/三栏)、顶栏、侧栏、Banner、背景图、日夜间模式不同背景、背景沉浸、浮动操作按钮等，提供了丰富的自定义选项

3.**夜间模式** - 支持日间、夜间、纯黑三种模式，并可以根据时间自动切换或跟随系统夜间模式

4.**功能繁多** - Tag 和分类统计、作者链接、额外链接、文章字数和预计阅读时间、文章过时信息显示

5.**Pjax** - 支持 Pjax 无刷新加载，提高浏览体验

6.**友情链接** - 支持使用 Wordpress 自带的链接管理器进行友链管理，支持多种友链样式

7.**"说说" 功能** - 随时发表想法，并在专门的 "说说" 页面展示，也支持说说和首页文章穿插

8.**评论功能扩展** - Ajax 评论，评论支持 Markdown、验证码、再次编辑、显示 UA、悄悄话模式、回复时邮件通知、查看编辑记录、无限加载等功能

9.**诸多功能** - 文章目录、阅读进度、Mathjax 或 Katex 公式解析、图片放大预览、Pangu.js 文本格式化、平滑滚动等

10.**丰富的短代码** - 支持通过短代码在文章中插入 TODO、标签、警告、提示、折叠区块、Github 信息卡、时间线、隐藏文本、视频等模块

11.**多语言** - 支持中文、英文、俄文等语言

12.**其他** - 自适应、精心优化的文章阅读界面 CSS、可切换衬线/非衬线字体、可自定义 CSS 和 JS、支持使用 CDN 加速静态文件访问、SEO 友好、Banner 打字动画、留言板页面等

## 快速使用

### 如何使用？

### 注意事项

必须安装nodejs的前置

安装过hexo

---

可以下载安装包 目前支持github下载 或者 直接下载

直接下载对于无法访问github或者访问github非常非常困难 就不错

[下载0.0.2版本](https://v3.wmz.link/BFHUI.v.0.0.2.zip)

[Release 0.0.2 · black-fruit/theme-Hexo-BFHUI (github.com)](https://github.com/black-fruit/theme-Hexo-BFHUI/releases/tag/0.0.2)

[github link](https://github.com/black-fruit/theme-Hexo-BFHUI)

#### 更多版本

[0.0.1](https://v3.wmz.link/BFHUI.v.0.0.1.zip)

### 应用到hexo

把此zip压缩包解压

之后把解压缩后的文件夹移动到`你的hexo博客/themes`文件夹

之后

![image-20210503101537963](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/99512_image-20210503101537963.png)

更改他的名字为`bfhui`

然后打开**您的博客根目录**中的**_config.yml**

把其中的theme修改为`bfhui`

![image-20210503101906670](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/66405_image-20210503101906670.png)

#### 本博客主题必须使用的插件

在`cmd`或者`bash`中输入

```bash
npm install hexo-generator-search --save
```



#### 之后enjoy吧（还没有主题设置哦）

图片

![image-20210503102845407](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/54443_image-20210503102845407.png)

![image-20210503102900138](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/91472_image-20210503102900138.png)

![image-20210503102916977](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/15391_image-20210503102916977.png)

## 主题设置

请打开本主题的`_config.yml`

![image-20210503103030979](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/44984_image-20210503103030979.png)

### 设置评论

暂时只支持对`gitalk`的支持（所以快去找作者催更啊）

![image-20210503103208242](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/78247_image-20210503103208242.png)

代码段

|        功能         |  类型  |              作用              |
| :-----------------: | :----: | :----------------------------: |
|       enable        |  bool  |   开启或关闭(true or false)    |
|      githubID       | string |    输入你的github username     |
|        owner        | string |   你的github名字或者组织名字   |
|        repo         | string |     存放issue(评论)的仓库      |
|      adminuser      | string |        admin github名字        |
|      clientID       | string |        在oauth获取的id         |
|    clientSecret     | string |      在oauth获取的Secret       |
| distractionFreemode |  bool  | 分心自由模式（我感觉没什么用） |

client id和client Secret怎么得到呢？

进入**setting**

进入**开发者设置**

进入这里

![image-20210503104516744](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/29780_image-20210503104516744.png)

点击新建

![image-20210503104540808](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/99608_image-20210503104540808.png)

比如这样、

![image-20210503104625321](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/93885_image-20210503104625321.png)

之后就得到了

![image-20210503104702712](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/58336_image-20210503104702712.png)

下边是clietsecret

点击![image-20210503104729100](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/81553_image-20210503104729100.png)就可以新建了

之后每个填上去就ok了

### pangu.js （强迫症的福音）

如果你在看文章的时候english和中文混在一起还有12334的数字 你一定看着很烦

那就用它吧

他会自动把中英文分割

就像这样

`你好 hello wrold 啊`

规格是

![image-20210503105516569](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/45081_image-20210503105516569.png)

|     功能     | 类型 |           作用            |
| :----------: | :--: | :-----------------------: |
| enable_pangu | bool | 是或者否（true or false） |

### lazyload （图片服务器的福音）

为什么呢

当然是

它看到哪里 图片就跟到哪里

有人看一半就走了

但是不用它 全加载了 （服务器流量哭晕在厕所）

规格

![image-20210503110017359](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/53349_image-20210503110017359.png)

|          功能          |    类型     |           作用            |
| :--------------------: | :---------: | :-----------------------: |
|    enable_lazyload     |    bool     | 开启或关闭(true or false) |
|   lazyload_threshold   |     int     |   距离多少像素开始加载    |
|    lazyload_effect     |   string    |       图片显示动画        |
| lazyload_loading_style | int or none |      图片加载的动画       |

### 全局

里面包含

字体设置之类的

规格

![image-20210503111111009](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/89748_image-20210503111111009.png)

|               功能                |      类型      |           作用           |
| :-------------------------------: | :------------: | :----------------------: |
|            theme_color            |     string     |         主题颜色         |
| show_customize_theme_color_picker |      bool      | 允许用户自定义主题主颜色 |
|        darkmode_autoswitch        |     string     |     自动切换夜间模式     |
|        enable_amoled_dark         |      bool      |   false=灰黑 true=暗黑   |
|            card_radius            |      int       |     默认卡片圆角大小     |
|            card_shadow            | string or none |     卡片阴影（影子）     |
|               font                |     string     |           字体           |
|          enable_headroom          |      bool      |  滚动时是否自动折叠顶栏  |
|               none                |      none      |           none           |

#### 字体对比

sans-serif ![image-20210503112337056](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/94220_image-20210503112337056.png)

serif![image-20210503112412961](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/18293_image-20210503112412961.png)

（我感觉还是第一个比较好看👩）

### 顶栏

规格

![image-20210503113603108](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/42737_image-20210503113603108.png)

|       功能        |  类型  |     作用     |
| :---------------: | :----: | :----------: |
|   toolbar_icon    | string |   显示图片   |
| toolbar_icon_link | string | 顶栏图标链接 |
|   toolbar_title   | string |     标题     |

## 高级设置

### 页脚

![image-20210503114905567](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/62508_image-20210503114905567.png)

使用string类型

支持超链接 ico

### 数学公式（没用的东西 滑稽）

![image-20210503115008734](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/99981_image-20210503115008734.png)

建议不要弄 弄完了网站有点卡

### 脚本

![image-20210503115044610](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/60900_image-20210503115044610.png)

众所周知 就是脚本呗

### 代码高亮

![image-20210503115111918](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/70778_image-20210503115111918.png)

第一项开启或者关闭

第二行是主题

### 大图预览

![image-20210503115206501](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/28271_image-20210503115206501.png)

一般默认

### 平滑滚动

![image-20210503115258763](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/94824_image-20210503115245800.png)

### 浮动操作按钮

![image-20210503115332445](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/60845_image-20210503115332445.png)

都是bool值 直接自己设置

### Banner

![image-20210503115459560](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/35917_image-20210503115459560.png)

### 侧栏

![image-20210503115517443](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/52254_image-20210503115517443.png)

![image-20210503115542218](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/56020_image-20210503115542218.png)

### 文章

![image-20210503115612272](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/44133_image-20210503115612272.png)

### 背景

![image-20210503115647809](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/20152_image-20210503115647809.png)

### 其他

![image-20210503115707564](https://gitee.com/wmz1024/pic1/raw/master/img/2021/05/03/21634_image-20210503115707564.png)

## 配置完之后 当然要部署

hexo s 本地

其他的自己百度

---

就没别的了 走吧

