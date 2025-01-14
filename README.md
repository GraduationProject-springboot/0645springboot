# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0645springboot班级综合测评管理系统--论文

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV14HerezEwW?p=2)


# 绪论
## 1.1课题研究的背景
随着电子技术的普及和快速发展，线上管理系统被广泛的使用，有很多事业单位和商业机构都在实现电子信息化管理，班级综合测评管理也不例外，由比较传统的人工管理转向了电子化、信息化、系统化的管理。

传统的班级综合测评管理系统，一开始都是手工记录，然后将手工记录的文档进行存档；随着电脑的普及，班级综合测评管理演变成了手工记录后，输入电脑进行存档。这两种管理方式，对教师来说工作量大，不单要教授课程，后期的班级综合测评管理还需要花费大量时间。而且这种班级综合测评管理的方式，容易出现遗失或因为失误输入错误的信息等等。在这些基础上，我把用Springboot为框架的班级综合测评管理系统作为我的毕业设计，希望可以解决传统班级综合测评管理系统中出现的问题，简化教师的工作，也可以方便管理员进行系统化、电子化的管理。
## 1.2 课题研究的内容
研究的基本内容：本设计主要是实现一个班级综合测评管理系统，实现学校管理的自动化、信息化管理。系统的主要的设计原则是：以实际应用为核心，重点突出“实用、易用、简洁、稳定”的优点。既能够注重到实效，满足现实用户的实际需要，也能够为系统以后的升级和扩展留有一定的余地。在技术设计的实现上，突出“实现合理、结构清晰、简单易懂”的特点。

本系统的主要目的在于加速信息化进程，充分利用计算机技术和现代通讯的手段面向学校的服务。建立信息交流平台，方便信息资源的共享，加强各个部门之间的交流。提高整体的办公效率，为管理员以及教师提供辅助的班级综合测评管理服务。本系统将最大程度地提高学校整体的工作效率和工作质量，降低管理和工作的成本，改善工作的环境和条件，提高管理和决策的自动化和科学化水平。帮助学校节省费用，减少中间环节，优化业务流程，提高整体效率，促进管理的进步。
## 1.3 系统开发的意义
随着互联网技术的发展，人们的生活无处不在的受到互联网技术影响，而互联网技术给人们生活带来的便利是不言而喻的。对于现代化的班级综合测评管理系统而言，它的目的并不是减少教师的工作量，而是让教师们从繁琐的班级综合测评过程中解脱出来，将更多的关注点放到教学水平和教学技能上，这样就可以提高学校的教学水平，服务于更多的群众，所以开发本系统是十分有意义的。
## 1.4初步设计方法与实施方案
软件体系结构方案：由于本系统需要在不同设备上都能运行，而且电脑配置要求也要越低越好，为了实现这一要求，经过考虑B/S结构成为最佳之选。使用B/S结构的系统可以几乎在任何电脑上运行，只要浏览器可以正常工作就可以正常运行该系统，而且后期维护及二次修改较为容易，符合要求。

操作系统方案：Windows10操作系统，该系统是目前微软公司推出的最新系统，目前大多数市面上的电脑都使用该系统，并且该系统功能完善，兼容性好。开发工具：选用My Eclipse、Java开发技术。
## 1.5 本文研究内容
本论文主要划分成七大章节，具体内容如下：

第一部分为绪论，主要介绍了目前电脑技术发展状况、班级综合测评管理行业发展阶段，分析传统班级综合测评管理的弊端以及使用信息技术来管理班级综合测评信息的好处。

第二部分为相关技术简介，主要介绍了各技术的发展历程，技术发展现状，技术优点以及选用该技术的原因等。

第三部分为系统分析，主要分析了软件设计所需要的功能。

第四部分为系统设计，主要进行了系统的架构设计、数据库设计等。

第五部分为系统详细设计。

第六部分为系统调试与测试，利用测试方法进行可行性测试、性能测试、系统测试等。

第七部分为总结与致谢，主要总结了程序设计的完成过程及完成情况，比对完成设计过程中施以援手的特性和老师表达中心的感谢和祝愿。



# 2相关技术介绍
## 2.1 Java技术
Java是由Sun公司推出的一门跨平台的面向对象的程序设计语言。因为Java 技术具有卓越的通用性、高效性、健壮的安全性和平台移植性的特点，而且Java是开源的，拥有全世界最大的开发者专业社群，所以Java的发展迅速。
## 2.2B/S架构
B/S的系统是通过能上网的电脑就可以使用，它最大的优点是不需要安装专门的软件，首先浏览器向服务器发出请求，然后服务器处理请求把信息再返回给浏览器。不需要再次对数据进行存取与计算数据，只要负责显示数据来降低要求，如果说客户端像个“瘦子”，而服务器会越来越“胖”。B/S体系结构与C/S体系结构相比，最大的不同是：B/S体系的应用软件使用网络浏览器作为与用户交互的平台，而C/S则需要开发专用的应用程序。

