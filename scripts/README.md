# 脚本使用说明

## GitHub 自动推送

### 首次配置

1. 设置 Token 环境变量（添加到 `~/.bashrc`）：
```bash
echo 'export GITHUB_TOKEN=你的_TOKEN' >> ~/.bashrc
source ~/.bashrc
```

2. 配置 Git credential：
```bash
git config --global credential.helper store
```

### 推送页面

```bash
cd /root/.openclaw/workspace
./scripts/auto-push-github.sh entity-single-analysis.html "添加实体分析页面"
```

### 在线访问

部署完成后访问：
```
https://jcchervy.github.io/WmOS/页面名称.html
```
