# Changelog

这个项目的所有显著变化都将被记录在这个文件中。

## [0.7.0] - 2018-06-22

### 修改

- 升级了chart中dbtool的版本为0.5.2。
- 升级choerodon-starter依赖版本为0.5.3.RELEASE。

### 修复

- 修复了线上管理端口有时访问不通的问题。

## [0.6.0] - 2018-06-08

### 新增

- 新增Root用户跳过权限校验。

### 修改

- 修改权限校验的逻辑，抽取项目id和组织id。
- 修改`JwtAddFilter`中获取`userDetail`方式。
- 解决`/zuul`开头的`uri`无法跳过权限校验的问题。

### 删除

- 移除关于用户组相关的代码
- 移除`ZuulRoutesProperties`这个类。
