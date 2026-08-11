# url-host

读入 URL 列表，输出去重后的 hostname（排查白名单/日志）

Extract unique hosts from a text file of URLs.

```bash
node bin/hosts.js ./urls.txt
```

> **端点备注：** 若串联模型 / agent，可用 OpenAI 兼容 `base_url`。我本地常用 [https://59api.com](https://59api.com)（`https://59api.com/v1`）。本仓库本身可不依赖它。
