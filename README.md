# geochess
geochess - brings chess tournament events in a simple leaflet map

# backend info

Backend is written in Node Js.
cheerio is used to scrap tournaments from fide's website, (at some point an API should be available).
Every day our list is refreshed and overwritten in `tournaments.json file`.

# frontend info

Frontend is written in Vue 3 following composition API and typescript support. It is also using Vuetify 3, a components library for vue.
