# [首页查询更多项目](https://github.com/GraduationProject-weixin) 包安装运行


# 50447wxapp“口腔助手”的设计与实现_1171u小程序

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV1NvtMeFEiw?p=107)


# 绪  论
## 1.1课题背景
“口腔助手”小程序主要通过计算机网络，对“口腔助手”小程序所需的信息进行统一管理，方便用户随时随地进行增添、修改、查询、删除各类信息。本系统极大的促进了系统与数据库管理系统软件之间的配合，满足了绝大部分用户的需求，给用户带来了很大的便利。以现在计算机的技术的应用，使计算机成为人们使用现代发达技术的桥梁。计算机可以有效的解决信息，十分方便的获取信息，从而提高工作的效率。
## 1.2 课题目的及意义
随着信息化管理技术不断发展，传统的“口腔助手”管理已经无法适应，效率与预期相差甚远，因此需要开发一套操作方便，效率较高的“口腔助手”小程序。当前，21新世纪，人们已经进入了信息时代，人们获取信息的方式大大增加，摆脱了传统的报纸、电视、广播等媒体，而是从各种网络、自媒体平台上获取信息，这就导致日常生活中产生的数据信息十分巨大，尤其是对于“口腔助手”管理，更需要大量的信息。本系统能为用户提供一个“口腔助手”小程序，就能够快速有效的帮助用户获得对方想要的信息，并且可以让管理员能够轻松效率地浏览所有的信息。系统开发的意义主要在于两个方面，一方面，系统上线后，能够为“口腔助手”管理带来很大便利，“口腔助手”管理涉及的数据量较大，要求精度高，采用计算机系统能够很好满足此需求，并且随着目前电脑、手机的普及，方便用户的使用。另一方面，通过自己动手操作设计系统，不仅可以提升自己的学习兴趣，也是在进入社会之前的一次很好的锻炼机会[6]。
## 1.3课题研究现状
其实，相关的研究在国外已经开展了很多年了，将“口腔助手”与信息技术相融合的理念在欧美等发达国家的“口腔助手”建设中很受欢迎 美国开放的Ravel平台，能够在手机上实现远程“口腔助手”信息管理等功能，并且可以实现可视化的详细的过程展示、在线测试、在线评价等，极大的丰富了线上“口腔助手”管理模式。2015年2月，国王学园正式提出了在线信息管理的制度设想[5]，希望通过互联网技术保障实现信息管理。但现如今，也有许多国外学者提出，信息化时代带来的乱象越来越多，日益增长的在线管理平台让人应接不暇，需一场数字化的现代化的转型，建立可靠的“口腔助手”小程序，实现数字管理。

随着人流量不断的增加，越来越多的人们开始加入了“口腔助手”行业的大潮中，但是我国“口腔助手”小程序信息管理效果低下，而且出错率也很高。因此大家迫切需要一款更加专业化的“口腔助手”小程序[3]。

随着“口腔助手”小程序的不断出现，用户需求不断增多，“口腔助手”小程序也不断的得到壮大。该系统主要是满足多方面的需求的实际需要，方便用户利用互联网实现对“口腔助手”的了解、对比，同时让管理者可以通过这个系统对用户实际需求以及各“口腔助手”信息的所有了解进行操作。设计该系统主要目的是为了方便用户可以有一个非常好的“口腔助手”管理平台，管理员也可以通过该系统进行更加方便的管理操作[4]。
## 1.4 论文主要工作内容
本文设计并实现了一个“口腔助手”小程序，主要包括以下具体工作内容：

（1）参考国内外相关系统开展了系统的需求分析，明确了系统首页，个人中心，医生管理，用户管理，预约信息管理，口腔历史管理，用户反馈管理，在线问诊管理，保健知识管理，系统管理等主要功能需求。

（2）设计系统技术方案，采用JAVA语言，选用MySQL数据库、SpringBoot框架来设计并实现本系统。

（3）具体介绍了各个功能模块的设计与实现。

