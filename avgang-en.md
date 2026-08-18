# Privacy Policy — Avgang

*Effective date: 17 August 2026* · [Norsk versjon](avgang)

## Summary

Avgang does not collect, store, or share any personal data about you.

---

## Data collected by the developer

**None.** The developer of Avgang does not collect, store, process, or share any personal data. There are no analytics, crash reporting, advertising SDKs, or backend servers operated by this app.

## Location

Avgang requests access to your device's location solely to identify the public transit stops nearest to you. Your location is processed entirely on your device and is never transmitted to the developer or stored anywhere outside your device.

Finding the nearest stops is done on your device, against a stop list that ships with the app and is updated periodically — your coordinates are not sent to Entur or to anyone else in order to do it. The qualifications to on-device processing are the features described under Apple Maps below — in particular the optional walking-time estimate, which is the only feature that sends your own position anywhere. It is off by default.

## Third-party services — Entur

To display real-time departure information, the app queries the public API operated by Entur (entur.no). Queries include the identifiers of transit stops you view, but not your location. For details on how Entur handles data, please refer to [Entur's privacy policy](https://om.entur.no/personvern).

Departure data is provided by Entur under the [Norwegian Licence for Open Government Data (NLOD) 2.0](https://data.norge.no/nlod/no/2.0).

## Third-party services — Apple Maps

The app uses Apple's MapKit framework to draw maps and, optionally, to estimate walking time. Map imagery is not contained in the app; it is requested from Apple's servers as it is needed, which means Apple receives the map area being requested. Three features talk to Apple's servers: the first is on by default, the other two are off by default. All of them can be switched off in the app's settings.

- **The background of the departures screen.** This is **on by default**. The card showing your next departure is drawn over a small map of the area around the stop — roughly 400 metres across, centred on the stop itself rather than on you. What is sent is the stop's own coordinate, which is public data from the National Stop Register; your own position is not sent. Note, however, that the app normally shows the stop nearest you, so the areas requested over time will tend to correspond to places you have been. Apple does not receive your coordinates, but the requests come from your device and their subject matter follows your journeys. These images are cached on your device for about two weeks, so the same stop is normally requested only once in that period. Switching off "Vis kartbilde bak avgangskortet" in settings stops this entirely — no map imagery is then requested for this screen.
- **The map tab.** If you turn on the optional map tab, it shows an interactive map that opens centred on your location and marks your position on it. Apple therefore receives the map area you are looking at, which at that moment approximately reflects where you are. Your position is still not sent to the developer. This tab is off by default.
- **Walking time to the stop.** If you turn on "Vis gåtid til stasjonen" in settings, two screens display an estimate of how many minutes it takes to walk to the stop, on the card showing the departure itself: the departures screen and the screen showing a single departure. To calculate this, your device sends your current position, together with the stop's coordinate, to Apple as a walking-route request. This is the only feature in the app that transmits your own position; it is **off by default**, and no such requests are made until you turn it on. Results are cached on your device so the request is not repeated on every refresh. Your position is still not sent to the developer, and never to Entur.

How Apple handles these requests is described in [Apple's privacy policy](https://www.apple.com/legal/privacy/). See also Apple's [legal notice for map data](https://gspe21-ssl.ls.apple.com/html/attribution-1.html).

## Analytics and crash reporting

None. No third-party analytics or crash-reporting tools are used.

## Children

This app does not knowingly collect information from anyone, including children under the age of 13.

## Changes to this policy

If this policy changes, the updated version will be published at this URL with a new effective date.

## Contact

Questions about this privacy policy can be sent to [avganger@p.xxd.no](mailto:avganger@p.xxd.no).
