# Analiza uticaja pola osiguranika na rizik od saobraćajnih nezgoda

Ovaj projekat koristi podatke iz francuskog auto-osiguranja (`freMTPL2freq.csv`) kako bi analizirao da li pol osiguranika utiče na učestalost saobraćajnih nezgoda.
podaci - https://www.kaggle.com/datasets/floser/french-motor-claims-datasets-fremtpl2freq?resource=download

## Ciljevi
- Identifikovati grupe osiguranika sa sličnim profilima rizika (klasterovanje)
- Predvideti broj šteta koristeći različite klasifikacione metode
- Uporediti performanse modela i proceniti pouzdanost predikcija

## Metode
- **Klasterovanje**: K-means (Silhouette), hijerarhijsko klasterovanje (dendogram)
- **Klasifikacija**: Decision Tree, KNN, Naive Bayes
- **Evaluacija**: Accuracy, Precision, Recall, F1-score

## Struktura projekta
- `klasterovanje/`: Analiza segmenata korisnika
- `klasifikacija/`: Predikcija broja šteta
- `izvestaj/`: Finalni izveštaji, grafikoni i rezultati
