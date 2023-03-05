# Send2CRM
This repository contains public send2crm JavaScript libraries.

You will need a send2crm service to connect to.
https://www.send2crm.com/

## send2crm.min.js
This is the main client library. To include on your website:
```
<script>(function(s,e,n,d2,cr,m){n[e]=n[e]||{};m=document.createElement('script');m.onload=function(){n[e].init(d2,cr);};m.src=s;document.head.appendChild(m);})('https://cdn.jsdelivr.net/gh/FuseInfoTech/send2crmjs@v0.8.0.23065/send2crm.min.js', 'send2crm', window, '<service_url>', '<shared_key>');</script>
```