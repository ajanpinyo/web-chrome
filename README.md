# web-chrome: Chrome with NoVNC

```
docker run -d --name web-chrome --restart always -p 8088:8088 -p 5900:5900 ajanpinyo/web-chrome:latest
```

<p><b><h3>[ ! ] This project runs directly as a root user with non-sandboxed chrome!<br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;do not use in production environments.</h3></b></p>

## Environment variables: 
|      PORT      |                NoVNC HTTPS Port (Default: 8088)                |
|:--------------:|:--------------------------------------------------------------:|
|    VNC_PASSWORD|               VNC Password (Default: samplepass)               |
|    VNC_TITLE   |              VNC Session Title (Default: Chrome)               |
| VNC_RESOLUTION |               VNC Resolution (Default: 1920x1080               |
|    APP_NAME    |                Name of the app (Heroku specific)               |
|    NO_SLEEP    | Prevent app from sleeping (Heroku specific, default: disabled) |
