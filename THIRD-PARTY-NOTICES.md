# Third-party notices

Servalan is built with the open-source software and open data below. Each
installer carries this file, with the full licence texts in a `licences`
folder beside it. In Servalan, choose About Servalan, then Licences…, to
open them.

Servalan itself is under the MIT licence.

## Software

| Component | Version | Licence | Full text in the app's `licences` folder |
| --- | --- | --- | --- |
| Qt, including Qt WebEngine | 6.11.2 | LGPL-3.0. Used unmodified, as separate shared libraries | `Qt-PySide6.txt`, `LGPL-3.0.txt`, `GPL-3.0.txt` |
| Qt for Python (PySide6, Shiboken6) | 6.11.2 | LGPL-3.0, as Qt | `Qt-PySide6.txt` |
| Chromium, inside Qt WebEngine | as in Qt WebEngine 6.11.2 | BSD-3-Clause, and its third-party components' licences, the most restrictive LGPL-2.1 | `Chromium-LICENSE.txt`, `QtWebEngine-third-party.txt`, `LGPL-2.1.txt` |
| MapLibre GL JS | 6.11.2 | BSD-3-Clause | `MapLibre-GL-JS-LICENSE.txt` |
| Terra Draw | 1.35.0 | MIT | `Terra-Draw-LICENSE.txt` |
| Terra Draw MapLibre GL adapter | 1.4.1 | MIT | `Terra-Draw-MapLibre-adapter-LICENSE.txt` |
| OS API branding (the OS Maps API logo) | 0.4.0 | Open Government Licence v3.0 | `OS-API-branding-README.md` |
| pyproj | 3.8.0 | MIT | `python-packages/pyproj/LICENSE` |
| PROJ, inside pyproj | 9.8.1 | MIT | `python-packages/pyproj/LICENSE_proj` |
| libtiff, libjpeg-turbo, libwebp, zstd, XZ Utils, zlib, curl, SQLite, inside pyproj (which ones depends on the OS) | as in pyproj 3.8.0 | libtiff, IJG and BSD-3-Clause, BSD-3-Clause, BSD-3-Clause, 0BSD, zlib, curl; SQLite is public domain | `pyproj-native-libraries.txt` |
| NumPy | 2.5.3 | BSD-3-Clause, with the licences of the code it bundles | `python-packages/numpy/` |
| GeographicLib | 2.1 | MIT | `python-packages/geographiclib/LICENSE` |
| keyring | 25.7.0 | MIT | `python-packages/keyring/LICENSE` |
| jaraco.classes, jaraco.context, jaraco.functools, more-itertools (used by keyring) | 3.4.0, 6.1.2, 4.6.0, 11.1.0 | MIT | `python-packages/` |
| certifi (used by pyproj) | 2026.7.22 | MPL-2.0 | `python-packages/certifi/LICENSE` |
| packaging, setuptools (collected by the app builder) | 26.3, 84.0.0 | Apache-2.0 or BSD-2-Clause; MIT | `python-packages/` |
| fitdecode (when FIT files can be opened) | 0.11.0 | MIT | `python-packages/fitdecode/LICENSE.txt` |
| Python | 3.12 | PSF License, and the licences of the software it incorporates (OpenSSL: Apache-2.0) | `Python-3.12.txt` |

The `python-packages` folder is copied from each package as installed for
the build, so it always matches what that installer carries.

## Data

- **OSTN15:** the OSTN15 transformation grid (`uk_os_OSTN15_NTv2_OSGBtoETRS.tif`)
  is from Ordnance Survey, converted to GeoTIFF by the PROJ project, under
  the 2-Clause BSD licence (`OSTN15-LICENSE.txt`). Servalan uses it to convert between GPS positions
  and the British National Grid.
- **OpenStreetMap:** map data © OpenStreetMap contributors, available under
  the Open Database Licence. The basemap's tiles come from OpenFreeMap and
  OpenMapTiles, credited on the map.
- **Ordnance Survey:** OS maps are shown with your own OS Data Hub key, under
  Ordnance Survey's terms, with OS's logo and copyright statement on the map.
- **Terrain heights:** heights for routes you draw come from the Terrain
  Tiles open dataset on AWS. The sources it combines are credited in the app
  while heights are shown; the full list is at
  https://github.com/tilezen/joerd/blob/master/docs/attribution.md.
