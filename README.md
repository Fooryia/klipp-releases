# Klipp

Skjermbilde, video og rullebilde med enkel markering: piler, bokser, sladd, tekst og nummerering. For Windows og Mac.

Her ligger bare installasjonsfilene.

## Last ned

Gå til **[siste utgave](https://github.com/Fooryia/klipp-releases/releases/latest)** og hent filen under «Assets»:

- **Windows:** `Klipp-Setup-<versjon>.exe`
- **Mac (M-brikke):** `Klipp-<versjon>-arm64.dmg`

## Windows

Kjør filen. Den installerer for din bruker uten administratorrettigheter og starter Klipp.

- Programmet er ikke signert, så Windows kan vise «Windows beskyttet PC-en din». Velg **Mer info** og **Kjør likevel**.
- På Windows 11 kan PrtSc være tatt av Utklippsverktøyet. Da står det «er opptatt» i Klipp. Bytt hurtigtast under Innstillinger i Klipp, eller slå av «Bruk Print Screen-tasten til å åpne skjermklipp» i Windows.

## Mac

Åpne `.dmg`-filen og dra Klipp til Programmer.

- Appen er ikke signert hos Apple, så macOS stopper den første gang. Åpne **Systeminnstillinger > Personvern og sikkerhet**, bla ned og velg **Åpne likevel**.
- Første gang du tar et bilde ber macOS om tilgang til skjermopptak. Slå på Klipp samme sted, under **Skjermopptak**, og start Klipp på nytt.

## Oppdateringer

Klipp sier selv fra når en ny utgave er ute, med en knapp nederst i vinduet. På Windows oppdaterer den seg selv når du klikker. På Mac åpner den denne siden.

## Lisens for ffmpeg

Klipp bruker [ffmpeg](https://ffmpeg.org) til videoklipping og GIF. ffmpeg følger med som et eget program og er lisensiert under GPL versjon 3. Kildekoden finnes på [ffmpeg.org/download.html](https://ffmpeg.org/download.html), og bygget som følger med kommer fra [ffmpeg-static](https://github.com/eugeneware/ffmpeg-static).
