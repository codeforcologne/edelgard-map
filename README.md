# EDELGARD map

A routing web app for the EDELGARD project in Cologne, Germany

## Background

[EDELGARD <sup>(de)</sup>](https://edelgard.koeln/) is a campaign by the [Cologne Initiative Against Sexualized Violence <sup>(de)</sup>](https://www.koelner-initiative-gegen-sexualisierte-gewalt.de/).
Its goal is to improve protection for women and girls against sexualized violence in public spaces within Cologne, Germany.
More than one hundred organizations and businesses in Cologne have agreed to open their doors for people seeking a protected space.

## Purpose

This app assists the user in finding available protected spaces based on geolocation and business hours.
It can then route the user to the place of their choice.

A demo version of the app can be viewed at https://edelgard-test.netlify.com/

![Screenshot of the EDELGARD map](https://edelgard-api-test.netlify.com/assets/screenshot.png)

## Development

The app currently requires an API token for the services of [Mapbox](https://www.mapbox.com/),
both for the map tiles and for routing requests.
A token can be retrieved after creating a free [Mapbox account](https://account.mapbox.com/auth/signup/).

Please create a file named `.env.local` in the `client` directory with the following contents.

```shell
REACT_APP_MAPBOX_TOKEN=yourtokenhere
```

You can then install the dependencies and start the development server.

```shell
npm install
npm start
```
