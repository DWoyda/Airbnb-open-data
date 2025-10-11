# Airbnb-open-data
## Opis projektu

Ten projekt to krótka, edukacyjna analiza danych **Airbnb Open Data**. Celem jest przejście pełnego mini-workflow data science: od wstępnego audytu surowych danych, przez proste czyszczenie, eksplorację i KPI rynku, aż po bazowy model (np. regresję ceny) i prostą wizualizację na mapie.

## Zakres
- **Audyt RAW:** rozmiary, braki, duplikaty, podstawowe kontrole jakości (ceny ≥ 0, daty parsowalne).
- **Czyszczenie:** poprawa typów, usunięcie oczywistych outlierów, domknięcie najprostszych braków.
- **EDA + KPI:** rozkład cen, porównanie typów pokoi i dzielnic, proste korelacje.
- **Model baseline (opcjonalnie):** przewidywanie ceny z podstawowych cech.
- **Mapa (opcjonalnie):** poglądowe rozmieszczenie ofert i cen.

## Dane
Zestaw: [Airbnb Open Data (Kaggle)](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata/data)  
Typowe kolumny: `id, neighbourhood, latitude, longitude, room_type, price, minimum_nights, number_of_reviews, last_review, reviews_per_month, availability_365`.

## Wynik
- Oczyszczony zbiór `data/processed/clean.parquet`.
- 5–7 prostych wykresów (PNG) i krótkie wnioski w `reports/summary.md`.
- (Opcjonalnie) model bazowy + metryki oraz mapka poglądowa.

