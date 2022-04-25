deploy cf_worker/index.js into cloudflare worker

after git push github.com/diyism/diyism.github.io/jsproxy/

firefox opened https://<cloudflare worker custom domain>/jsproxy/
/ mouse right click / Inspect / Application / Service Workers / sw.js / Unregister
/ mouse right click / Inspect / Storage / Cache Storage / .sys / mouse right click / Delete All
press keyboard ctrl + r    to reload https://<cloudflare worker custom domain>/jsproxy/
