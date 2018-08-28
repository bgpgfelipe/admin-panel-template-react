## Admin Panel Template

Admin Dashboard developed in react.js and node.js.

#### How to setup project

1. Clone the repo `https://github.com/varunon9/admin-panel-template-react.git`
2. Move to project folder `cd admin-panel-template-react`
3. Install dependencies `npm install`
4. Create config.js file from config-sample.js `cd config && cp config-sample.js config.js`
5. In MySql create a database "adminPanelTemplate" (or with any other name but must be mentioned in config.js)
6. Update `username` with your MySql username and `password` with your MySql password in config.js 
7. Build bundle.js `npm run build`
8. start the project from project root directory `node bin/www` or `nodemon`
9. Visit localhost:4000 in browser