![2009318052962238](/md/blog.008.png)

图2-1 B/S结构图
## 2.3 MySQL介绍
在软件项目，通过经营性数据的数据库，可以保证其安全，独立和数据一致，访问数据的系统来提供，所以有效减少时间程序员开发应用程序。

MySQL可以支持多线程，可以方便使用系统的资源，提高运行的速度。并提供odbc、jdbc和tcp/ ip，以各种形式连接到MySQL; 功能方面表现欠缺，规模小，但对于这个系统就足够了。

因为MySQL是源代码对外开放的，所以任何人都可以通过相应的方法下载，并根据个性化需求进行修改。由于MySQL的速度，可靠性和适应性，MySQL受到重视。

MySQL虽然功能可能不是很强大，但由于其开源，广泛传播，导致很多人都意识到这个数据库。

## 2.4 Springboot框架
本技术是Java平台的开源应用框架，其目的是简化Sping的初始搭建和开发过程。默认配置了很多框架的使用方式，自动加载Jar包，为了让用户尽可能快的跑起来spring应用程序。

SpinrgBoot的主要优点有：

1. 为所有spring开发提供了一个更快、更广泛的入门体验；
1. 零配置；
1. 集成了大量常用的第三方库的配置；
1. 提供准备好的特性。当今，Java领域的开发者机会都在使用SpinrgBoot,在开发领域逐渐成为领导者。










# 3系统需求分析
## 3.1 可行性分析
可行性分析是系统开发过程中的重要的一步，可行性研究是指在开发系统时，先对整体系统的所有的需求，所需要使用的技术和在开发时候需要用到的方法，以及开发所需要的人员，资金等各方面的综合考虑之后，再对该系统是否符合实际开发的要求进行评估，满足实际要求之后再进行实际的开发工作。一般的可行性分析包括：技术可行性、经济可行性可行性等；

研究的目的就是使用最小的代价和最短的时间来确定问题是否能够完善解决。该系统的可行性分析主要包括以下几个方面的内容。
### 3.1.1 经济可行性分析
班级综合测评管理系统，主要面向的是电脑用户，成本并不高，对于系统的维护和调试，只需要一个人就可以完成，所以在人力方面，投入的也很少。虽然说人力和资金的投入并不多，但是面临的收益是十分可观的，在21世纪，很多企业、公司等都会将管理的目标转移到线上管理，知识是无价的。在未来，很多企业投入的人力资源和资金不会太多，但却又能保证企业运转继续进行。这对整个企业的发展是非常有利的。
### 3.1.2 技术可行性分析
班级综合测评管理系统的开发使用了比较成熟的企业级项目开发的模式。使用MyEclipse作为开发工具，数据库使用MySQL。以Java技术为基本，使用Springboot框架搭建工程环境，结合自身的实际项目开发能力，完全可以开发出比较完善的班级综合测评管理系统。 
## 3.2 需求分析
### 3.2.1用户需求分析
根据账号登陆进入班级综合测评管理系统，系统根据角色展示相应的功能权限。教师可以修改个人信息和密码，还可以对学生信息，综合评价等进行详情、修改、删除、测评等。超级管理员拥有系统所有功能权限，可以管理系统，管理教师和学生的信息。
### 3.2.2 功能需求分析
根据一般班级综合测评管理系统的功能需求分析，本系统的功能模块如下：

（1）在个人中心，管理员可以修改自己的用户名和登录密码。

（2）在教师管理模块中，可以查看教师的信息，和进行修改、删除。

（3）在学生管理模块中，可以查看学生的信息，和进行修改、删除。

（4）在综合测评管理页面，管理员只有查看详情、修改、删除和查看统计图的权限，新增的权限是在教师的手上。
### 3.2.3系统性能需求分析
对系统性能进行分析，可对系统反应度、界面简洁清晰度、储存能性、易学性和稳定性进行分析；

系统反应度：同时上万人在线时反应时间应该在两三秒以内，。

界面简洁清晰：系统界面要求简单明了，操作简单，用户操作容易上手。

储存性能高：高考志愿智能推荐系统中需要存储的信息有很多，所以对系统的存储量要求很高，因此数据库就应该很强大，才能保证信息能安全稳定的进行存储；

易学性：该系统在操作上必须简单好上手，没有很多复杂的操作，只需要简单的进行学习就能操作该系统。

稳定性：要求高考志愿智能推荐系统运行要稳定，界面清楚、字体清晰等。
## 3.3系统流程的分析
由于不同的系统实际使用用户角色的不同，他们的业务分析也会变得有所不一样，为了论述方便接下来都将以用户功能权限下的系统业务流程来分析，如下图所展示:
### 3.3.1用户管理的流程
![](/md/blog.009.png)

