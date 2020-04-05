# Hello-World Node JS App
## Steps to run the App in PCF

### Set npm registry 
`npm config set registry http://registry.npmjs.org/`

### install dependencies
`npm install`

### run app in PCF
`cf push content-hello-node -m 256M`
