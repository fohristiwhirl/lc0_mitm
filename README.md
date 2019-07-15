# lc0_mitm

Extremely crude hack of [Nibbler](https://github.com/fohristiwhirl/nibbler) to run via a browser with a Golang backend that actually runs the engine.

```
go get github.com/gorilla/websocket
go build lc0_mitm.go
```

Then run the Go backend in the same folder as `lc0.exe` or `lc0`, and launch the HTML file in a browser. If needed, you should configure Leela with an `lc0.config` file.

Tested on Firefox only, for now. A bunch of non-functional or broken code lurks in the JS (i.e. it works in Nibbler but won't work here).