（4）对系统的系统首页，个人中心，医生管理，用户管理，预约信息管理，口腔历史管理，用户反馈管理，在线问诊管理，保健知识管理，系统管理等功能进行了全面的测试。


62

![](/md/blog.004.png)![](/md/blog.005.png)
# 2 系统关键技术
## 2.1微信小程序
### 2.1.1微信小程序的介绍
微信小程序是由张小龙研发且于2017年1月9日正式推出的一种不用下载的就可以使用的轻量应用，而且用完之后也不需要卸载，实现了用完即走的原则，因此小程序的传播消耗和获取用户的成本在一定程度上被大大地降低了。这为用户与服务的连接开辟了一种新的方式。对于微信小程序更直接的理解，就是可以分解为微信和小程序，由此不难理解，即微信小程序的开发环境就是微信，因此在微信中用户可以通过线下二维码扫一扫或者扫公众号中关联的二维码打开小程序应用，或者用户还可以通过搜索小程序打开应用。微信小程序最重要也是最有优势的一点就是其占用的空间非常小，因此用户从获取小程序到进入该小程序消耗的时间很少，大大的提升了用户的使用体验。
### 2.1.2微信小程序框架概述
(1) 逻辑层

逻辑层就是微信小程序中所有.js文件的集合，在逻辑层小程序会给视图层发送处理好的数据，同时视图层将时间请求反馈回来给逻辑层。其中微信团队进行了一系列的优化，例如通过使用app的方法来作为小程序的入口，对页面还使用了page的方法来未作页面的入口。同时还陆陆续续的提供了许多多功能的API接口，这个对于开发者来说是非常便利的，同时微信团队还将页面的作用域进行独立化，这样使得页面具有了模块化的功能，可以管理小程序的生命周期，实现数据和事件的分发等功能。但是逻辑层中比较特殊的一点就是在逻辑层中的js代码并不是在浏览器中运行的，因此js在web中不具有dom、window等一部分能力，所以在平时的开发过程中我们要注意这些点。

(2) 视图层

.wxml文件和.wxss文件的集合就是组成了微信小程序的视图层，其中在.wxml文件中实现页面结构的搭建，包括元素组成、数据的显示、事件的绑定等。视图层的页面是通过bind绑定的，同时也支持冒泡事件的绑定，但这个还是有区别于HTML的on的。而.wxss文件则完成页面结构和数据的显示样式，而数据的显示又是以小程序的基本单位组件(component)来展示的，特别的是为了适配各式的设备屏幕，微信小程序还新增了一个尺寸单位rpx，通过使用这个单位来进行页面的布局，很好的实现各种设备不同屏幕下的页面的自适应显示，大大提高了开发者的工作效率。

数据层中可以缓存临时数据，本地存储，可以存储或者调用网络。首页数据层中通过setData()函数将数据传递给视图层以达到数据改变驱动页面的改变的目的，在 开发过程中切忌频繁使用setData()，否会出现页面卡顿或数据未更新的情况。同时微信小程序还为本地的存储提供了一些比较成熟的API接口，例如设置缓存数据的本地存储wx.setStorage，获取缓存数据的API接口wx.getStorage以及清除缓存数据的接口wx.clearStorage。而网络的存储和调用的实现也可以通过一些成熟的API来实现，例如上传文件接口wx.uploadFile,与其对应的下载文件接口wx.downloadFile和最常用的网络请求的接口wx.request。在平时的微信页面跳转中则是一些网络的调用，包括页面的跳转wx.navigateTo，该方法除了不能跳转至tabBar页面以外其他的都可以跳转，且还可以返回原来的页面。
## 2.2 MySQL数据库
数据库系统是一个进行数据存储的系统，数据库就是这个系统的库，用来存放通过系统的数据，数据库在开发人员的日常生活中，占据了很大的地位。因为使用数据可以使自己系统存储数据更加方便、快捷[14]。 

