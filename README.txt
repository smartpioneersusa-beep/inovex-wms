INOVEX Warehouse System — launcher for https://wms.inovex-group.com

This small static site only sends people to the secured portal (Google Apps Script web app running in info@inovex-group.com).
- INOVEX staff  → company Google sign-in address (https://script.google.com/a/macros/inovex-group.com/s/<ID>/exec)
- Invited users → e-mail + password sign-in        (https://script.google.com/macros/s/<ID>/exec)

To change the portal address later, edit config.js only.
Hosting: GitHub Pages (repo inovex-wms) with custom domain wms.inovex-group.com (file CNAME).
DNS (Squarespace → Domains → inovex-group.com → DNS → Custom records):  CNAME · Host: wms · Data: smartpioneersusa-beep.github.io
