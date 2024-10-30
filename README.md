# Talojen Hintojen Ennustusprojekti

Tämän projektin tavoitteena on ennustaa talojen hintoja eri ominaisuuksien perusteella koneoppimistekniikoita hyödyntäen. Projektissa käytetään **House Price Prediction Treated Dataset** -aineistoa, joka on saatavilla Kagglesta ja sisältää kattavat tiedot eri talon ominaisuuksista ja myyntihinnoista.

## Sisällysluettelo

1. [Projektin Yleiskuvaus](#projektin-yleiskuvaus)
2. [Data](#data)
3. [Asennus](#asennus)
4. [Käyttö](#käyttö)
5. [Projektin Rakenne](#projektin-rakenne)
6. [Osallistuminen](#osallistuminen)
7. [Lisenssi](#lisenssi)

## Projektin Yleiskuvaus

Projektin tarkoituksena on analysoida talotietoja ja soveltaa koneoppimismalleja ennustamaan talon hintaa eri tekijöiden, kuten neliömäärän, sijainnin ja makuuhuoneiden lukumäärän, perusteella. Analysoimalla ja visualisoimalla näiden tekijöiden ja hintojen välistä suhdetta voidaan kehittää malli tarkkojen hintojen ennustamiseen.

## Data

- **Data-aineisto:** [House Price Prediction Treated Dataset](https://www.kaggle.com/datasets/aravinii/house-price-prediction-treated-dataset/data)
- **Ominaisuudet:** Sisältää yksityiskohtaiset tiedot talon ominaisuuksista, kuten koosta, kunnosta ja naapurustosta.
- **Kohdemuuttuja:** Talon myyntihinta.

Lataa aineisto Kagglesta ja tallenna se projektihakemistoon `data/house_data.csv` nimellä.

## Asennus

1. Kloonaa tämä arkisto omalle koneellesi:
    ```bash
    git clone https://github.com/Mainm0e/Asuntojen-hintojen-ennustaminen-datan.git
    cd house-price-prediction
    ```
2. Asenna Python ja Jupyter Notebook, jos niitä ei ole asennettu:
    ```bash
    pip install jupyter
    ```
3. Asenna tarvittavat Python-kirjastot:
    ```bash
    pip install -r requirements.txt
    ```

## Käyttö

1. **Avaa Jupyter Notebook:**
   ```bash
   jupyter notebook house_price_prediction.ipynb
   ```
2. **Suorita notebookin solut**:
   - Lataa ja esikäsittele aineisto.
   - Suorita eksploratiivinen datanalyysi (EDA) visualisointien avulla.
   - Kouluta ja arvioi koneoppimismallit talojen hintojen ennustamiseksi.

## Projektin Rakenne

```plaintext
house-price-prediction/
├── data/
│   └── house_data.csv               # Data-aineisto
├── notebooks/
│   └── house_price_prediction.ipynb # Pääasiallinen Jupyter Notebook
├── README.md                        # Projektin dokumentaatio
└── requirements.txt                 # Python-riippuvuudet
```

## Osallistuminen

Kaikki ovat tervetulleita osallistumaan! Forkkaa arkisto ja luo pull request ehdottaaksesi muutoksia.

## Lisenssi

Tämä projekti on avoimen lähdekoodin ja saatavilla [MIT-lisenssin](LICENSE) alaisuudessa.
