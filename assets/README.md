# App Icons

Verified October 15, 2026. Eduardo requested the same icons as the real App Store.
The three JPEGs are unmodified 512 x 512 images downloaded from the official
`artworkUrl512` returned by Apple's lookup API for the listed app IDs.
They are served locally to avoid depending on a remote image request for each visitor.
CSS displays the complete image at 48 x 48, without cropping its artwork.

| File | App | Apple App Store ID |
|---|---|---|
| `passport-party.jpg` | Passport Party | `6765947275` |
| `sqllearn.jpg` | SQLlearn | `6762401475` |
| `pythonplayroom.jpg` | PythonPlayroom | `6762590223` |
| `roundtable-ai.png` | Roundtable AI | Existing approved Roundtable store asset |
| `nordo-wordmark.jpg` | NORDO | Existing website header wordmark |

## Official Sources

- Lookup: https://itunes.apple.com/lookup?id=6765947275,6762401475,6762590223&country=us
- Passport Party: https://is1-ssl.mzstatic.com/image/thumb/Purple221/v4/74/28/2a/74282ab2-0bc9-3bb5-ca27-8c85144fbc02/AppIcon-0-0-1x_U007ephone-0-1-85-220.png/512x512bb.jpg
- SQLlearn: https://is1-ssl.mzstatic.com/image/thumb/Purple211/v4/8d/30/47/8d30477f-5d82-a7fc-7f8b-ae83cec04119/AppIcon-0-0-1x_U007epad-0-1-85-220.png/512x512bb.jpg
- PythonPlayroom: https://is1-ssl.mzstatic.com/image/thumb/Purple221/v4/74/b1/4f/74b14ff7-3b28-2b4f-72b2-7e6ec0026ec9/AppIcon-0-0-1x_U007epad-0-1-85-220.png/512x512bb.jpg

Roundtable's PNG is an unchanged copy of its approved `google-play-assets/icon.png`.
NORDO does not have App Store artwork. Its existing text wordmark was captured
directly from the visible header at https://nordo.skin/ using a browser screenshot
of only that logo (100 x 44 JPEG, including its existing dark background).
No AI generation, redraw, image editing or new font dependency was used.
