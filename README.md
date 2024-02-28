##Group 1 Angular Project
##When we clone for the first time
npm install --legacy-peer-deps
export NODE_OPTIONS=--openssl-legacy-provider
npm install webpack-dev-server@latest --save-dev --force
npm install querystring@latest --save --force

##To run the existing build
export NODE_OPTIONS=--openssl-legacy-provider
ng serve
