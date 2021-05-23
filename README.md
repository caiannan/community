# 工程简介
## 资料
[github oAuth](https://docs.github.com/en/developers/apps/creating-an-oauth-app)
[spring 文档](https://spring.io/guides)
[es社区](https://elasticsearch.cn/explore)
[github deploy key](http://developer.github.com/v3/guides/managing-deploy-keys/#deploy-keys)
[bootstrap](https://v3.bootcss.com/getting-started/)

# 工具
[Git](https://git-scm.com/download)
[visual-paradigm](https://www.visual-paradigm.com)

# 脚本
'''sql
create table user
(
    id           int auto_increment
        primary key,
    account_id   varchar(100) null,
    name         varchar(50)  null,
    token        char(36)     null,
    gmt_create   bigint       null,
    gmt_modified bigint       null
);
'''
