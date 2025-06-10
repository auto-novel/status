# Monitor

[![GPL-3.0](https://img.shields.io/github/license/auto-novel/status)](https://github.com/auto-novel/status#license)

## 部署

下载项目：

```bash
> git clone https://github.com/auto-novel/status.git
> cd status
```

创建并编辑 `.env` 文件，内容如下:

```bash
VPS_CORE_IP=                    # core VPS 的 IP 地址
CLOUDFLARE_API_TOKEN=           # Cloudflare 的 API token
```

运行 `docker compose up -d` 命令启动服务。
