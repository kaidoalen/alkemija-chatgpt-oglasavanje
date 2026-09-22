# Objava na alkemija.com i alkemija.hr

WordPress API ne prima izmjene bez prijave. Ovdje je točan HTML za zalijepiti. Cijena u cjeniku nije izmišljena — stavi satnicu 50 € ili iznos koji odlučiš.

## Stanje (provjera 22. 9. 2026.)

| Mjesto | Status |
| --- | --- |
| [alkemija.com/chatgpt-oglasavanje](https://alkemija.com/chatgpt-oglasavanje/) | objavljeno, s uputama |
| Početna alkemija.com (pločica u paketima) | nije |
| [alkemija.hr/chatgpt-oglasavanje](https://www.alkemija.hr/chatgpt-oglasavanje/) | nije |
| [Cjenik / ponuda](https://www.alkemija.hr/cjenik/) | nije |
| Naslovnica alkemija.hr (uz piluricu) | nije |

## 1. Pločica na početnoj alkemija.com

1. WP alkemija.com → Media → upload `assets/chatgpt-tile.jpg`.
2. Uredi početnu, blok `ak-tiles` pod **paketi za posao**.
3. Zalijepi sadržaj `alkemija-com-plocica.html` kao prvu pločicu, ispred izloga.
4. Ako Media da drugi URL slike, zamijeni `src`.

## 2. Upute na alkemija.hr

1. WP alkemija.hr → Stranice → Dodaj.
2. Naslov: `ChatGPT oglašavanje`. Slug: `chatgpt-oglasavanje`.
3. Custom HTML: zalijepi `alkemija-hr-stranica.html` (bez gornjeg komentara).
4. Objavi. URL treba biti `https://www.alkemija.hr/chatgpt-oglasavanje/`.

## 3. Ponuda / cjenik

Cjenik kaže da oglasi nisu uključeni. Ovo je rad Alkemije, ne medijski budžet.

U tablicu, npr. ispod satnice:

| Naziv — opis | JM | Aktualna | Sidrena |
| --- | --- | --- | --- |
| ChatGPT oglašavanje — postava i vođenje (medijski budžet nije uključen) | sat | 50,00 | 50,00 |

U `cjenik.csv` red:

```csv
Satnica,ChatGPT oglašavanje — postava i vođenje (bez medijskog budžeta),50,sat
```

Na naslovnici alkemija.hr, uz piluricu, isti stil poveznice:

`chatgpt oglašavanje >` → `https://www.alkemija.hr/chatgpt-oglasavanje/`
