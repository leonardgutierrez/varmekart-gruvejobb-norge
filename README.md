# 🗺️ Varmekart over den geografiske fordelingen av ansatte i gruvesektoren i Norge  
### *Heat map of the geographical distribution of employees in the mining sector in Norway*

**Analyse og visualisering av den geografiske fordelingen av ansatte i norsk gruvesektor ved bruk av åpne data og datavitenskapsverktøy.**  
**Analysis and visualization of the geographical distribution of employees in the Norwegian mining sector using open data and data science tools.**

---

## 📘 Generell Beskrivelse – General Description  
Dette prosjektet søker å analysere hvordan ansatte i gruvesektoren (05–09 Gruvedrift og utvinning) er geografisk fordelt i ulike regioner i Norge, ved hjelp av åpne data fra **Statistisk sentralbyrå (SSB)**.  

This project seeks to analyze how employees in the mining sector (05–09 Mining and Quarrying) are geographically distributed in different regions of Norway, using open data from **Statistics Norway (SSB)**.  

Ved hjelp av grunnleggende geografisk databehandling og visualiseringsteknikker genereres et **interaktivt varmekart** som gjør det mulig å observere regionale trender og mønstre i ansattfordelingen i den norske gruvesektoren.  
Using basic geographic data processing and visualization techniques, an **interactive heat map** is generated that allows observing regional trends and patterns in employee distribution in the Norwegian mining sector.

---

## 🎯 Mål – Objectives  

**På norsk:**  
- Forstå den geografiske fordelingen av gruvearbeidere i Norge.  
- Visualiser data interaktivt ved hjelp av Google Colab og Python.  
- Utvikle et omfattende og dokumentert datavitenskapsprosjekt som kan brukes som en del av en profesjonell portefølje.  

**En español:**  
- Comprender la distribución geográfica de los empleados en minería en Noruega.  
- Visualizar los datos de forma interactiva utilizando Google Colab y Python.  
- Desarrollar un proyecto completo y documentado de Ciencia de Datos que sirva como parte del portafolio profesional.  

**In English:**  
- Understand the geographic distribution of mining employees in Norway.  
- Visualize data interactively using Google Colab and Python.  
- Develop a comprehensive and documented Data Science project that can be used as part of a professional portfolio.

---

## 🧠 Metodikk – Methodology  
1. **Datainnsamling / Data collection:** last ned fra [SSB.no](https://www.ssb.no/arbeid-og-lonn/sysselsetting/statistikk/arbeidskraftundersokelsen)  
2. **Behandling / Processing:** Datarensing, normalisering og filtrering *(05–09 Mining and Quarrying)*  
3. **Geografisk integrasjon / Geographic integration:** Datakobling med GeoJSON-filer fra norske fylker *(data linking with GeoJSON files of Norwegian provinces)*  
4. **Utstilling / Visualization:** Generering av interaktive varmekart med *Plotly* og *Geopandas*  

---

## 🧰 Verktøy som brukes – Tools Used  
- **Python** (`pandas`, `geopandas`, `plotly`, `folium`, `matplotlib`)  
- **Google Colab** – analyse- og utførelsesmiljø *(analysis and execution environment)*  
- **GitHub** – versjonskontroll og prosjektpublisering *(version control and project publishing)*  
- **Data åpne fra SSB** – open data from Statistics Norway  

---

## 📁 Repositorystruktur – Repository Structure  
📁 **Repositorystruktur - Repository structure**

```bash
varmekart-gruvejobb-norge/
│
├── notebooks/
│   └── 1_data_processing_varmekart.ipynb   ← Hovedanalyse – Principal analysis
├── README.md                               ← This file – Denne filen
├── LICENSE                                 ← MIT-lisens - MIT license
└── .gitignore                              ← Utelukkelse av midlertidige filer - Exclusion of temporary files
```
---

## ⚙️ Hvordan man skal gjennomføre prosjektet – How to Execute the Project  
1. Åpne notatboken i **Google Colab**. *(Open the notebook in Google Colab.)*  
2. Koble den til **Google Drive-kontoen din.** *(Connect it to your Google Drive account.)*  
3. Kjør celler trinn for trinn *(fra import til visning).*  
4. Observer det interaktive varmekartet som genereres i den siste blokken. *(Observe the interactive heat map generated in the final block.)*

---

## 📊 Forventede resultater – Expected Results  
Hovedresultatet vil være et **interaktivt varmekart** som viser konsentrasjonen av gruvearbeidsplasser per region eller fylke i Norge, basert på historiske SSB-data.  
Dette prosjektet har som mål å tjene som et eksempel på tilgjengelig og reproduserbar geospatial analyse.  

The main result will be an **interactive heat map** showing the concentration of mining jobs per region or county in Norway, based on historical SSB data. This project aims to serve as an example of accessible and reproducible geospatial analysis.  

---

## 🧾 Tillatelse – License  
Dette prosjektet distribueres under **MIT-lisensen**, som tillater fri bruk til pedagogiske eller profesjonelle formål, med korrekt kreditering.  
This project is distributed under the **MIT License**, allowing its free use for educational or professional purposes, with proper attribution.  

---

## ✍️ Forfatter – Author  
**Leonard Gutiérrez**  
Prosjektet er utviklet som en del av mikroprosjektinitiativet for personlig datavitenskap og forretningsintelligens.  
Project developed as part of the personal microproject initiative in Data Science and Business Intelligence.  