MySQL之所以受到广大开发人员的欢迎，主要原因使因为数据库的使用是免费的。最开始的数据库研发出后，是需要收费的，但是随着MySQL的出现和不断更新，越来越多的用户去使用这款软件[15]。首先它是开源且免费的，这样大大减少了开发的成本；第二MySQL可以在多个平台上使用，在MAC、Windows和Linux上都可以使用。其次它的性能也是十分强大的，性价比极高。最后，MySQL相比其他数据库语言来说，更加简单易于上手；可以与很多平台搭建联系，比如本文使用的Java [16] 。
## 2.3 B/S结构
B/S架构，也就是浏览器/Server (Browser/Server)，是在因特网技术发展过程中， C/S架构的一种改变和完善。采用该架构，可以充分利用 WWW的浏览器来完成用户接口，而在前端完成交易的部分业务，而服务端则完成了交易的基本功能。这就构成了3- tier的构造。B/S体系架构，采用了日益完善的 WWW技术，将各种 Script、 VBScript、 JavaScript、 ActiveX等技术相融合，通过一款普通的网络浏览器，既可以完成一些复杂的特定程序，又可以节省大量的资源，又可以节省大量的资源。由于视窗98/2000把浏览器技术移植到了操作系统中，所以这个架构现在已经是目前最受欢迎的应用程序架构了。

B/S架构，也就是浏览/伺服器（Browser/Server）架构，是指仅有一个伺服器（Server）被安装，而客户机则使用浏览（Browse）来执行该软件。这是因特网技术出现后， C/S架构的一种改变与完善。它充分运用日益完善的 WWW技术，并将各种 Script、 JavaScript、 ActiveX等 Script技术相融合，形成了一个崭新的体系结构技术。
## 2.4 SpringBoot框架
Spring Boot是由Pivotal的开发团队在2013年开发的一个免费、轻量级、开源的系统框架。SpringBoot的主要设计思想是约定大于配置，因此SpringBoot在设计时几乎达到零配置。SpringBoot集成了业界的开源框架。

SpringBoot是一个非常强大的后台框架，因为SpringBoot的开发基本上不需要写配置文件，所以利用SpringBoot来构建网站的后台环境，在SpringBoot的YML配置文件中写项目启动端口，项目就可以启动了。项目的Java和静态文件由SpringBoot管理。


# 3 系统分析
## 3.1 可行性分析
“口腔助手”小程序主要目标是实现网上的相关信息管理服务。在确定了目标后，我们从以下四方面对能否实现本系统目标进行可行性分析。
### 3.1.1 技术可行性
技术上的可操作性是项目建设顺利进行的一个关键因素，技术措施必须达到要求，方能使项目顺利进行。该方案使用了开放源码的代码，并使用Java等技术，对软件的设计具有适度的困难和对电脑的硬件需求。所有的语言都很容易使用。该项目具有技术上的可行性。
### 3.1.2 操作可行性
当今社会，电脑已经是耳熟能详的存在了，绝大部分用户都可以通过电脑轻松操作本系统。由此可知，我们的管理系统对于绝大部分用户来说，操作是完全可行的，并不存在操作上的盲区。
### 3.1.3 经济可行性
本系统所需要用到的所以的工具都是开源，不收费的，并且本系统因为不具有太过于复杂的结构，用户维护系统的费用也不高。所以，本系统的经济可行性是可行的。
### 3.1.4 法律可行性
此“口腔助手”小程序是自己设计的管理系统，具有很大的实际意义。因为无论是软件还是数据库，采用的都是开源代码，因此这个系统的开发和设计，并不存在侵权等问题，在法律上完全具有可行性。

综上所述，“口腔助手”小程序在技术、经济、操作和法律上都具有很高的可行性，开发此程序是可行的。
## 3.2 系统性能分析
### 3.2.1 系统安全性
“口腔助手”小程序必须由领导机构严格执行。具体要求如下：

（1）如果要使用“口腔助手”小程序，必须先注册才能进行登录。未获许可的使用者，不可以任意的方法，进入或浏览系统资讯及资料，因而本系统将会得到保护。

（2）在不同司法管辖区的具体实施。使用其他权限登录时，无法跳过此操作。

