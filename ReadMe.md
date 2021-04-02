## Framework installation

### Install node js

Installation guide can be found
here: https://docs.npmjs.com/downloading-and-installing-node-js-and-npm

On Linux nodejs can be updated via below commands on ubuntu

```
sudo npm cache clean -f
sudo npm install -g n
sudo n stable

### Install all dependencies

```
npm install
```

### Run tests
For Local run:
```
npx cypress open
```
For Dashboard:
```
npx cypress run --record --key ba8eb115-244d-471d-9c0c-bfa06070a1d9
```