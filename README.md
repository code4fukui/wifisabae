# wifisabae

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

An interactive map of public WiFi hotspots in Sabae City, Fukui, Japan. This project uses open data to help residents and visitors find free internet access.

## Demo

**[Live Map: 鯖江WiFiマップ](https://code4fukui.github.io/wifisabae/)**


![OGP Preview](https://code4fukui.github.io/wifisabae/ogp.jpg)


## Features

- Visualizes public WiFi locations in Sabae on an interactive map.
- Displays estimated signal coverage (a 30m radius) with a semi-transparent circle for each hotspot.
- Provides key details on click: SSID, password, operating hours, and power outlet availability.
- Features a "Show Current Location" button to find nearby WiFi spots.

## Data and Technology

This application is built with vanilla HTML/CSS and JavaScript (ES Modules).

- **Mapping:** Uses [egmapjs](https://code4fukui.github.io/egmapjs/egmap.mjs).
- **Data Source:** Fetches data live via SPARQL queries from the [Open Data Platform (ODP)](https://odp.jig.jp/).
- **Dataset:** [Public Wireless LAN (Sabae City, Fukui)](https://ckan.odp.jig.jp/dataset/jp-fukui-sabae-173-odp), provided by Sabae City under a CC BY license.

## Credit

APP: