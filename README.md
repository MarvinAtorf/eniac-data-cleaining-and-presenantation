# Discount- & Umsatzanalyse (ENIAC)

Dieses Projekt analysiert das **Rabattverhalten im E-Commerce** und dessen Einfluss auf Umsatz und Produktkategorien.  
Der Schwerpunkt liegt auf **Datenbereinigung, Feature Engineering und explorativer Datenanalyse** mit Python.

Ziel ist es, aus heterogenen Rohdaten eine **belastbare Analysegrundlage** zu schaffen und daraus **geschäftsrelevante Erkenntnisse** abzuleiten.

---

## Projektziel

- Bereinigung und Standardisierung mehrerer Rohdatensätze
- Identifikation und Behebung von Datenqualitätsproblemen
- Aufbau eines konsolidierten Master-Datensatzes
- Analyse von Rabattstruktur und Rabattintensität
- Unterstützung datenbasierter Pricing- und Margenentscheidungen

---

## Projektstruktur

Die Repository-Struktur ist bewusst klar und analyseorientiert aufgebaut:

```text
.
├─ data/
│  ├─ raw/          # Unveränderte Rohdaten (CSV-Dateien)
│  └─ clean/        # Bereinigte und aufbereitete Datensätze
│
├─ notebooks/
│  └─ eniac_disc_analysis.ipynb
│     # Datenbereinigung, Feature Engineering und Analyse
│
├─ powerpoint/
│  └─ presentation.pptx
│     # Management- und Business-Präsentation der Ergebnisse
│
├─ .gitattributes
│  # Git-Konfiguration (z. B. für Notebook-Handling)
│
└─ README.md
