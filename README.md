# Lyrid NodeJS v16 Express.JS Template

## Run locally with:
```
npm i
npm start
```

Open http://localhost:3000

## Edit the names (optional):
Open .lyrid-definition and change the App and Module name, because this will override another applications with the same name in the platform.

## Then submit to Lyrid Platform:

```
lc code submit
```
Wait until the cloud platform to finish with the build and the default deployment.

## Start hacking:

Edit the routes at /src/entry/entry.js with your custom API. 

Add more middlewares or your business logic in there.

<a href="https://app.lyrid.io/login?one-click-deploy=true&origin=github&repository-url=https://github.com/LyridInc/Express-NodeJS16.x-Template.git&env=empty&project-type=Express-NodeJS16.x&repo-name=Express-NodeJS16.x-Template">
  <button>
    <img src="/dist/assets/svg/ocd_deploy_to_lyrid.svg" style="height: 50px; width:200px;"/>
  </button>
</a>