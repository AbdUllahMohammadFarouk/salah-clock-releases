# Third-party notices — Salah Clock

Salah Clock includes or uses the following third-party software, fonts, data and services. Full licence texts are in the `licenses` folder next to this file.

## Software (bundled)

| Component | License | Source |
|---|---|---|
| Electron (includes Chromium and Node.js; their licenses ship as `LICENSES.chromium.html` and `LICENSE.electron.txt` in the install folder) | MIT | https://github.com/electron/electron |
| React, React DOM | MIT | https://github.com/facebook/react |
| adhan (offline prayer-time calculation) | MIT | https://github.com/batoulapps/adhan-js |

## Fonts (bundled)

| Font | License | Source |
|---|---|---|
| Titillium Web | SIL Open Font License 1.1 | https://fonts.google.com/specimen/Titillium+Web |
| Amiri | SIL Open Font License 1.1 | https://github.com/aliftype/amiri |

## Data (bundled)

| Data | License / attribution |
|---|---|
| Country and place catalogue (`resources/app.asar/dist/geo`) | Derived from **GeoNames** (https://www.geonames.org), licensed under Creative Commons Attribution 4.0 (CC BY 4.0). Modified: every populated place with ≥ 1,000 people (171,226 places); fields reduced; Arabic names used as search keywords only. |
| Country names in Arabic | Unicode CLDR via ICU (Unicode License) |

## Online services (used at run time)

| Service | Use | Terms |
|---|---|---|
| **Aladhan Prayer Times API** — https://aladhan.com | Monthly prayer times and Hijri dates | Free public API; see https://aladhan.com/prayer-times-api |
| **Windows Location service** (built into Windows) | Optional "Detect with Windows location" button: the device position, matched offline to the nearest catalogue place | Part of Windows; governed by the user's Windows privacy settings |

No geocoding or IP-lookup service is used. The widget also works without Aladhan: prayer times fall back to cached data and then to local astronomical calculation.
