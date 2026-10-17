# Evision Live DNS

Signed server configuration for the standalone Evision Live Android application.

Current configuration contains one enabled host: http://ramboiptv.net:8080.

This repository is separate from ANTHONYBSET1/e-vision-dns-live, which remains unchanged for the existing Official/VIP box and ATV editions.

The app verifies dns.json using dns.json.sig and its embedded public certificate. Publish the JSON and matching signature together for each future change. This repository contains public configuration only.