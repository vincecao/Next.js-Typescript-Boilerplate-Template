# Next.js Typescript Boilerplate Template

A template for Nextjs typescript with local HTTPS 

# Usage

``` bash
# choose one of `package.json` and `package_w_prettier.json` based on if want format feature
# rename as `package.json` and remove unnecessary one

# install dependencies
yarn install

# use mkcert to generate key and cert 
mkcert -install
mkcert local.com "*.local.com" local.test localhost 127.0.0.1 ::1

# copy key and cert under certificates folders and rename them in the server.js

# run the server
yarn dev

# start development
# https://localhost:3000/
# https://localhost:3000/hello
```

# Reference

* [Next.js](https://nextjs.org/learn).
* [mkcert](https://github.com/FiloSottile/mkcert)
* [Secure your local development server with HTTPS (Next. JS)](https://medium.com/@anMagpie/secure-your-local-development-server-with-https-next-js-81ac6b8b3d68)
