# think6-multi-app

用于ThinkPHP6+的多应用支持

## 安装

~~~
composer require xpf0000/think6-multi-app
~~~

## 使用

用法参考ThinkPHP6完全开发手册[多应用模式](https://www.kancloud.cn/manual/thinkphp6_0/1297876)章节。
<br>不同点就是在应用下面可以新增模块文件夹, 每个模块都是独立的controller view, 方便后期维护.<br>
例如 admin/user/index/userList 指向的就是admin应用下的user模块下的index控制器下的userList方法. 
<br>实际目录结构就是: /app/admin/user/controller/Index.php 
<br>视图文件在: /app/admin/user/view/index/userList.html

