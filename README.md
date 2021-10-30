<!-- PROJECT LOGO  -->
<br />
<p align="center">
  <a href="https://github.com/schaudhary1/food-festival">
    <img src="./assets/img/logo.png" alt="Logo" width="100" height="">
  </a>

  <h3 align="center">Food Festival</h3>

  <p align="center">
    A platform that offers tickets options for food festivals.
    <br />
    <a href="https://github.com/schaudhary1/food-festival"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://chaudharys1.github.io/food-festival/">View Demo</a>
    ·
    <a href="https://github.com/schaudhary1/food-festival/issues">Report Bug</a>
    ·
    <a href="https://github.com/schaudhary1/food-festival/issues">Request Feature</a>
  </p>
</p>

## Usage: 
Event attendees will use the app on their phones, it needs to be fast and performant, especially on mobile. But the application loads very slowly when the client tries to simulate a 4G internet connection using Chrome DevTools. 

Application is now optimized by minifying assets, adding offline functionality, and turning it into a Progressive Web Application (PWA).

## Features
- Optimize CSS, JavaScript, and media assets for performance.
- Set up webpack in a new front-end project.
- Use service workers to cache assets for offline functionality.


## Tools Used
* Google Lighthouse is a tool that helps improve the performance of web applications by providing audits for performance, accessibility, Progressive Web Apps, and more.

* Webpack is a module bundler for JavaScript that simplifies front-end web development by generating static assets from modules with dependencies and using plugins and loaders to help automate certain optimization strategies. 

* The webpack-bundle-analyzer plugin allows to visualize the size of webpack output files with an interactive zoomable treemap.

* The file-loader plugin resolves import/require() on a file into a URL and emits the file into the output directory.

* The image-webpack-loader plugin allows to enhance the image-loading process.

* The SW-precache-webpack plugin allows to use service workers to cache external project dependencies. 

* The webpack-PWA-manifest plugin generates a manifest.json for the PWA, with auto icon resizing and fingerprinting support.