# WeChat Bot

基于 WeChatFerry 开发的微信机器人项目。

## 功能特点

- 自动回复消息
- 群聊管理
- 定时任务
- 关键词触发
- 自定义插件系统

## 安装说明

### 环境要求

- Windows 操作系统
- Python 3.7+
- WeChat PC 版本 3.9.2.23

### 安装步骤

1. 克隆仓库
```bash
git clone https://github.com/GUEWE/WECHATBOT.git
cd WECHATBOT
```

2. 安装依赖
```bash
pip install -r requirements.txt
```

3. 配置文件
- 复制 `config.example.json` 为 `config.json`
- 根据需要修改配置项

## 使用方法

1. 启动程序
```bash
python main.py
```

2. 扫码登录微信

3. 开始使用机器人功能

## 配置说明

配置文件 `config.json` 包含以下主要设置：

- `auto_reply`: 自动回复设置
- `group_manage`: 群管理设置
- `schedule_tasks`: 定时任务设置
- `plugins`: 插件配置

## 注意事项

- 请遵守微信使用规范
- 不要频繁发送消息以避免封号
- 定期备份重要数据

## 贡献指南

1. Fork 本仓库
2. 创建新的功能分支
3. 提交代码
4. 创建 Pull Request

## 许可证

本项目采用 Apache 2.0 许可证，详见 [LICENSE](LICENSE) 文件。 