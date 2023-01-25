# PWA Text Editor

## Description

A text editor app that runs in the browser and offline. It's a single-page application that meets the PWA criteria.

This application:
- uses IndexedDB to create an object store and includes GET and PUT methods.
- works without an internet connection.
- saves content inside the text editor when the DOM window is unfocused.
- bundles with webpack.
- creates a service worker with workbox that Caches static assests.
- uses babel in order to use async/await.
- has a generated manifest.json using the WebpackPwaManifest plugin.
- can be installed as a Progressive Web Application.

## Visuals

![pwa-text-editor](/assets/pwa-text-editor.png)

## Deployed Link

https://enigmatic-gorge-52968.herokuapp.com/

## Questions

Feel free to contact me at jennyhawes24@gmail.com or look at my [Github](https://github.com/JenniferKiesler).