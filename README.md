## Local Development

Install deps

`npm install`

Running locally

`npm run dev`

## Deploying

1. Build the dist for gh pages to serve

`npm run build` 

2. Deploying

This will push the dist files to gh-pages branch

`npm run deploy`

_Must ensure in Settings > Pages > Build & Deployment is set to deploy from branch gh-pages from /(root)_

If there are any issues, delete the `dist` folder and build and deploy again

It also helps to clear cache and hard refresh