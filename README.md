# yg-media

Beelden voor de opening van [yg-digital.nl/eerste-ontwerp](https://www.yg-digital.nl/eerste-ontwerp), geserveerd via GitHub Pages:
`https://steinclaude.github.io/yg-media/werelden/`.

- `werelden/werelden.json`: per wereld de sleutel, naam, kop en beeldbestanden. Het fragment op de site leest dit bestand bij het openen.
- `werelden/<sleutel>-1600.webp|jpg`: liggend beeld, 1600x900, voor schermen vanaf 768 px breed.
- `werelden/<sleutel>-tel.webp|jpg`: staand beeld, 900x1600, voor telefoons.

Alleen stills, geen video. Bron en werkwijze: `yg-luxury/droom/LEESMIJ.md`; bijwerken met
`node tools/werelden-media.cjs` en `node tools/werelden-publiceer.cjs` in yg-luxury.
