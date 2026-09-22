# Objava na alkemija.com i alkemija.hr

WordPress API ne prima izmjene bez prijave. Ovdje je točan HTML za zalijepiti. Cijena u cjeniku nije izmišljena — stavi satnicu 50 € ili iznos koji odlučiš.

## Stanje (objavljeno 22. 9. 2026.)

| Mjesto | Status |
| --- | --- |
| [alkemija.com/chatgpt-oglasavanje](https://alkemija.com/chatgpt-oglasavanje/) | objavljeno |
| Početna alkemija.com (pločica) | objavljeno |
| [alkemija.hr/chatgpt-oglasavanje](https://www.alkemija.hr/chatgpt-oglasavanje/) | objavljeno, s uputama, bez imprinta |
| [Cjenik](https://www.alkemija.hr/cjenik/) | objavljeno (sat, 50 €, bez medijskog budžeta) |
| Naslovnica alkemija.hr (ispod pilurice) | objavljeno |

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

Na naslovnici alkemija.hr, odmah ispod pilurice, isti stil kao „priprema newslettera i web izloga >”:

`chatgpt oglašavanje >` → `https://alkemija.com/chatgpt-oglasavanje/`

Točan HTML: `alkemija-hr-naslovnica-link.html`. Kad bude živa stranica na alkemija.hr, zamijeni href u `/chatgpt-oglasavanje/`.