（3）如果专门应用，该系统将包含许多必须保密的数据和信息。该系统存在系统漏洞，发布此信息将给客户造成重大损失。因此，我们充分保证了该规则和系统的发展趋势。
### 3.2.2 数据完整性
（1）必须对所有的数据进行详尽的记载，而该信息的内容不得为空白。

（2）各种资料的关联一定要恰当。

（3）在不同的档案中，同一资料资讯应该互相相符。
## 3.3 系统功能分析
“口腔助手”小程序主要有管理员，医生和用户三个功能模块。以下将对这三个功能的作用进行详细的剖析。

管理员模块：管理员是系统中的核心用户，管理员登录后，可以对后台系统进行管理。主要功能有：系统首页，个人中心，医生管理，用户管理，预约信息管理，口腔历史管理，用户反馈管理，在线问诊管理，保健知识管理，系统管理等功能。管理员用例如图3-1所示。

![](/md/blog.006.png)

图3-1 管理员用例图

用户：用户进入系统可以实现对首页，医生，保健知识，我的页面进行操作，点击我的页面可以进行预约信息，口腔历史，用户反馈，在线问诊详细操作；用户用例如图3-2所示。

![](/md/blog.007.png)

图3-2 用户用例图

医生：医生进入系统可以实现对首页，医生，保健知识，我的页面进行操作，点击我的页面可以进行预约信息，口腔历史，用户反馈，在线问诊详细操作；医生用例如图3-3所示。

![](/md/blog.008.png)

图3-3 医生用例图

## 3.4 系统流程分析
### 3.4.1 数据开发流程
“口腔助手”小程序开发时，首先对此系统进行需求分析，进而对系统进行模块、编码等详细设计总体的设计规划，设计系统功能模块，数据库的选择等，本系统的开发流程如图3-4所示

![](/md/blog.009.png)

图3-4系统开发流程图
### 3.4.2 用户登录流程
要想利用这个软件来进行系统的安全管理，首先需要登录到该软件中。如图3-5所示。

![](/md/blog.010.png)

图3-5 登录流程图

### 3.4.3 系统操作流程
用户登录系统时需要输入正确的用户名和密码，数据库在进行匹配核实后匹配结果正确才能进入系统，若错误则提示用户名或密码错误，即无法登录。操作流程如图3-6所示。

![](/md/blog.011.png)

图3-6 系统操作流程图

### 3.4.4 添加信息流程
管理员可以添加信息，用户添加可以自己权限内的信息，输入信息后，要想利用这个软件来进行系统的安全管理，首先需要登录到该软件中。添加信息流程如图3-7所示。

![](/md/blog.012.png)

图3-7 添加信息流程图

### 3.4.5 修改信息流程
管理员可以修改“口腔助手”管理信息，用户可以修改自己权限内的信息，首先进入修改信息界面，输入需要修改信息，在系统进行判定为正确和合规后修改成功，并将数据更新至数据库。信息不合法则修改失败，重新输入。修改信息流程图如图3-8所示。

![](/md/blog.013.png)

图3-8 修改信息流程图

### 3.4.6 删除信息流程
管理员可以删除“口腔助手”管理信息，点击删除按钮，系统会提示是否删除信息，点击确定，则信息被删除，数据库中的信息随之删除，删除信息流程图如图3-9所示。

![](/md/blog.014.png)

图3-9 删除信息流程图



# 4 系统设计
## 4.1 系统概要
在对该方法进行了系统的解析之后，进行了一个包括了整体和细节的记性系统的设计。整体的设计仅仅是一个整体的方案，通过整体的方案，我们可以将整个体系中的某些部分分割开来，比如文件，文档，数据等等。经过整体的规划，我们可以将这些软件的各个部分，都分成了不同的部分。不过这仅仅是一种初步的分类，并未实际实施。

总体来说，这是一个初步的方案，也是一个工程。我们可以进行多种方案的综合，在比较中，从性能、成本、效益三方面进行比较，最后得出最佳的产品，选用好的总体设计能够减少成本，提高企业效益，从这一点来讲，整体设计非常重要的。

“口腔助手”小程序工作原理图如图4-1所示：

![](/md/blog.015.png)

