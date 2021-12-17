# Streamlabs Desktop API documentation


[Streamlabs Desktop](https://github.com/stream-labs/streamlabs-obs) Has a local API for interacting with the application. You can use this API to speed up some UI actions or for writing drivers for any kind of remote controllers.

[GOTO DOCUMENTATION PAGES](https://stream-labs.github.io/streamlabs-desktop-api-docs/docs/index.html)

This repo also includes a simple web-interface for [Streamlabs Desktop](https://github.com/stream-labs/streamlabs-obs) that you can use as an example to start working with the API. This web-interface demonstrates some basic features like switching between scenes, show/hide, mute/unmute sources.
 
 [Launch web-interface](https://stream-labs.github.io/streamlabs-desktop-api-docs)

![Screenshoot1](https://raw.githubusercontent.com/stream-labs/streamlabs-desktop-api-docs/master/screenshots/screen1.png)

# How to connect the web-application to Streamlabs Desktop
* Remote connections are disabled by default. To enable it go to `Settings->Remote Control` and click on the QR-Code and than on `show details`
* copy the token
* [Launch web-interface](https://stream-labs.github.io/streamlabs-desktop-api-docs)
* inset your token in the `token` field on the top of the page
* click the `connect` button 


The web-interface also includes a simple console for testing direct API requests
![Screenshot1](https://raw.githubusercontent.com/stream-labs/streamlabs-desktop-api-docs/master/screenshots/screen2.png)

# How to run this app on the local machine
* clone the repo
* install the web-interface application via `npm install`
* run `npm start` to start simple HTTP server
* open one of the suggested URLs in a browser

