# geochess
geochess - brings chess tournament events in a simple leaflet map

# backend info

Backend is written in Node Js.
cheerio is used to scrap tournaments from fide's website, (at some point an API should be available).
Every day our list is refreshed and overwritten in `tournaments.json file`.

# frontend info

Frontend is written in Vue 3 following composition API and typescript support. It is also using Vuetify 3, a components library for vue.
# Setup for local development

## 1st way clone the whole repository
This repo is based to two git-submodules for indepedant organization purposes. geo-frontend & geo-backend repos.
To clone the whole app with both repositories:
1. Clone the whole repo
2. Open VS Code on the directory and run `git submodule init`. This connects to the subrepositories
3. Then run `git submodule update`. This fetches the repositories locally.
4. Now you can cd in the two directories and follow the instructions bellow from the **second step**.

## Setup for local development

1. Clone both backend (Node js) and Frontend (Vue) folders
2. Install the dependices in both directories by running `npm install`
3. Open the backend and run `npm run start`, nodemon will run the local backend server
4. Open the frontend and run `npm run dev`.
5. You should be ready to go, open your browser in  **http://localhost:5173/**
