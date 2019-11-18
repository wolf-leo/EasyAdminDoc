# 权限忽略配置

### 登录判断和权限验证忽略配置
配置文件位置：`app/admin/config/admin.php`
```php
<?php

// +----------------------------------------------------------------------
// | EasyAdmin
// +----------------------------------------------------------------------
// | PHP交流群: 763822524
// +----------------------------------------------------------------------
// | 开源协议  https://mit-license.org
// +----------------------------------------------------------------------
// | github开源项目：https://github.com/zhongshaofa/EasyAdmin
// +----------------------------------------------------------------------

return [

    // 不需要验证登录的控制器
    'no_login_controller' => [
        'login',
    ],

    // 不需要验证登录的节点
    'no_login_node'       => [
        'login/index',
        'login/out',
    ],

    // 不需要验证权限的控制器
    'no_auth_controller'  => [
        'ajax',
        'login',
        'index',
    ],

    // 不需要验证权限的节点
    'no_auth_node'        => [
        'login/index',
        'login/out',
    ],
];
```

* no_login_controller：不需要验证登录的控制器
* no_login_node：不需要验证登录的节点
* no_auth_controller：不需要验证权限的控制器
* no_auth_node：不需要验证权限的节点

控制器和节点是一个并关系，如果控制器在二级目录下，写法应该为：system/config （对应位置：`app/admin/controller/system/Config.php`）