# portfolio-app

My simple portfolio app with JWT auth

The app uses spring boot and java in the backend. Login API returns a valid JWT when called with the correct username and password. APIs either require authetication (JWT token) or do not. APIs can be protected with ROLE based allowance by adding the springboot role annotation directly to the controller method
that you wish to be protected. APIs are not currently guarded by role based annotations. 

The Front-end is written in JS, (React). JWT is stored currently in LocalStorage but will be later moved to cookies. Only pages of Register and login can be accessed unless the user has logged in and possesses a valid JWT token in the Header request the front end will submit to the Backend API. Overall, a simple app that will be further refined and improved but works consistently and robustly. 