图3-1 用户管理流程
### 3.3.2个人中心管理流程
![](/md/blog.010.png)

图3-2 个人中心管理流程
### 3.3.3登录流程
![](/md/blog.011.png)

图3-3 登录流程

## 3.4 系统现状分析
系统使用用户的数量直接决定了用户信息管理者的工作量，毫无疑问，网站管理者的工作量较大较繁琐。通过前期的调研总结出网站现有的对用户管理工作状况如下分析：

缺少统筹规划，如果一个网站在信息化管理中缺少综合性、系统性、整体性，那不可避免的需要投入大量人力物力来规划整理信息。引入信息化管理方式无疑可以达到节省信息管理成本的目的不仅减少资源浪费还可以使班级综合测评信息的管理变得井井有条，成为市场竞争中的一大优势。

要循序渐进，心急吃不了热豆腐，任何事情都不可能一蹴而就，就算信息管理系统也一样，要让系统发挥最大效率还是应该多调研，多听取用户和管理者的意见，并进行必要的统筹规划，有组织有目的地设计系统功能，团结各个部门发挥主观能动性。

(3)信息安全措施不到位

隐私权神圣不可侵犯，这是中华人民共和国宪法赋予我们的权利，人和人都不能侵犯我们的正当权益，而网络用户信息管理存在极大安全隐患，信息泄露的案列不在少数，加强信息安全措施是完善网络信息管理过程中不可避免的一环。

` `(4)资源不能充分共享

资源共享是网络的一大特点，没有共享就没有社交，网络也就失去了他应有的魅力，如果能够实现用户信息共享，无疑对于社会的发展存在不可或缺的帮助。

(5)现有系统可扩展性不高。

如今科学技术发展飞速，随着而来的就是技术更新，那势必会给软件更新带来挑战，因此，系统必须具备良好的开放性和可扩充性，为了不落后于时代，这是必备特色之一。

基于上述分析，班级综合测评管理系统网站应该切合实际，做到确实有效，集体表现为：一是系统能够整理并集合归类用户信息，防止用户信息混乱，难以整理；二是系统要安全稳定，不能泄露用户信息，造成隐私泄露，不仅伤害用户利益更是对经营者名誉的损毁；三是系统要具有良好的开放性，不仅要方便定期的维护维修，更要方便及时增加新功能，保证先进的时代契合性。经过详细的讨论论证，确定系统的总体要求。

28
![](/md/blog.012.png)
# 4系统总体设计与实现
## 4.1总体设计
班级综合测评管理系统采用了结构化开发的方法。这种开发方法的优点是控制性比较强，开发过程中采用了结构化和模块化的设计思想，自顶向下，从总体到部分，合理划分系统的结构和模块。结构化开发时使用模块式开发，各模块之间互不影响，方便系统的开发与管理。 

本系统的设计是基于 B/S架构的三层体系结构，也就是浏览器和服务器结构。计算机技术发展的速度非常快，以前的设计结构都以C/S的模式为主，也就是客户端和服务端模式。但随着网页技术的发展，越来越多的用户习惯于使用浏览器。现在的网页技术可以在浏览器中实现非常漂亮的效果，以前的单一低调的客户端页面已经无法满足用户的需求。在B/S这种结构下，技术人员可以很轻松的设计出用户所需要的工作界面，页面代码通过浏览器进行解析展示，在浏览器中不做过多的事务逻辑的处理。主要的事务逻辑放在服务端进行处理。这样用户的电脑就不会承载过多的东西，只需要浏览器展示即可。对于开发人员也很方便进行系统的维护和升级。开发人员只需要在服务端进行系统的维护就可以了。使用Java这样的跨平台性非常好的语言，这样的开发模式更加的方便，高效。本系统合理的进行了模块划分和组合，因此由于各个模块之间基本上是相互独立的，所以每个模块都可以独立的被解释、执行、调试和修改，让繁琐的系统设计工作简单化。系统总体设计图如下图4-1所示：

![](/md/blog.013.png)

图4-1系统总体设计图
## 4.2数据库设计
### 4.2.1概念模型设计
数据可设计要遵循职责分离原则，即在设计时应该要考虑系统独立性，即每个系统之间互不干预不能混乱数据表和系统关系。

数据库命名也要遵循一定规范，否则容易混淆，数据库字段名要尽量做到与表名类似，多使用小写英文字母和下划线来命名并尽量使用简单单词。

概念模型是对现实中的问题出现的事物的进行描述，ER图是由实体及其关系构成的图，通过E-R图可以清楚地描述系统涉及到的实体之间的相互关系。

学生管理实体图如图4-2所示：

![](/md/blog.014.png)

