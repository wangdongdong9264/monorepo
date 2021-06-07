# monorepo

包管理实验

## 常用命令

```shell

lerna create @mo-demo/xxx # 创建报

lerna add chalk # 为所有 package 增加 chalk 模块 
lerna add semver --scope @mo-demo/cli-shared-utils # 为 @mo-demo/cli-shared-utils 增加 semver 模块 
lerna add @mo-demo/cli-shared-utils --scope @mo-demo/utils # 增加内部模块之间的依赖

lerna publish # 发布

```
