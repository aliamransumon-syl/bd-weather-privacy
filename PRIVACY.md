# Privacy Policy — BD Weather

_Last updated: 8 November 2026_

BD Weather ("the app") is a weather app for Bangladesh. It covers every
upazila (all 496, across 64 districts in 8 divisions) and shows live weather,
air quality, prayer times, sun and moon times, alerts and a district map for
the place you are in.

The short version: **we collect nothing and operate no servers.** To show you
the weather for where you are, the app sends your position straight from your
phone to four public services, listed below. Nothing passes through us.

## What we collect

**Nothing.** The app has no accounts, no sign-in, no analytics, no
advertising, and no third-party tracking SDKs. We operate no servers of our
own, so there is nowhere for your data to be sent to us.

## Location

Location is **opt-in**. The app asks for permission when you tap **"Locate
me"** / **"Use my location"**. If you grant it, the app may read your
location again on later launches — _only_ while the permission stays granted
— to refresh your place and weather. Revoking the permission in Android
Settings stops this immediately.

The app requests **precise location** (`ACCESS_FINE_LOCATION`), with
`ACCESS_COARSE_LOCATION` as the fallback Android lets you choose instead. A
precise fix is what lets the app name the neighbourhood or mahalla you are in
and pick the nearest of the 496 upazilas (within a 100 km limit — outside
Bangladesh the app tells you it cannot help). A coarse fix is only about 2 km
wide. If you allow only approximate location, the app still works, with a less
exact neighbourhood name.

Your position leaves the device only in the requests listed below. We never
receive it.

## Third-party services

The app contacts four public services:

1. **Open-Meteo weather API** — `api.open-meteo.com`. Receives your
   position to return your forecast. It also receives the fixed coordinates
   of Bangladesh's 64 district centres (not your position) for the national
   map and the national coolest / warmest district.
   Terms: <https://open-meteo.com/en/terms>
2. **Open-Meteo air-quality API** — `air-quality-api.open-meteo.com`.
   Receives your position to return the US AQI reading.
3. **OpenStreetMap Nominatim** — `nominatim.openstreetmap.org`. Receives
   your position to return the neighbourhood / village name shown in the
   header. The request also carries the developer's contact email address
   (`aliamransumon@gmail.com`), which OpenStreetMap's usage policy requires
   from apps; it is not your email. Place names © OpenStreetMap contributors.
   Usage policy: <https://operations.osmfoundation.org/policies/nominatim/>
4. **OpenStreetMap tile servers** — `tile.openstreetmap.org`. When you open
   the Map tab, your device requests map tiles. A tile request reveals the map
   area you are viewing and your IP address, not your exact position.

These services may log coordinates and IP addresses in their own access logs
under their own policies. The app sends no device identifiers, accounts or
advertising IDs. Fonts, weather icons, the map library and all other assets
ship inside the app; it fetches nothing from Google Fonts or any other
third-party host.

## What is calculated on your device

Sunrise, sunset, moonrise, moonset, moon phase, prayer times (including
Seheri and Iftar), and the heat, storm and air-quality advice shown under
**Alerts** are all calculated on your phone from the forecast data it already
holds. Nothing extra is sent anywhere to produce them.

## Notifications

Daily weather notifications (tomorrow's weather at 9 PM, today's at 7 AM) are
**opt-in**: Android asks for the notification permission when you switch them
on. They run entirely on the device using Android's local-notification system
— no push servers, no FCM token. Switch them off in the app or in Android
Settings at any time.

## Sharing

The **Share** button hands a short text summary of the current weather to the
share sheet you choose. The app does not send it anywhere itself.

## What is stored on your device

The app saves the following in its private local storage, so that it opens
instantly and works offline:

* the last downloaded weather and air-quality data for recently viewed
  upazilas,
* the upazila last used and the last known neighbourhood name,
* a map reference for that neighbourhood lookup: your position rounded to about
  100 metres, kept for about 10 minutes so the app does not repeat the
  look-up each time it opens,
* your chosen theme, language, temperature unit and notification setting.

This data never leaves your device. Uninstalling the app removes it. The app's
Android backup is disabled, so it does not sync to Google Drive or any other
cloud backup.

## Weather alerts and safety tips

Alerts and tips in the app are generated automatically from forecast data.
They are general guidance, **not** official warnings and **not** medical
advice. For official warnings follow the Bangladesh Meteorological Department
and local authorities; in an emergency call 999.

## Children

The app is suitable for all ages and collects no personal data from anyone,
including children.

## Changes

Any future change to this policy will be published at this same address, with
a new "last updated" date.

## Contact

Questions about this policy: **aliamransumon@gmail.com**
