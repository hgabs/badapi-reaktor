# Bad API Assignment for Reaktor


|Backend|Frontend|Hosting|
|-------|--------|-----|
|node, express|react.js|Azure|

The goal was to serve the page as fast as possible taking into consideration all the exceptions that might arise. The API data alone should take more or less 700 ms to be fetched and will be automatically refresh every 5 minutes. The user should be able to use the page with little to practically no waiting and navigate with ease.

## Cloning the repository

This repository uses submodules for the backend and frontend.

`git clone --recurse-submodules <repository_url>`

## Serving the Backend and Frontend

### Production

The frontend should be built from the backend's directory using the **npm run build:ui** and served from the backend with **npm start**.

### Development

To serve the frontend independently, run it from its directory with **yarn start**. Run the backend from own directory with **npm run dev**. This will run the backend using nodemon and add the cors header that will allow accessing the api from the frontend.
