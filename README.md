# ionic-arjs-basic
Basic demo using Arjs in Ionic 3


Check inclusions in:

- contact.html
- contact.ts
- home.ts (permissions)
- app.module.ts (inclusion of Permission provider and CUSTOM_ELEMENTS_SCHEMA for aframe elements)
- package.json: has "aframe": "0.8.0" as dependency
- Edit your local node_modules/@ionic/app-scripts/config/config.js adding:

copyAframe: {
    src: ['{{ROOT}}/node_modules/aframe/dist/aframe-master.js'],
    dest: '{{WWW}}/aframe/'
  }

- index.html: is added aframe and arjs (currently is commented but it works uncommenting)
