# Jpom 部署说明

## 使用Jpom管理单个服务器

> 在需要被管理的服务器中部署插件端和服务端即可

> 说明：同一个服务器中，先安装插件端，再安装服务端，服务端将自动添加节点信息

> 单服务器中不涉及到节点项目分发

## 使用Jpom管理多个服务器

> 1. 所有在需要被管理的所有的服务器中安装插件端
> 2. 选择一个服务器或者其他服务器中安装服务端
> 3. 登录Jpom后台在节点管理中依次添加对应节点即可


## 多节点中使用节点分发功能

> 要使用节点分发功能所有需要确保已经安装并添加多个节点
> 节点分发项目无法在对应节点中的项目管理中直接修改

### 创建节点分发项目

#### 全新方式创建节点分发项目

> 如果需要被管理的项目还没有创建则可以采用直接创建分发项目，将自动在对应节点创建对应信息，省去需要在多个节点中依次创建项目的麻烦

#### 关联已经存在的项目为节点分发

> 如果需要被管理的项目已经在部分节点创建，则可以采用添加关联项目，把多个节点的项目进行关联然后具有分发功能   