图4-2学生管理实体图

教师管理实体图如图4-3所示：

![](/md/blog.015.png)

图4-3教师管理实体图

综合测评管理实体图如图4-4所示：

![](/md/blog.016.png)

图4-4综合测评管理实体图
### 4.2.2物理模型设计
根据上诉的逻辑模型设计，下面给出物理模型的设计，如下表:

表4-1：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-2：token表

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

表4-3：教师

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|jiaoshigonghao|varchar|200|教师工号|||
|mima|varchar|200|密码|||
|jiaoshixingming|varchar|200|教师姓名|||
|xingbie|varchar|200|性别|||
|zhaopian|varchar|200|照片|||
|jiaoshidianhua|varchar|200|教师电话|||

表4-4：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-5：班级

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|banji|varchar|200|班级|||

表4-6：综合测评

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|xuehao|varchar|200|学号|||
|xueshengxingming|varchar|200|学生姓名|||
|jiaoshigonghao|varchar|200|教师工号|||
|jiaoshixingming|varchar|200|教师姓名|||
|banji|varchar|200|班级|||
|deyu|float||德育|||
|zhiyu|float||智育|||
|tiyu|float||体育|||
|zonghechengji|float||综合成绩|||
|lurushijian|date||录入时间|||

表4-7：学生

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|xuehao|varchar|200|学号|||
|mima|varchar|200|密码|||
|xueshengxingming|varchar|200|学生姓名|||
|xingbie|varchar|200|性别|||
|touxiang|varchar|200|头像|||
|xueshengshouji|varchar|200|学生手机|||
|banji|varchar|200|班级|||
|jiaoshigonghao|varchar|200|教师工号|||


# 5 系统功能的详细设计与实现
## 5.1 管理员功能模块
管理员输入账号和密码，选择登录角色进行登录，管理员登录界面如图5-1所示：

![](/md/blog.017.png)











图5-1管理员登录界面

管理员功能：管理员登录系统后，能对首页、个人中心、学生管理、教师管理、班级管理、综合测评管理进行操作。管理员功能如下图所示：

![](/md/blog.018.png)






图5-2管理员功能界面

学生管理：在学生管理页面，可以对索引、学号、学生姓名、性别、班级、学生手机、班级、教师工号等内容进行详情、修改和删除等操作，如图5-3所示：

![](/md/blog.019.png)

图5-3学生管理界面

教师管理：在教师管理页面，可以对索引、教师工号、教师姓名、性别、照片、教师电话等内容进行详情、修改和删除等操作，如图5-4所示：

![](/md/blog.020.png)

图5-4教师管理界面

班级管理：在班级管理页面，可以对索引、班级等内容进行修改和删除等操作，如图5-5所示：

![](/md/blog.021.png)

图5-5班级管理界面

综合测评管理：在综合测评管理页面，可以对索引、学号、学生姓名、教师工号、教师姓名、班级、德育、智育、体育、综合成绩、录入时间等内容进行详情，修改和删除等操作，如图5-6所示：

![](/md/blog.022.png)

图5-6综合测评管理界面

## 5.2学生功能模块
学生功能：学生登录到班级综合测评管理系统后，可以对首页、个人中心、综合测评管理等进行操作，如图5-7所示：

![](/md/blog.023.png)

图5-7学生功能界面

个人中心：学生可以将学号、学生姓名、性别、头像、学生手机、班级、教师工号等个人信息进行修改，还能修改密码，如图5-8所示：

![](/md/blog.024.png)

图5-8个人中心界面

综合测评管理：在综合测评管理页面，可以对索引、学号、学生姓名、教师工号、教师姓名、班级、德育、智育、体育、综合成绩、录入时间等内容进行详情操作，如图5-9所示：

![](/md/blog.025.png)

图5-9综合测评管理界面

## 5.3教师功能模块
教师功能：教师登录到班级综合测评管理系统后，可以对首页、个人中心、学生管理、综合测评管理等进行操作，如图5-10所示：

![](/md/blog.026.png)

图5-10教师功能界面

个人中心：教师可以将教师工号、教师姓名、性别、照片、教师电话等个人信息进行修改，还能修改密码，如图5-11所示：

![](/md/blog.027.png)

图5-11个人中心界面

学生管理：在学生管理页面，可以查看对索引、学号、学生姓名、性别、头像、学生手机、班级、教师工号等内容进行详细和综合测评等操作，如图5-12所示：

![](/md/blog.028.png)

图5-12学生管理界面

综合测评管理：在综合测评管理页面，可以对索引、学号、学生姓名、教师工号、教师姓名、班级、德育、智育、体育、综合成绩、录入时间等内容进行详情、修改和删除等操作，如图5-13所示：

![](/md/blog.029.png)

图5-13综合测评管理界面

















# 系统










