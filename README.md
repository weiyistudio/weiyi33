# weiyi33
SSM图书借阅管理系统的设计与实现

#### 介绍
图书借阅管理系统分为管理员模块和用户模块。用户模块完成的功能有可以进行用户的注册和登录，用户可以使用图书检索来找到自己想要的图书，用户可以对图书有借阅功能和图书归还功能。管理员模块可以对用户借阅的图书进行审核，同意借阅和归还，可以对后台的图书进行添加增加，删除图书，修改图书信息的功能。管理员可以对用户信息进行修改，有图书信息的历史记录。
经过检测完成后，图书借阅管理系统用户可以进行图书借阅和归还，管理员可以进行审批，符合大学图书馆的借阅系统的应用。


图书借阅管理系统大致页面分为图书借阅管理系统图书检索页面，用户登录页面，我的借阅页面，历史借阅页面，个人信息页面，管理员页面等等。
图书借阅管理系统大致业务流程为匿名用户可通过网址访问游览网站主页，匿名用户可以游览图书检索页面，首次借阅书籍需要进行登录。新用户通过注册页面进行用户的首次注册，成功注册后的用户可通过图书借阅管理系统登录页面提交登录信息来进入图书借阅管理系统的查看图书页面。图书借阅管理系统会对每一次成功登录的用户进行身份效验，如果效验通过，图书借阅管理系统后端会记录这次用户登录的信息，保存到服务器，并且重新跳转到图书借阅管理系统图书借阅页面。图书借阅管理系统的核心业务模块分为用户模块，图书模块，借阅模块，管理员模块。
![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/020113_230cd682_4865385.png "屏幕截图.png")

图书借阅管理系统的主要功能模块大致可分为用户模块，图书模块，借阅模块，管理员模块。
（1）用户模块
用户模块作为图书借阅管理系统的核心功能模块之一，其主要功能为储存图书借阅管理系统的用户信息为用户做操作的一系列流程提供信息基础。用户模块需求为匿名游客可通过注册页面注册成为系统用户。匿名游客可通过登录页面登录本系统。系统用户可自由修改个人信息，包括个人密码，签名等等。系统用户离开时可通过注销功能注销登录并退出系统。
（2）图书模块
图书模块作为图书借阅管理系统的核心业务的功能模块之一，其主要功能为对系统中用户可借阅的图书进行储存的功能。图书模块的需求为系统用户可通过图书检索页面检索到系统的所有图书，并且可以点击相应的书籍进入该书籍的详细信息页面查看到书籍的详细信息，管理员可以通过后台管理页面添加图书，删除图书等功能。 
（3）借阅模块
借阅模块作为图书借阅管理系统不可或缺的核心业务模块，其主要功能为对系统中用户借阅的书籍进行储存的功能。借阅模块的需求为登录后的用户可通过系统对喜欢的书籍进行借阅，用户借阅书籍后需要等待后台管理员审核借阅，用户可随时查看自己等待审核借阅的书籍。用户也可对已借阅的书籍进行还书的操作，还书同样需要管理员审核，管理员审核通过后的还书借阅信息系统会转存为借阅历史信息，用户可随时查看到自己的借阅历史信息。
（4）管理员模块
管理员模块作为图书借阅管理系统核心业务的功能模块之一，其主要功能为管理系统各个模块的功能。管理员模块的主要需求为对借阅的审核，对用户的管理，对图书的管理等。

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/020137_e63c6350_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/020147_3b23ac52_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/020157_72b1fa5e_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/020205_c4d5f9f4_4865385.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2020/1128/020214_9f6a100b_4865385.png "屏幕截图.png")

联系方式
联系Q：2762501186
![输入图片说明](https://images.gitee.com/uploads/images/2020/1119/003728_cd598bb9_4865385.jpeg "微信.jpg")
