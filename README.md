# Kudos

Visualizing your Strava data.

## ⚙️ Project setup

1. Create a [Strava API Application](https://developers.strava.com/docs/getting-started/#account) and get the Client ID and Client Secret.
2. Create a Mapbox account and [get your access token](https://docs.mapbox.com/help/glossary/access-token/).
3. Create a .env file in the root of the project that looks like:

```
   VUE_APP_CLIENT_ID=YOUR_CLIENT_ID
   VUE_APP_CLIENT_SECRET=YOUR_CLIENT_SECRET
   VUE_APP_MAPBOX_TOKEN=YOUR_MAPBOX_TOKEN
```

4. `npm install`
5. `npm run serve`

Don't forget to restrict your keys and tokens!

## 🚀 Project deployment

### Create a new Heroku app

```
heroku create your-app-name
```

### Set Heroku config variables

```
heroku config:set VUE_APP_CLIENT_ID=YOUR_CLIENT_ID
heroku config:set VUE_APP_CLIENT_SECRET=YOUR_CLIENT_SECRET
heroku config:set VUE_APP_MAPBOX_TOKEN=YOUR_MAPBOX_TOKEN
```

### Deploy app to Heroku

```
git push heroku master
```

## 💻 Technologies and API's

- [Vue.js](https://vuejs.org/)
- [Strava V3 API](https://developers.strava.com/)
- [Mapbox](https://www.mapbox.com/)
