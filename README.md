# web-chrome: Chrome with NoVNC

```
docker run --name web-chrome -e PORT=9870 -p 9870:8080 -e VNC_PASS samplepass vital987/chrome-novnc:latest
```

<p><b><h3>[ ! ] This project runs directly as a root user with non-sandboxed chromium! <br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;do not use in production environments.</h3></b></p>

## Environment variables: 
|      PORT      |                NoVNC HTTPS Port (Default: 8088)                |
|:--------------:|:--------------------------------------------------------------:|
|    VNC_PASSWORD|               VNC Password (Default: samplepass)               |
|    VNC_TITLE   |              VNC Session Title (Default: Chromium)             |
| VNC_RESOLUTION |               VNC Resolution (Default: 1280x720)               |
|    APP_NAME    |                Name of the app (Heroku specific)               |
|    NO_SLEEP    | Prevent app from sleeping (Heroku specific, default: disabled) |
