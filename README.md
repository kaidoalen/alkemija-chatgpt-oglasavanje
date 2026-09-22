# ChatGPT oglašavanje — Alkemija

Statička landing stranica na hrvatskom za uslugu **ChatGPT oglašavanje**. Alkemija postavlja i vodi kampanje: račun, mjerenje, kreativa i mjesečni izvještaj.

Vizual prati početnu [alkemija.com](https://alkemija.com/): tamna podloga, Roboto, narančasti akcent. Svaka stavka u blokovima „Paketi za posao” i „Programi” ima poveznicu, kratak opis i malu grafiku, isto kao na početnoj. Grafike ostalih stavki preuzete su s alkemija.com. Grafika za ChatGPT oglašavanje napravljena je za ovu stranicu.

Kontakt: [info@alkemija.hr](mailto:info@alkemija.hr), [alkemija.hr](https://www.alkemija.hr/), [upitnik](https://www.alkemija.hr/anketa/).

Stranica ne skuplja osobne podatke i ne traži lozinku.

## Pokretanje lokalno

U mapi repozitorija:

```bash
python3 -m http.server 8080
```

Otvorite [http://localhost:8080](http://localhost:8080).

Datoteka `index.html` može se otvoriti i izravno u pregledniku. Lokalni poslužitelj je pouzdaniji za fontove i relativne putanje.

Nema instalacije ni build koraka.

## Objava

Stranica je statička (`index.html`, `styles.css`, mapa `assets`). Sprema je GitHub Pages i Netlify.

### GitHub Pages

1. Na GitHubu otvorite **Settings → Pages**.
2. **Build and deployment → Source:** Deploy from a branch.
3. Branch: `main`, mapa: `/` (root).
4. Spremite. Stranica će biti na `https://kaidoalen.github.io/alkemija-chatgpt-oglasavanje/`.

U `index.html` su canonical i Open Graph adresa već postavljeni na taj URL. Ako stranica ide na drugu domenu, zamijenite ih.

### Netlify

Povucite repozitorij. Publish directory je korijen (`.`). Build command ostavite prazan.

## Sadržaj stranice

1. Hero — ChatGPT oglašavanje, napomena o besplatnom paketu i paketu Go, kontakt
2. Uključene usluge
3. Što je ChatGPT oglašavanje
4. Dostupnost u Hrvatskoj
5. Modeli naplate
6. Ciljanje
7. Mjerenje konverzija
8. Format oglasa
9. Usporedba s Google Adsom
10. Kome se isplati
11. Priprema weba
12. Trajanje i očekivanja
13. Paketi i programi s početne alkemija.com
14. Footer i kontakt