图4-1 系统工作原理图

## 4.2 系统结构设计
构图是系统的体系结构，体系结构是体系结构体系的重要组成部分。“口腔助手”小程序的总体结构设计如图4-2所示。

![](/md/blog.016.png)

图4-2 系统总体架构图
## 4.3 数据库设计
在电脑资讯系统中，以资料库为基础。当前计算机体系中最重要的是数据库。数据库的发展好坏，直接关系到整个系统的性能与运行效率。
### 4.3.1 数据库设计原则
利用 ER模式进行数据库的概念结构设计。E-R模型法的组成元素有：实体、属性、联系，E-R模型用E-R图表示，是一个关于工作环境中的事件的信息，而一个属性是关于物理特征的说明。在系统的设计过程中，资料库发挥了关键作用。下面设计出这几个关键实体的实体—关系图。
### 4.3.2 数据库实体
本系统的实体属性图如下图所示：

1、用户实体图如图4-3所示：

![](/md/blog.017.png)

图4-3用户实体图

2、关于我们实体图如图4-4所示：

![](/md/blog.018.png)

图4-4关于我们实体图

3、医疗公告实体图如图4-5所示：

![](/md/blog.019.png)

图4-5医疗公告实体图

4、保健知识评论表实体图如图4-6所示：

![](/md/blog.020.png)

图4-6保健知识评论表实体图

5、保健知识实体图如图4-7所示：

![](/md/blog.021.png)

图4-7保健知识实体图

### 4.3.3 数据库表设计
“口腔助手”小程序有一个内部数据库。对于数据库系统设计一般基于对我国现有企业数据库系统进行优化管理的操作系统。通常广泛采用的企业数据库资源管理软件系统主要类型包括MySQLserver、MySQL、oracle等。该管理系统主要采用了MySQL大型数据库资源管理软件。

下表将详细列出“口腔助手”小程序的数据库中所有列表。每一份量表的设计成果列出数据库的表信息属于设计的一部分，下面介绍数据库中的各个表的详细信息。

表4-1：用户

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yonghuming|varchar|200|用户名|||
|xingming|varchar|200|姓名|||
|mima|varchar|200|密码|||
|xingbie|varchar|200|性别|||
|lianxidianhua|varchar|200|联系电话|||
|shenfenzheng|varchar|200|身份证|||
|touxiang|longtext|4294967295|头像|||

表4-2：关于我们

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|subtitle|varchar|200|副标题|||
|content|longtext|4294967295|内容|||
|picture1|longtext|4294967295|图片1|||
|picture2|longtext|4294967295|图片2|||
|picture3|longtext|4294967295|图片3|||

表4-3：医生

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yishenggonghao|varchar|200|医生工号|||
|yishengxingming|varchar|200|医生姓名|||
|mima|varchar|200|密码|||
|shanzhanglingyu|varchar|200|擅长领域|||
|zhicheng|varchar|200|职称|||
|xingbie|varchar|200|性别|||
|yiling|varchar|200|医龄|||
|lianxidianhua|varchar|200|联系电话|||
|touxiang|longtext|4294967295|头像|||
|suoshuyiyuan|varchar|200|所属医院|||

表4-4：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-5：token表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|userid|bigint||用户id|||
|username|varchar|100|用户名|||
|tablename|varchar|100|表名|||
|role|varchar|100|角色|||
|token|varchar|200|密码|||
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|
|expiratedtime|timestamp||过期时间||CURRENT\_TIMESTAMP|

表4-6：收藏表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|userid|bigint||用户id|||
|refid|bigint||商品id|||
|tablename|varchar|200|表名|||
|name|varchar|200|名称|||
|picture|longtext|4294967295|图片|||
|type|varchar|200|类型(1:收藏,21:赞,22:踩,31:竞拍参与,41:关注)||1|
|inteltype|varchar|200|推荐类型|||
|remark|varchar|200|备注|||

