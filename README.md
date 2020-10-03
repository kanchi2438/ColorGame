# Color Game

This game is all about colors! You'll get three colors and a RGB Value. Click the square that matches the RGB color you've been given.

![Game](https://i.imgur.com/zNaOqed.png)

This game was built using HTML, CSS, JavaScript and is supported by the Bootstrap 4 Framework

## How to deploy this game:

Easily clone this Repository and start a local HTTP Server (eg, NGINX, Apache or for development [http-server](https://www.npmjs.com/package/http-server))

### Configuration Examples
Here are some examples how you could setup your webserver to host this game:

#### NGINX Virtual Host Config
```nginx
server {
    root /ColorGame;

    location / {
        index colorgame.html;
    }
}
```

#### Start with HTTP Server
```shell script
npx hs ColorGame
```
