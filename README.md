[![Netlify Status](https://api.netlify.com/api/v1/badges/6d681546-50c2-491d-b4bd-273117a848ab/deploy-status)](https://app.netlify.com/sites/wazo-wda-ring/deploys)

# wda-ring

Plugin for WDA to permit the user to change their ringtone for incoming call.

Build
-----

    docker build -t ring .

Run
---

    docker run --rm --name ring -p8901:80 ring

Configure
---------

To use the plugin on WDA, go to Portal -> Settings -> Applications -> Apps Configuration, create Wazo Desktop, then edit Advanced to specify key[manifest_urls] and value [http://URL/manifest.json] where my URL points to your docker deployed of the plugin.

Screenshots
-----------

![menu1](./screenshots/menu1.png?raw=true)
![menu2](./screenshots/menu2.png?raw=true)

