# dockerTest-css
<h2> <img src="https://www.docker.com/sites/default/files/d8/styles/role_icon/public/2019-07/horizontal-logo-monochromatic-white.png?itok=SBlK2TGU" alt="drawing" width="100"/> commands</h2>

(in WINDOWS use PowerShell, avoid git bash & cmd)

### Run in dev file change reactive
```sh
$ docker run -dp 3000:3000 -w /app -v "$(pwd):/app" node:12-alpine sh -c "yarn install && yarn run dev"
```


### Run normaly
```sh
$ docker build -t getting-started .
$ docker run -dp 3000:3000 getting-started
```
