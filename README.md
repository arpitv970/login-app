# packages required to install
## To create react app in `client` directory:
### enter `client` directory
```bash
cd client
```
creating react app
```bash
npx creat-react-app .
```
## Installing Express in `login-app` (main directory)
### make sure you return back to `login-app`
```bash
cd ..
```
to install npm using `npm`
```bash
npm i express
```
## Packages Available

### `dotenv`
```bash
npm i dotenv
```
### `nodemon`
```bash
npm i -D nodemon
```
### `mongoose`
```bash
npm i mongoose
```
### `bcrypt`
```bash
npm i bcryptjs
```
### `jsonwebtoken`
```bash
npm i jsonwebtoken
```
## To get random generated string for token
```bash
require('crypto').randomBytes(35).toString("hex")
```