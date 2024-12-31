> #### 作者主页：[舒克日记](https://blog.csdn.net/cativen)
>
>  简介：Java领域优质创作者、Java项目、学习资料、技术互助
>
> <b><font color=red>文中获取源码</font></b>

# 项目介绍

本田径运动会成绩管理系统主要满足3种类型用户的需求，这3种类型用户分别为队员、裁判员和管理员

​

队员功能：可查看系统信息，包括首页、赛前通知、比赛信息以及新闻资讯等，用户要想实现比赛报名等操作，必须登录系统，未有账号的队员可进行注册操作，注册登录后主要功能模块包括个人中心、比赛报名管理、弃权信息管理、特殊队员管理、赛前编排管理、赛中信息管理以及赛事成绩管理。

管理员功能：可登录系统后对系统进行全面管理，管理员登陆后主要功能模块包括个人中心、赛前通知管理、裁判员管理、队员管理、比赛信息管理、比赛项目管理、比赛报名管理、弃权信息管理、特殊队员管理、赛前编排管理、赛中信息管理、赛事成绩管理以及系统管理。

裁判员功能：注册登录后主要功能模块包括个人中心、队员管理、赛前编排管理、赛中信息管理、赛事成绩管理。

# 环境要求

1.运行环境：最好是java jdk1.8,我们在这个平台上运行的。其他版本理论上也可以。

2.IDE环境：IDEA,Eclipse,Myeclipse都可以。推荐IDEA;

3.tomcat环境：Tomcat7.x,8.X,9.x版本均可

4.硬件环境：windows7/8/10 4G内存以上；或者Mac OS;

5.是否Maven项目：是；查看源码目录中是否包含pom.xml;若包含，则为maven项目，否则为非maven.项目

6.数据库：MySql5.7/8.0等版本均可；

# 技术栈

运行环境：jdk8 + tomcat9 + mysql5.7 + windows10

服务端技术：Java、Spring、SpringMVC、Mybatis，SSM

前端：vue

# 使用说明

1.使用Navicati或者其它工具，在mysql中创建对应sq文件名称的数据库，并导入项目的sql文件；

2.使用IDEA/Eclipse/MyEclipse导入项目，修改配置，运行项目；

3.将项目中config-propertiesi配置文件中的数据库配置改为自己的配置，然后运行；

# 运行指导

idea导入源码空间站顶目教程说明(Vindows版)-ssm篇：

http://mtw.so/5MHvZq

源码地址：[http://www.codegym.top](http://www.codegym.top/)


# 运行截图

## 功能模块截图

![img](https://i-blog.csdnimg.cn/img_convert/716bb982bfc24f138832a3e45817f23a.png)

![img](https://i-blog.csdnimg.cn/img_convert/2362c6c6401f7f2a604397955cc5acdd.png)

![img](https://i-blog.csdnimg.cn/img_convert/a7e8a9f9b0ede328d4c82cd049195ac9.png)

![img](https://i-blog.csdnimg.cn/img_convert/3cd23bb68c3690df32f33a348e3dcecb.png)

###

### 项目截图

前台

![图片1](https://i-blog.csdnimg.cn/img_convert/4ca8b1aae554e0a71693419056ddc295.png)

![ssm124田径运动会成绩管理系统的设计与实现vue3](https://i-blog.csdnimg.cn/img_convert/3e4c943acec835ee45812d8f5486ef25.png)

![ssm124田径运动会成绩管理系统的设计与实现vue4](https://i-blog.csdnimg.cn/img_convert/ae0f05ae3deb5ee2f3350e3a34d4b805.png)

![ssm124田径运动会成绩管理系统的设计与实现vue5](https://i-blog.csdnimg.cn/img_convert/9bd82a8a353b6c01470a19ebcb02bd13.png)

![ssm124田径运动会成绩管理系统的设计与实现vue6](https://i-blog.csdnimg.cn/img_convert/dfeb67d80c9e0b06fd93c82434afb642.png)

后台

![ssm124田径运动会成绩管理系统的设计与实现vue10](https://i-blog.csdnimg.cn/img_convert/e8af82dd46aed7b0869ca82d9b2e1e9d.png)

![ssm124田径运动会成绩管理系统的设计与实现vue11](https://i-blog.csdnimg.cn/img_convert/b0e19af54cfadf03f0dfc1d2e2700cd1.png)

![ssm124田径运动会成绩管理系统的设计与实现vue12](https://i-blog.csdnimg.cn/img_convert/5cc9bb0387b75fc6b347cab39c25c3c6.png)

![ssm124田径运动会成绩管理系统的设计与实现vue13](https://i-blog.csdnimg.cn/img_convert/8cc748c93e3175ddff2428d7efe60a40.png)

![ssm124田径运动会成绩管理系统的设计与实现vue14](https://i-blog.csdnimg.cn/img_convert/58c1d7e304c5bc8cafcae3a755568fbe.png)

![ssm124田径运动会成绩管理系统的设计与实现vue15](https://i-blog.csdnimg.cn/img_convert/50fe65d9e52b1ebce7dd19829046a98e.png)

![ssm124田径运动会成绩管理系统的设计与实现vue16](https://i-blog.csdnimg.cn/img_convert/68d19412f725149b3da4face49f0bc8a.png)

![ssm124田径运动会成绩管理系统的设计与实现vue17](https://i-blog.csdnimg.cn/img_convert/4f14b1363901d276e8c5d5bb4a869c4f.png)

![ssm124田径运动会成绩管理系统的设计与实现vue18](https://i-blog.csdnimg.cn/img_convert/cc436a0823fdf68675721a6b71e517bb.png)
### 代码

```
  private List<TenantVO> getWorkTenantList(String userId) {
        return getTenantListByUserId(userId);
    }

    private List<TenantVO> getLifeTenantList(String userId) {
        return getTenantListByUserId(userId);
    }

    private UserDO getUserByUserId(String currentUserId) {
        UserDO userDO = this.baseMapper.selectOne(new LambdaQueryWrapper<UserDO>().eq(UserDO::getId, currentUserId));
        if (userDO != null){
            userDO.setCustomerFlag(isCustomer(currentUserId));
            return userDO;
        }

        //查询顾客信息
        CustomerDO customerDO = customerMapper.selectOne(new LambdaQueryWrapper<CustomerDO>().eq(CustomerDO::getId, currentUserId));
        if (customerDO != null){
            UserDO copyUser = new UserDO();
            BeanUtils.copyProperties(customerDO, copyUser);
            copyUser.setCustomerFlag(isCustomer(currentUserId));
            return copyUser;
        }
        throw new BizException("401", "用户不存在");
    }
```
