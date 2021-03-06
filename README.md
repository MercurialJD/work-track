# 996.DAO 项目说明

### 项目简介

996.DAO是一个基于区块链技术和理念的程序员自治社区，针对当下热点的996.ICU问题，力求探寻一种程序员自我管理模式。
* **功能** ：
1. 具有bbs社区基本的发帖跟帖顶帖以及热度排行功能，鼓励程序员之间的技术交流与生活交流。
2. 问答(Q&A)功能。
3. 程序员上下班打卡(check-in/check-out)功能。与公司的上下班打卡不同，此功能为程序员的日常工作时长提供了历史数据追踪与可视化。
4. 公司排行功能。将用户所提供数据与用户所属公司间建立连接，排出员工工作时间最长的十个公司，实时更新，为程序员的生涯规划与发展提供参考。
* **开发技术** ：
* 前端：Bootstrap（渲染）+Ajax（读取XML）+Flask（连接）
* 后端：Python
* 数据库：MySQL
* 部署：Apache
* 区块链：CPChain

### 界面
由于开发总时间较短，故界面较为简洁，但已初步具备所需功能。
* 首页（未登陆）
![homepage](https://github.com/996-dao/work-track/blob/master/static/images/homepage.png)
* 登录页面
![sign_in](https://github.com/996-dao/work-track/blob/master/static/images/sign%20in.png)
* 管理员界面
![administration](https://raw.githubusercontent.com/996-dao/work-track/master/static/images/administer.png)
* 工作时间追踪
![worktrack](https://raw.githubusercontent.com/996-dao/work-track/master/static/images/userWorkTrack.png)
* 版块主页
![section](https://github.com/996-dao/work-track/blob/master/static/images/section.png)
* 公司排行




### 程序使用

* 需要的Python包：flask，xml，pymysql(以及cryptography)，smtplib，email
* 按照MiniBBS_Building.txt中的语句进行数据库搭建
* （可选）运行database.py生成测试数据（python database.py）
* 运行minibbs.py开始服务，可以在本机进行访问（python minibbs.py）
* （可选）配置Apache进行部署