表4-7：在线问诊

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yishenggonghao|varchar|200|医生工号|||
|yishengxingming|varchar|200|医生姓名|||
|yonghuming|varchar|200|用户名|||
|xingming|varchar|200|姓名|||
|lianxidianhua|varchar|200|联系电话|||
|wenzhenshijian|datetime||问诊时间|||
|zhengzhuangmiaoshu|longtext|4294967295|症状描述|||
|shhf|longtext|4294967295|回复内容|||

表4-8：医疗公告

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|introduction|longtext|4294967295|简介|||
|picture|longtext|4294967295|图片|||
|content|longtext|4294967295|内容|||

表4-9：口腔历史

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|bianhao|varchar|200|编号|||
|yonghuming|varchar|200|用户名|||
|xingming|varchar|200|姓名|||
|yaominshi|varchar|200|药敏史|||
|zhengzhuang|longtext|4294967295|症状|||
|zhiliaoqingkuang|longtext|4294967295|治疗情况|||
|riqi|date||日期|||
|yaodan|longtext|4294967295|药单|||

表4-10：保健知识评论表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|refid|bigint||关联表id|||
|userid|bigint||用户id|||
|avatarurl|longtext|4294967295|头像|||
|nickname|varchar|200|用户名|||
|content|longtext|4294967295|评论内容|||
|reply|longtext|4294967295|回复内容|||

表4-11：预约信息

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|guahaobianhao|varchar|200|挂号编号|||
|yishenggonghao|varchar|200|医生工号|||
|yishengxingming|varchar|200|医生姓名|||
|suoshuyiyuan|varchar|200|所属医院|||
|yuyueriqi|date||预约日期|||
|yuyuedidian|varchar|200|预约地点|||
|shijianduan|varchar|200|时间段|||
|yonghuming|varchar|200|用户名|||
|xingming|varchar|200|姓名|||
|lianxidianhua|varchar|200|联系电话|||
|sfsh|varchar|200|是否审核||待审核|
|shhf|longtext|4294967295|审核回复|||

表4-12：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-13：用户反馈

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yishenggonghao|varchar|200|医生工号|||
|yishengxingming|varchar|200|医生姓名|||
|yonghuming|varchar|200|用户名|||
|xingming|varchar|200|姓名|||
|lianxidianhua|varchar|200|联系电话|||
|wentimiaoshu|longtext|4294967295|问题描述|||
|fankuishijian|datetime||反馈时间|||
|shhf|longtext|4294967295|回复内容|||

表4-14：保健知识

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|biaotimingcheng|varchar|200|标题名称|||
|wenzhangtupian|longtext|4294967295|文章图片|||
|zhishishipin|longtext|4294967295|知识视频|||
|faburiqi|datetime||发布日期|||
|zhishineirong|longtext|4294967295|知识内容|||
|thumbsupnum|int||赞||0|
|crazilynum|int||踩||0|

## 4.4 系统时序图
对于系统设计的详细描述主要采用了时序图的方式，时序图描述了对象之间传递消息的时间顺序, 用来表示用例中的行为顺序, 是强调消息时间顺序的交互图; 时序图描述的事物: 时序图描述系统中类和类之间的交互, 将这些交互建模成消息交换, 时序图描述了类以及类之间的交换以完成的期望行为的消息, 时序图中每条消息都代表了类的一个操作或者引起状态机改变的触发事件。
### 4.4.1 注册时序图
注册时序图，如图4-8所示。

![](/md/blog.022.png)

图4-8注册时序图

### 4.4.2 登录时序图
登录时序图如图4-9所示。

![](/md/blog.023.png)

图4-9 登录时序图

### 4.4.3 管理员修改用户信息时序图
管理员修改用户信息时序图如图4-10所示。

![](/md/blog.024.png)

图4-10 管理员修改用户信息时序图
### 4.4.4 管理员管理系统信息时序图
管理员管理系统信息时序图如图4-11所示。

![](/md/blog.025.png)

图4-11管理员管理系统信息时序图



# 5 系统的实现
## 5.1 基本任务
该系统的实施方式是指能精确地描绘要实施的对象，以便后续的代码可以按照系统的实际情况用编程的方式来写相应的软件。

