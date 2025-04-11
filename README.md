# docker
Docker容器一键管理脚本

<img width="697" alt="截屏2025-03-13 10 13 26" src="https://github.com/user-attachments/assets/41b833ac-2d99-48e1-abf8-5ffae52e6c99" />

docker管理一键脚本：
```
bash <(curl -sL https://github.com/3981877/docker/releases/download/5.0/default.sh)
```
## 使用准备：

### 设置权限
```
chmod +x docker.sh
```
### 运行脚本
```
./docker.sh
```

## 模块化管理：
容器管理（启动/停止/重启/删除/日志/Shell接入）

镜像管理（拉取/删除/详情查看/清理）

网络管理（创建/删除/详情查看）

存储卷管理（创建/删除/清理）

系统管理（版本/磁盘/全局清理）

## 增强功能：
批量启动/停止所有容器

日志查看支持实时跟踪和指定行数

支持选择Shell类型（bash/sh）

详细的JSON格式信息查看（依赖jq命令）

危险操作二次确认

自动资源清理功能

彩色状态显示（运行中/已停止）

## 安全机制：
所有删除操作需要确认

自动过滤无效输入

清理操作限制权限提示

## 操作指南：
主菜单选择管理类别（容器/镜像/网络/卷/系统）

每个子菜单提供数字选项操作

红色文本表示危险操作

黄色文本表示警告提示

绿色文本表示成功操作
