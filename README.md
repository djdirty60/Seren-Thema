# Nuvio Arc V2 – thema voor Seren

Een donker, cinematisch thema voor de Kodi-add-on **Seren**, in de stijl van **Nuvio Arc V2** (Cinematic Glass): grote achtergronden, glazen panelen, afgeronde kaarten en een witte gloed op de geselecteerde knop.

![Bronkeuze](screenshots/bronkeuze.jpg)

> De afbeeldingen zijn voorbeelden met nep-artwork. In Kodi zie je de echte achtergrond en het echte logo van de film of serie.

---

## Wat zit erin

| Scherm | Wat je ziet |
| --- | --- |
| **Bronkeuze** | Logo, info en beschrijving links; rechts een glazen paneel met alle streams als kaarten, met kwaliteit, provider, debrid, grootte en badges |
| **Streams zoeken** | Voortgangsbalk en aantallen per kwaliteit (4K, 1080p, 720p, SD) en per brontype |
| **Stream openen** | Glazen kaart met laadbalkje en badges van de gekozen stream |
| **Volgende aflevering / Kijk je nog?** | Glazen kaart rechtsonder over de video, met afgeronde afbeelding en aftelbalkje |
| **Handmatig cachen** | Zelfde stijl als de bronkeuze, met het aantal seeds |
| **Download Manager** | Kaart per download met percentage, voortgangsbalk, snelheid en resterende tijd |
| **Achtergrond** | Achtergrondfoto en logo tijdens het laden |

### Badges in plaats van tekst

In plaats van `DV | HDR | ATMOS` toont het thema gekleurde badges, bijvoorbeeld **Dolby Vision**, **HDR**, **HEVC**, **REMUX**, **Atmos**, **TrueHD**, **DTS:X** en **5.1 / 7.1**. Er zijn 40 badges. Elke stream laat alleen zijn eigen badges zien, netjes naast elkaar zonder gaten. Slechte versies (CAM, SCR, HC-subs) zijn rood.

De badges zijn eigen ontwerpen. Het zijn geen officiële logo's van Dolby of DTS.

---

## Schermafbeeldingen

**Streams zoeken**
![Streams zoeken](screenshots/streams-zoeken.jpg)

**Stream openen**
![Stream openen](screenshots/stream-openen.jpg)

**Volgende aflevering**
![Volgende aflevering](screenshots/volgende-aflevering.jpg)

**Handmatig cachen**
![Handmatig cachen](screenshots/handmatig-cachen.jpg)

**Download Manager**
![Download Manager](screenshots/downloads.jpg)

---

## Installeren

### Manier 1: rechtstreeks vanaf GitHub (makkelijkst)

1. Open Seren en ga naar **Gereedschap → Instellingen openen → Interface**.
2. Kies bij Thema's **Thema installeren → Webadres** (*Web Location*).
3. Vul dit adres in (vervang `GEBRUIKER/REPO` door de naam van deze repository):
   ```
   https://github.com/GEBRUIKER/REPO/zipball/main
   ```
4. Seren vraagt of je het thema wilt gebruiken. Kies **Ja**.

### Manier 2: met een zip-bestand

1. Download deze repository als zip (groene knop **Code → Download ZIP**).
2. Zet het bestand op je apparaat, bijvoorbeeld in de map *Download*.
3. Ga in Seren naar **Gereedschap → Instellingen openen → Interface → Thema installeren → Bladeren**.
4. Kies het zip-bestand en daarna **Ja**.

### Terug naar het standaardthema

Ga naar **Gereedschap → Instellingen openen → Interface → Thema wisselen** en kies **Seren Default**.

---

## Goed om te weten

- **Logo's en achtergronden** komen uit Seren zelf (TMDB). Vul in Seren een gratis **Fanart.tv API-sleutel** in voor meer logo's. Is er geen logo, dan staat de titel in grote letters.
- **Lettertype**: het thema gebruikt de lettertypen van je Kodi-skin. Het kan er dus per skin net iets anders uitzien.
- **Niet aangepast**: de vensters voor filteren, sorteren en provider-instellingen. Die blijven in de standaard Seren-stijl.
- Gemaakt voor Seren 3.x (Kodi 21 en 22), schermresolutie 1080p.

---

## Mapstructuur

```
resources/
└── skins/
    ├── meta.json              naam en versie van het thema
    └── Default/
        ├── 1080i/             de vensters (XML)
        └── media/             texturen
            └── flags/         de badges
screenshots/                   afbeeldingen voor deze README
```

Seren verwacht de map `resources/` bovenaan in de zip. Verplaats die dus niet.

---

## Credits

- Geïnspireerd op het ontwerp van [Nuvio Arc](https://github.com/ysosrs123/NuvioTV-Fork). Dit thema is daar niet aan verbonden.
- Gemaakt voor [Seren](https://github.com/nixgates/plugin.video.seren) van Nixgates. Ook daar is dit thema niet aan verbonden.
