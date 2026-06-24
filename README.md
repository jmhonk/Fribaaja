# Fribaaja

Fribaaja on Android-sovellus frisbeegolfin pisteidenlaskuun. Suunniteltu käytettäväksi kierroksen aikana kentällä — nopea, selkeä ja toimii offline.

## Ominaisuudet

### Kierroksen pelaaminen
- **Pisteiden syöttö** väylä kerrallaan, tuki OB-merkinnöille
- **Tulostaulukko** reaaliajassa kierroksen aikana
- **Heittoalijärjestys** lasketaan automaattisesti väylän tulosten perusteella
- **Kierroksen keskeyttäminen** ilman tallennusta
- **Laskentatyyli** — Zero (laskenta nollasta) tai Par (laskenta par-arvosta)

### Pelaajat & radat
- **Usean pelaajan tuki** — lisää pelaajia tallennetusta listasta tai luo uusia
- **Radat** — tallenna omia ratoja väyläkohtaisine pareineen (1–36 väylää)
- **Suosikit** — tähtimerkkaa usein käytetyt pelaajat ja radat

### Historia & tilastot
- **Historia** — kaikki pelatut kierrokset tallentuvat, selattavissa väylä kerrallaan
- **Kierrostilastot** — birdie, eagle, holari, OB, par, bogey ym. kierroksen päätyttyä
- **Pelaajatilastot** — kehityksen seuranta, parhaat kierrokset, ratakohtaiset tilastot

### Käyttöliittymä
- **Pyyhkäisynavigointi** — siirry näkymien välillä pyyhkäisemällä vasemmalle tai oikealle
- **Pohjanavigaatio** — 5 välilehteä: Pelaajat, Radat, Kierros, Historia, Tilastot
- **Kieli** — suomi ja englanti
- **Teema** — tumma ja vaalea, valittava korostusväri
- **Haptinen palaute** — värinäpalaute nappeja painettaessa (kytkettävissä pois)

### Tiedot
- **Varmuuskopiointi** — vie ja tuo kaikki data JSON-tiedostona

## Tekniikka

- Flutter (Dart)
- Provider — tilanhallinta
- SharedPreferences — paikallinen tallennus
- Google Fonts (Poppins)
- Kohdeympäristö: Android

## Lataus

**Liity google ryhmän jäseneksi tästä:** https://groups.google.com/g/fribaaja-closed-beta
**Sen jälkeen voit ladata appin Play-storesta:** https://play.google.com/store/apps/details?id=fi.fribaaja.app