系统实现的基本任务如下：

（1）模块的数据结构进行设计，在之前的需求分析、概要设计中更加明确地界定更加含糊的资料类型。

（2）更加精确地对每个模板进行了更加细致的算法设计，并对每个组件的处理过程进行了算法的说明。

（3）执行实体化的资料库。

（4）其他设计：有时候，还要考虑到系统的不同，如：输入/输出格式设计、代码设计、人机对话设计等。

（5）对系统的说明书进行编写。

（6）评审：审查程序中的规则和数据库的实体构造。

系统结构可分为具有三个不同功能的包的java源代码、系统的数据库文件、界面代码。java源代码中三个不同包分别为控制、逻辑、缩写层，分别控制也不同的程序具有不同的性质。有了他们就能对系统的数据进行增删改查，完成界面的显示和数据统计，产生随机数和属性文件的读取。定时器类、翻页工具类等，包含了日期转换、字符串处理、获取编译环境等信息。这些类极大地方便了Java编程，日常开发中，经常要用来这些类。
## 5.2小程序前台首页界面实现
当人们打开微信小程序后，首先看到的就是首页界面。在这里，人们能够看到微信小程序的导航条，用户可以根据导航条进行查找想要的信息，并进行操作；首页界面如图5-1所示：

![](/md/blog.026.png)

图5-1 首页界面

第一次使用本小程序的使用者，首先是要进行注册，点击“注册”，然后就会进入到注册的页面里面，将用户信息录入注册表，确认信息正确后，系统才会进入登录界面，用户登录成功后可使用本小程序所提供的所有功能，注册界面如图5-2所示。

![](/md/blog.027.png)

图5-2 注册界面

保健知识：在保健知识页面输入标题名称进行搜索，可以看到保健知识详细信息，按照提示即可完成评论或收藏操作。保健知识详情如图5-3所示。

![](/md/blog.028.png)

图5-3 保健知识详情界面图

用户登录成功后，点击“我的”进入我的页面，在我的页面可以对预约信息，口腔历史，用户反馈，在线问诊等进行详细操作，用户功能界面如图5-4所示。

![](/md/blog.029.png)

图5-4 用户功能界面图

医生登录成功后，点击“我的”进入我的页面，在我的页面可以对预约信息，口腔历史，用户反馈，在线问诊等进行详细操作，医生功能界面如图5-5所示。

![](/md/blog.030.png)

图5-5 医生功能界面图

## 5.3后台管理员模块实现
管理员登录，在登录页面正确输入用户名和密码后，进入操作系统进行操作；如图5-6所示。

![](/md/blog.031.png)

图5-6 管理员登录界面

管理员进入主页面，主要功能包括对系统首页，个人中心，医生管理，用户管理，预约信息管理，口腔历史管理，用户反馈管理，在线问诊管理，保健知识管理，系统管理等进行操作。管理员主页面如图5-7所示：

![](/md/blog.032.png)

图5-7管理员主界面

管理员点击用户管理。进入用户页面输入用户名可以查询，新增或删除用户信息列表，并根据需要对用户详细信息进行详情，修改和删除等操作。如图5-8所示：

![](/md/blog.033.png)

图5-8用户管理界面

管理员点击口腔历史管理。进入口腔历史页面输入用户名可以查询或删除口腔历史列表，并根据需要对口腔历史详细信息进行详情，修改或删除操作。如图5-9所示：

![](/md/blog.034.png)

图5-9口腔历史管理界面

管理员点击保健知识管理。进入保健知识页面输入标题名称可以查询、新增或删除保健知识列表，并根据需要对保健知识详细信息进行详情，修改、查看评论或删除操作。如图5-10所示：

![](/md/blog.035.png)

图5-10保健知识管理界面

管理员点击系统管理，进入医疗公告页面输入标题可以查询、新增或删除医疗公告列表，并根据需要对医疗公告详细信息进行详情、修改或删除操作，还可以对关于我们、系统简介和轮播图管理进行详细操作；如图5-11所示：

![](/md/blog.036.png)

图5-11系统管理界面


# 










