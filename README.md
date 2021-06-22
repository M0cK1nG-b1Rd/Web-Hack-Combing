# Web安全学习脉络梳理


母版来自https://github.com/LyleMi/Learn-Web-Hacking 该仓库仅作学习自用


### 笔记大纲
---

1. 序章
    1. Web技术演化
    2. 网络攻防技术演化
    3. 安全观
2. 计算机网络与协议
    1. 网络基础
    2. UDP协议
    3. TCP协议
    4. 路由算法
    5. 域名系统
    6. HTTP标准
    7. HTTPS
    8. SSL/TLS
    9. IPsec
    10. Wi-Fi
3. 信息收集
    1. 网络整体架构
    2. 域名信息
    3. 端口信息
    4. 站点信息
    5. 搜索引擎利用
    6. 社会工程学
4. 常见漏洞攻防
    1. SQL注入
    2. XSS
    3. CSRF
    4. SSRF
    5. 命令注入
    6. 目录穿越
    7. 文件读取
    8. 文件上传
    9. 文件包含
    10. XXE
    11. 模版注入
    12. Xpath注入
    13. 逻辑漏洞 / 业务漏洞
    14. 配置安全
    15. 中间件
    16. Web Cache欺骗攻击
    17. HTTP 请求走私
5. 语言与框架
    1. PHP
    2. Python
    3. Java
    4. JavaScript
    5. Golang
    6. Ruby
    7. ASP
    8. PowerShell
    9. Shell
6. 内网渗透
    1. 信息收集 - Windows
    2. 持久化 - Windows
    3. 痕迹清理 - Windows
    4. 域渗透
    5. 信息收集 - Linux
    6. 持久化 - Linux
    7. 痕迹清理 - Linux
    8. 后门技术
    9. 综合技巧
    10. 参考链接
7. 防御技术
    1. 团队建设
    2. 安全开发
    3. 威胁情报
    4. ​​ATT&CK
    5. 风险控制
    6. 防御框架
    7. 加固检查
    8. 入侵检测
    9. 蜜罐技术
    10. RASP
    11. 应急响应
    12. 溯源分析
8. 认证机制
    1. SSO
    2. JWT
    3. OAuth
    4. SAML
    5. Windows
    6. Kerberos
    7. NTLM 身份验证
9. 工具与资源
    1. 推荐资源
    2. 相关论文
    3. 信息收集
    4. 社会工程学
    5. 模糊测试
    6. 漏洞利用
    7. 近源渗透
    8. Web持久化
    9. 横向移动
    10. 操作系统持久化
    11. 审计工具
    12. 防御
    13. 运维
    14. 其他
10. 手册速查
    1. 爆破工具
    2. 下载工具
    3. 流量相关
    4. 嗅探工具
    5. SQLMap使用
11. 其他
    1. 代码审计
    2. WAF
    3. Unicode
    4. 拒绝服务攻击
    5. Docker
    6. APT
    7. 近源渗透

### 本地编译
---

```bash
git clone https://github.com/LyleMi/Learn-Web-Hacking.git
cd Learn-Web-Hacking
pip install sphinx sphinx-rtd-theme
make html
```

