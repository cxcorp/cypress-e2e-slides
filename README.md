# cypress-e2e-slides

Ohjelmistotuotantoprojektikurssin aikana pidetyn Cypress & E2E-testaus -esityksen slidet. Esityksen kohderyhmä on toisen tai kolmannen vuoden opiskelijat HY:llä.

Slidet verkossa (paina S-näppäintä avataksesi muistiinpanot):

https://cypress-e2e-esitys.heikkila.dev

## Branchit

Sorsat `master`:issa, Zeit now:lla tuotannossa oleva versio `static`-branchillä

## Buildaus

Asenna ensin `reveal-md` npm:stä (`npm i -g reveal-md`).

Kehitysmoodi live-reloadilla:

```
reveal-md --theme robot-lung.css --template reveal.html --css slides.css -- slides.md
```

Static buildi tuotantoa varten:

```
reveal-md --theme robot-lung.css --template reveal.html --css slides.css --static -- slides.md
```

Static buildin jälkeen saattaa joutua kopioimaan assetit+css:ät + muokata template manuaalisesti sisään, en jaksanut tutkia oikeita komentorivivipuja.
