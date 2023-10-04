# Database Concessionario

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.

| COLONNA               | TIPO          | ATTRIBUTI                            |
| --------------------- | ------------- | ------------------------------------ |
| ID AUTO               | BIGINT        | INCREMENT-PRIMATY KEY-AUTO_INCREMENT |
| IMMAGINE              | TEXT          | NOTNULL                              |
| MARCA                 | VARCHAR(50)   | NOTNULL                              |
| MODELLO               | VARCHAR(50)   | NOTNULL                              |
| ANNO DI FABBRICAZIONE | YEAR          | NOTNULL                              |
| KM                    | INT-UNSIGNED  | NULL                                 |
| CARBURANTE            | CHAR (30)     | NOTNULL                              |
| DESCRIZIONE           | TEXT          | NULL                                 |
| PREZZO                | DECIMAL (7,2) | NULL                                 |
