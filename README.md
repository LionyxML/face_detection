# face_detection

An example on how to use face-api.js (a face detection api) with JavaScript and HTML.

It works!

![testing](./demo/testing.png)

Check this great project here:

[face-api.js](https://github.com/justadudewhohacks/face-api.js/)

### note

This project uses
`navigator.getUserMedia` which is now deprecated and should be replaced by `navigator.mediaDevices.getUserMedia`, however the second is implemented (on Google Chrome) only to work with URLS that contain `httpS`, so I kept the deprecated way since it is easier to test on "unsafe" localhost.
