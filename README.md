# Analiza energetskog potencijala i smanjenja CO2 u Hrvatskoj

Ovaj projekt istražuje potencijal obnovljivih izvora energije (sunce i vjetar) za 10 odabranih gradova u Hrvatskoj te procjenjuje mogući utjecaj na smanjenje emisija CO2 u energetskom sektoru.

## Interaktivna vizualizacija
Glavni rezultat analize je interaktivna karta koja prikazuje energetski potencijal i procijenjene uštede po gradovima:
[**POGLEDAJ INTERAKTIVNU KARTU OVDJE**](https://grgolalic.github.io/energetski-potencijal-rh/energetski_potencijal_RH.html)

## Ključne značajke
- **Web Scraping:** Automatsko prikupljanje podataka o osunčanosti sa službenih stranica DHMZ-a pomoću biblioteke `BeautifulSoup`.
- **Baza podataka:** Strukturiranje i pohrana prikupljenih podataka u `SQLite` bazu podataka (`projekti.db`).
- **Analiza podataka:** Obrada podataka u Pythonu (Pandas) i izračun isplativosti postavljanja solarnih i vjetroelektrana.
- **Geoprostorna vizualizacija:** Izrada karte s prikazom lokacija i izračunatih ušteda pomoću `Folium` biblioteke.

## Korištene tehnologije
- **Programski jezik:** Python 3
- **Biblioteke:** Pandas, BeautifulSoup4, SQLite3, Folium, Matplotlib, Seaborn
- **Podaci:** DHMZ, javni energetski izvori RH

## Kako pokrenuti projekt lokalno
1. Klonirajte ovaj repozitorij na svoje računalo.
2. Osigurajte da imate instalirane potrebne biblioteke (pogledajte `requirements.txt`).
3. Otvorite Jupyter Notebook datoteku: **`analiza_energetskog_potencijala.ipynb`**.

## Rezultati
Projekt identificira gradove s najvišim brojem sunčanih sati i brzinom vjetra, procjenjujući ukupnu godišnju uštedu od približno **5640 tona CO2** na analiziranim lokacijama.
