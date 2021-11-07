# Metadata guide

## Dane w tym pliku csv zawierają informacje na temat zakupu odkurzaczy w województwie świętokrzystkim. Informacje dotyczą klientów, którzy dokonali zakupu a także wystawionych przez nich ocen zakupionego sprzętu.

## Informacje potrzebne w celu łatwiejszego zrozumienia danych:

Header | Definition
---|---------
Unnamed | int - numer id;
Dni od zakupu | int - liczba dni, które minęły od zakupu (względna);
Marka | string - nazwa producenta kupionego odkurzacza;
Wiek kupującego  | float - wiek osoby, która zakupiła odkurzacz;
Płeć kupującego | string - płeć klienta: K - kobieta, M - mężczyzna, bd. - brak danych;
Ocena | float - Ocena odkurzacza wystawiona przez kupującego w skali 0 - 5 z krokiem 0.5 tj. (0, 0.5, 1, 1.5 ...).

## Lokalizacja oryginalnych plików
Dane zostały pobrane z [here](https://github.com/KAIR-ISZ-ADB/laboratorium-6-kmotyka00).