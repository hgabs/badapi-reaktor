# Bad API Assignment for Reaktor


|Backend|Frontend|Hosting|
|-------|--------|-----|
|node, express|react.js|Azure|

The goal was to serve the page as fast as possible taking into consideration all the exceptions that might arise. The API data alone should take more or less 700 ms to be fetched and will be automatically refresh every 5 minutes. The user should be able to use the page with little to practically no waiting and navigate with ease.

## Cloning the repository

This repository uses submodules for the backend and frontend.

`git clone --recurse-submodules <repository_url>`

## Prerequisites and Running the backend/frontend

From the backend's folder, build the frontend by executing ***npm run build:ui***. Once done it can be served with ***npm run*** and accessed on the localhost on port 8888. You may also run the backend in development mode with ***npm run dev***, run the frontend separately with ***yarn start*** and access it on localhost on port 3000.
