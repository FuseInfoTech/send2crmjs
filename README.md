# Send2CRM

This repository contains public Send2CRM JavaScript libraries.

You will need a Send2CRM service to connect to.

## License

Use of this software is subject to the [EULA](https://github.com/FuseInfoTech/send2crmjs/blob/main/EULA.txt)

## send2crm.min.js

This is the main client library. To include on your website:

```
<script>(function(s,e,n,d2,cr,m){n[e]=n[e]||{};m=document.createElement('script');m.onload=function(){n[e].init(d2,cr);};m.src=s;document.head.appendChild(m);})('https://cdn.jsdelivr.net/gh/FuseInfoTech/send2crmjs@v1.20.0.25080/send2crm.min.js', 'send2crm', window, '<service_url>', '<shared_key>');</script>
```

### Optional: Subresource Integrity (SRI) hash verification

Copy the SRI hash from the send2crm.sri-hash.sha384 file.

```
<script>(function(s,e,n,d2,c,r,m){n[e]=n[e]||{};m=document.createElement('script');m.onload=function(){n[e].init(d2,c);};m.src=s;m.integrity='sha384-'+r;document.head.appendChild(m);})('https://cdn.jsdelivr.net/gh/FuseInfoTech/send2crmjs@v1.20.0.25080/send2crm.min.js', 'send2crm', window, '<service_url>', '<shared_key>', 'MMhLTpx4KWjOglo+qHQHspMKG2PZq/xf5eVrewB2A2u4+6aysZiXZ71mDRjiQwTO');</script>
```

If delivering via CDN, ensure that a specific version is applied and the hash used is from the same release.

## CDN hosted

The library may be delivered directly from Github via the jsDelivr CDN.

Instead of copying the script file to your web server, reference the latest version directly:

```
https://cdn.jsdelivr.net/gh/FuseInfoTech/send2crmjs@v1.20.0.25080/send2crm.min.js
```

## send2crm-content.min.js

This provides the `<send2crm-content />` custom element to interact with the Web Content package.
