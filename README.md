# 基本静态网站

此仓库是一个最简静态站示例，可直接部署到 **GitHub Pages**。

## 步骤

1. 在 GitHub 创建新仓库并推送本代码。  
2. 进入 **Settings → Pages**，选择 **Branch: main / / (root)** 并保存。  
3. 若使用自定义域名，在同一页面填写你的域名并按提示添加 A/CNAME 记录。  
4. 等待 DNS 生效后，访问域名即可看到页面。

## 结构

```
.
├── index.html          # 主页
├── assets/
│   └── styles.css      # 简单样式
├── CNAME               # 可选：自定义域名文件，内容为你的域名
└── .gitignore
```
