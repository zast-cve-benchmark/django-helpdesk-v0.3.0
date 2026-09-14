# django-helpdesk-v0.3.0 - 漏洞总览

| # | CVE | 漏洞类型 | 端点 |
|---|---|---|---|
| 1 | CVE-2018-25111 | CWE-277 不安全默认权限 (os.umask) | POST /tickets/submit/ |
| 2 | CVE-2021-3945 | CWE-79 存储型 XSS (ticket title) | GET /datatables_ticket_list/<query> |
| 3 | CVE-2021-3950 | CWE-79 存储型 XSS (SVG 上传) | POST /tickets/submit/ |
| 4 | CVE-2021-3994 | CWE-79 存储型 XSS (Markdown mark_safe) | POST /tickets/submit/ + GET /tickets/<id>/ |
