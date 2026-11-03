# fzt-showcase

Interactive browser demo of [fzt](https://forgejo.romaine.life/romaine-life/fzt),
using its Go engine compiled to WASM. The public demo remains at
[fzt.romaine.life](https://fzt.romaine.life).

Forgejo Actions downloads the released fzt-browser assets during the build and
deploys the complete bundle to Azure Static Web Apps. The browser loads its WASM,
JavaScript, fonts and styles from the public demo hostname.
