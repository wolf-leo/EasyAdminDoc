# 文档简介

- 本文档是在老项目 `EasyAdmin` 的基础上镜像，可参考，实际使用请根据现有 `EasyAdmin8` 相关框架自行匹对。
- 在使用中请尊重 `EasyAdmin` 源作者的开发成果。
- 如喜欢现有 `EasyAdmin8` ，可以到项目 `git` 中帮忙点个 `star` ~

# 项目介绍

`EasyAdmin` 是基于ThinkPHP6.0+Layui的快速开发的后台管理系统。
`EasyAdmin8` 是基于 `EasyAdmin` 的快速开发的后台管理系统，并衍生了 `Laravel`、`webman`不同框架的后台管理系统。

# 演示站点

- 源版本 `ThinkPHP6` 演示地址：[http://easyadmin.99php.cn/admindemo](http://easyadmin.99php.cn/admindemo)
- `EasyAdmin8` 项目地址：[https://easyadmin8.top](https://easyadmin8.top)
- （账号：admin，密码：123456。备注：只有查看信息的权限）

# 项目特性

* 快速CURD/CRUD命令行
    * 一键生成控制器、模型、视图、JS文件
    * 支持关联查询、字段预设置等等
* 基于`auth`的权限管理系统
    * 通过`注解方式`来实现`auth`权限节点管理
    * 具备一键更新`auth`权限节点，无需手动输入管理
    * 完善的后端权限验证以及前面页面按钮显示、隐藏控制
* 完善的菜单管理
    * 分模块管理
    * 无限极菜单
    * 菜单编辑会提示`权限节点`
* 完善的上传组件功能
    * 本地存储
    * 阿里云OSS`建议使用`
    * 腾讯云COS
    * 七牛云OSS
* 完善的前端组件功能
    * 对layui的form表单重新封装，无需手动拼接数据请求
    * 简单好用的`图片、文件`上传组件
    * 简单好用的富文本编辑器`ckeditor`
    * 对弹出层进行再次封装，以极简的方式使用
    * 对table表格再次封装，在使用上更加舒服
    * 根据table的`cols`参数再次进行封装，提供接口实现`image`、`switch`、`list`等功能，再次基础上可以自己再次扩展
    * 根据table参数一键生成`搜索表单`，无需自己编写
* 完善的后台操作日志
    * 记录用户的详细操作信息
    * 按月份进行`分表记录`
* 一键部署静态资源到OSS上
    * 所有在`public\static`目录下的文件都可以一键部署
    * 一个配置项切换静态资源（oss/本地）
* 上传文件记录管理
* 后台路径自定义，防止别人找到对应的后台地址

# 特别感谢

以下项目排名不分先后

ThinkPHP：[https://github.com/top-think/framework](https://github.com/top-think/framework)

Layuimini：[https://github.com/zhongshaofa/layuimini](https://github.com/zhongshaofa/layuimini)

Annotations：[https://github.com/doctrine/annotations](https://github.com/doctrine/annotations)

Layui：[https://github.com/sentsin/layui](https://github.com/sentsin/layui)

Jquery：[https://github.com/jquery/jquery](https://github.com/jquery/jquery)

RequireJs：[https://github.com/requirejs/requirejs](https://github.com/requirejs/requirejs)

WangEditor：[https://github.com/wangfupeng1988/wangEditor](https://github.com/wangfupeng1988/wangEditor)

Echarts：[https://github.com/apache/incubator-echarts](https://github.com/apache/incubator-echarts)

# BUG反馈

项目使用过程成，如遇到BUG，可通过以下途径进行反馈。

GitHub:[https://github.com/zhongshaofa/easyadmin/issues](https://github.com/zhongshaofa/easyadmin/issues)

Gitee:[https://gitee.com/zhongshaofa/easyadmin](https://gitee.com/zhongshaofa/easyadmin/issues)

`EasyAdmin` QQ群:[763822524](https://jq.qq.com/?_wv=1027&k=5IHJawE)
`EasyAdmin8` QQ群:[751595815](https://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=CVrFoAMpXNLzn0IN6mv8qpIcbKKxqnp-)

# 版权信息

EasyAdmin遵循MIT开源协议发布，并提供免费使用。

# QQ交流群

`EasyAdmin` QQ群:[763822524](https://jq.qq.com/?_wv=1027&k=5IHJawE) 

`EasyAdmin8` QQ群:[751595815](https://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=CVrFoAMpXNLzn0IN6mv8qpIcbKKxqnp-)

`加群请备注来源：如gitee、github、官网等`。