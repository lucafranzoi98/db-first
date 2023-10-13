Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

Cars:
<!-- Name | Type - Attribute   >   Example -->
- Serial number | CHAR(17) - PK, NOT NULL, UNIQUE   >   1XXXX11XXXX111111
- Plate | CHAR(7) - NOT NULL, UNIQUE   >   AA000AA
- Brand | VARCHAR(50) - NOT NULL   >   Citroen
- Model | VARCHAR(50) - NULL   >   Berlingo
- Version | VARCHAR(50) - NULL   >   XTR
- Year | YEAR - NULL   >   2010
- Fuel type | VARCHAR(50) - NULL   >   Benzina
- Motor (cm^3) | SMALLINT - NULL -   >   1600
- Power (CV) | SMALLINT - NULL   >   90
- Traction | CHAR(3) - NULL   >   FWD
- Weight (kg) | SMALLINT - NULL   >   1400
- Lenght (cm) | FLOAT(4, 1) - NULL   >   438,2
- Width (cm) | FLOAT(4, 1) - NULL   >   181,8
- Height (cm) | FLOAT(4, 1) - NULL   >   180,0
- Seats | TINYINT - NULL   >   5
- Doors | TINYINT - NULL   >   5
- Color | VARCHAR(50) - NULL   >   Grigio