# Vessapaperien hintavertailu

UX/UI konseptiprojekti suomalaiselle vessapaperien hintavertailupalvelulle.

Tavoitteena oli suunnitella selkeä käyttöliittymä, joka auttaa käyttäjiä vertailemaan tuotteita nopeasti ja tekemään paremman ostopäätöksen.

---

# Ongelma

Vessapaperipakkausten vertailu on vaikeaa, koska pakkauksissa on eri määrä:

- rullia  
- arkkeja  
- kerroksia  

Pelkkä paketin hinta ei kerro todellista arvoa.

Esimerkiksi kaksi pakkausta voi maksaa saman verran, mutta sisältää hyvin eri määrän paperia.

---

# Ratkaisu

Palvelu normalisoi hinnan mittariksi:

**€/100 arkkia**

Tämä mahdollistaa tuotteiden todellisen vertailun.

Käyttäjä voi nopeasti nähdä:

- mikä tuote on halvin per arkki  
- missä tuotteessa on paras hinta-laatusuhde  
- mitkä tuotteet ovat tarjouksessa  

---

# Keskeiset ominaisuudet

### Tuotevertailu
Tuotteet esitetään vertailutaulukossa, jossa näkyy:

- rullien määrä  
- arkkien määrä  
- kerrosten määrä  
- valmistusmaa  
- €/100 arkkia  
- hinta  
- käyttäjäarvosanat  

---

### Suodattimet

Käyttäjä voi suodattaa tuotteita esimerkiksi:

- hinnan mukaan  
- rullien määrän mukaan  
- arkkien määrän mukaan  
- kerrosten mukaan
- valmistusmaa

---

### Tarjoukset

Erillinen **Tarjoukset-näkymä** nostaa esiin tuotteet, joissa on suurin säästö.

---

### Käyttäjäarvostelut

Tuotteita voidaan arvioida:

- tähtiarvosteluilla (1–5)
- kommenteilla

---

### Badge-järjestelmä

Tuotteet voivat saada erityisiä merkintöjä:

- 🌱 **Vastuullinen valinta**  
- 🏆 **Laatuluolalle**  
- 💰 **Budjettipyllylle**

Badge auttaa käyttäjää tunnistamaan tuotteiden vahvuudet nopeasti.

---

# UX Insights

Projektin keskeinen UX-oivallus oli, että käyttäjät eivät oikeasti vertaa pakkausten hintaa, vaan **paperin todellista määrää**.

Siksi käyttöliittymä korostaa metriikkaa:

**€/100 arkkia**

Tämä tekee tuotteiden vertailusta huomattavasti helpompaa.

---

# Prototype

Figma prototype:

https://www.figma.com/make/5CLS1jKvjJLRuzSzanPLSI/Vessapaperien-hintavertailu-UI?t=TXw7vuYgJVDB3dFa-1

---

# Screenshots

## Etusivu
![Homepage](design/screenshots/homepage.png)

## Tuotelistaus
![Products](design/screenshots/product-list.png)

## Vertailu
![Comparison](design/screenshots/comparison.png)

## Tarjoukset
![Offers](design/screenshots/offers.png)

---

# Teknologiat

Projektissa käytetyt työkalut:

- Figma
- Figma Make
- GitHub

---

# Projektin tavoite

Tämä projekti on UX/UI konseptiharjoitus, jonka tarkoituksena on demonstroida:

- käyttöliittymäsuunnittelua
- datavertailun UX:ää
- päätöksentekoa tukevia käyttöliittymiä
