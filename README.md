## Building own Node.js image

Goal: The purpose of this image is to test Node js

### Steps to building your own image

Be in the directory Node-Js-Sample-App
- `cd Node-Js-Sample-App`
- `docker build -t ravi2krishna/node-app .`
- `docker run -p 8080:8080 -d ravi2krishna/node-app`

