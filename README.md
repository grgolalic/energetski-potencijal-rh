# Analiza energetskog potencijala i smanjenja CO2 u Hrvatskoj

Ovaj projekt istražuje potencijal obnovljivih izvora energije (sunce i vjetar) za 10 odabranih gradova u Hrvatskoj te procjenjuje mogući utjecaj na smanjenje emisija CO2.

## Ključne značajke
- **Web Scraping:** Automatsko prikupljanje podataka o osunčanosti sa stranica DHMZ-a.
- **Baza podataka:** Pohrana i strukturiranje podataka pomoću SQLite-a.
- **Analiza podataka:** Obrada podataka u Pythonu (Pandas) i izračun energetskog potencijala.
- **Vizualizacija:** Interaktivna karta (Folium) s prikazom lokacija i ušteda.

## Korištene tehnologije
- **Python** (Pandas, BeautifulSoup, SQLite3)
- **Vizualizacija:** Folium, Matplotlib, Seaborn
- **Podaci:** DHMZ, javno dostupni energetski izvori

## Kako pokrenuti projekt
1. Klonirajte repozitorij.
2. Otvorite `GrgoLalic.ipynb` u Jupyter Notebooku ili Google Colabu.
3. Osigurajte da je datoteka `projekti.db` u istom direktoriju.

## Rezultati
Analiza pokazuje da bi strateško postavljanje elektrana na analiziranim lokacijama moglo uštedjeti približno **5640 tona CO2** godišnje.
