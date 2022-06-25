# Jekyll & Netlify & NetlifyCMS Landing page template

[![Netlify Status](https://api.netlify.com/api/v1/badges/16deb651-e3d4-4861-a002-69b3f783e4d3/deploy-status)](https://jekyll-netlify-netlifycms.netlify.app/)

Landing page template starter build using [Jekyll](https://jekyllrb.com/), [Netlify](https://www.netlify.com/), [NetlifyCMS](https://www.netlifycms.org/).

## Install
Feel free to use [asdf](https://github.com/asdf-vm/asdf) since there is file `.tool-versions`.

Install Jekyll:
```
https://jekyllrb.com/docs/
```

Install packages and bundle:
```
npm install
```

Bundle install:
```
npm run install
```

## Run

Run development mode (Jekyll & NetlifyCMS):
```
npm run dev
```

Run build - run build locally (there is no need to do it locally. Netlify will build it by itself at every deploy.)
```
npm run build
```

## Run  development mode on mobile

If you want to preview website on mobile:
- Run `npm run dev`,
- Make sure there is no firewall that block incoming connections on your PC,
- Type YOUR_IP:3000 e.g. `192.186.0.7:3000`,
- It works with livereload!
- Voilà.

## Deploy this template to Netlify

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/MikolajChybowski/jekyll-netlify-netlifycms)
