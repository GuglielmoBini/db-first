CARS

| COLONNE           | TYPES       | INDICI      | ATTRIBUTI                        |
| ----------------- | ----------- | ----------- | -------------------------------- |
| ID                | BIGINT      | PRIMARY KEY | NOT NULL, UNIQUE, AUTO_INCREMENT |
| MARCA             | VARCHAR(30) |             | NOT NULL                         |
| MODELLO           | VARCHAR(50) |             | NOT NULL                         |
| COLORE            | VARCHAR(20) |             | NOT NULL                         |
| TARGA             | CHAR(7)     |             | NOT NULL, UNIQUE                 |
| IMMATRICOLAZIONE  | DATE        |             | NOT NULL                         |
| ANNO PROD         | YEAR        |             | NOT NULL                         |
| PREZZO ACQ.       | FLOAT(8,2)  |             | NULL                             |
| PREZZO VEN.       | FLOAT (8,2) |             | NOT NULL                         |
| ALIMENTAZIONE     | CHAR(1)     |             | NOT NULL                         |
| CAP. SERBATOIO    | CHAR(2)     |             | NULL                             |
| CILINDRATA        | VARCHAR(4)  |             | NOT NULL                         |
| POTENZA           | VARCHAR(4)  |             | NOT NULL                         |
| TRAZIONE          | CHAR(3)     |             | NOT NULL                         |
| CAMBIO            | CHAR(1)     |             | NOT NULL                         |
| N. MARCE          | VARCHAR(8)  |             | NOT NULL                         |
| CONSUMO MEDIO     | VARCHAR(2)  |             | NULL                             |
| CHILOMETRI        | MEDIUMINT   |             | NOT NULL                         |
| STATO (1-10)      | VARCHAR(2)  |             | NOT NULL                         |
| INCIDENTI         | TINYINT(1)  |             | NOT NULL, DEFAULT = 0            |
| PROPRIETARI PREC. | CHAR(1)     |             | NULL                             |
| N. POSTI          | CHAR(1)     |             | NOT NULL                         |
| N. PORTE          | CHAR(1)     |             | NOT NULL                         |
| CAP. BAGAGLIAIO   | CHAR(2)     |             | NULL                             |
| DISPONIBILE       | TINYINT(1)  |             | NOT NULL, DEFAULT = 1            |
| OPTIONAL          | TINYINT(1)  |             | NULL                             |
| NOTE              | TEXT        |             | NULL                             |
