# Izbaci imprint sa alkemija.hr (ne diraj naslovnicu)

Makni ovaj red / blok sa svih stranica osim [naslovnice](https://www.alkemija.hr/):

`Alkemija · obrt za dizajn · 3. Pile 10, 10000 Zagreb · OIB 34772291906`

Naslovnica (page id 1479) ostaje kako je.

WordPress API ne prima izmjene bez prijave. U WP-u obriši samo navedene komade.

## Gdje sada stoji (22. 9. 2026.)

| Stranica | Što obrisati | Ne diraj |
| --- | --- | --- |
| [Naslovnica](https://www.alkemija.hr/) | ništa | cijeli footer |
| [Kontakt](https://www.alkemija.hr/kontakt/) | sivi odlomak s obrtom, adresom, OIB-om, MBO, žirom, IBAN-om | tekst „Dobro mi došli…”, telefon, mail |
| [/a/](https://www.alkemija.hr/a/) | isto kao kontakt | isto |
| [Cjenik](https://www.alkemija.hr/cjenik/) | adresa i OIB/MBO u zaglavlju; zadnji red tablice s adresom i OIB-om | naziv, kontakt, red „Podaci za uplatu” |
| [mesmerize](https://www.alkemija.hr/mesmerize/) | sivi centrirani odlomak s obrtom, adresom, OIB-om | ostalo |
| [Blog](https://www.alkemija.hr/blog/) — post [EM](https://www.alkemija.hr/em/) | prvi odlomak (imprint); zato se vidi na blogu | naslovnicu |

Pilurica, web, AI i ostale unutarnje stranice to nemaju.

## 1. Kontakt i /a/

Elementor → tekst widget. Obriši samo drugi odlomak, sivi:

`Alkemija, obrt za dizajn / obrt za usluge – vlasnik Alen Duka, adresa: 3. Pile 10, HR- 10000 Zagreb – OIB: 34772291906, MBO: 97704296, Žiro račun: RBA 2484008-1102197931, IBAN: HR8024840081135008228`

Ostavi prvi odlomak (HVALA, telefon, mail).

## 2. Cjenik

U zaglavlju `alk-mid` ostavi:

```html
<div class="alk-mid">Alkemija<br />vl. Alen Duka<br />info@alkemija.hr<br />+385 98 516 852</div>
```

Blok `alk-right` (OIB, MBO, IBAN) obriši.

Zadnji red tablice (adresa + OIB) obriši. Red „Podaci za uplatu” ostavi.

## 3. mesmerize

Elementor widget `92beead` — cijeli odlomak s OIB-om obriši.

## 4. Blog / post EM

Uredi post EM. Obriši odlomak koji počinje s „Alkemija, obrt za dizajn – vlasnik Alen Duka…”. To je kopija naslovnice; naslovnicu ne diraj.

## 5. Nova stranica ChatGPT

U `alkemija-hr-stranica.html` imprint je već maknut. Ostaju telefon, mail i cjenik.
