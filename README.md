# martink-gis-react

Here is a sample application that demonstrates how to integrate OpenLayers with React Functional Components including:

* creating a wrapper component ([MapWrapper.js](https://github.com/learningdollars/martink-gis-react/blob/main/src/components/MapWrapper.js))
* using hooks to initialize the map and add features from props
* get/set component state from within an OpenLayers event handler using refs
* Fetch and parse GeoJSON features from a mock API (done inside [App.js](https://github.com/learningdollars/martink-gis-react/blob/main/src/App.js))

![An example application featuring OpenLayers and React Functional Components](https://github.com/learningdollars/martink-gis-react/blob/main/GISreact.PNG "An example application featuring OpenLayers and React Functional Components")

## Install

Install the dependencies with the following command:

`npm install`

## Launch with Development Server

To run a development build and launch the development server, execute:

`npm start`

Once completed, the app should be avialable from http://localhost:3000/

## Development Environment

This application was developed using create-react-app, with Node version v12.16.1

## Supplemental Blog Post

Here is a blog post I created that explains the integration in further detail: [https://blog.learningdollars.com/author/mkimaniw/](https://blog.learningdollars.com/author/mkimaniw/)
