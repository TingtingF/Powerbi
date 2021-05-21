# PBIversjonKontroll

## --Prøve å gjøre versjonkontroll for Power BI: versjonkontroll av meausres og beregnet kolonner, men ikke for visualisering.

### 1. Lagre pbixfil til pbitfil
### 2. Endre pbitfil til zip
### 3. I zipfil ligger en fil som heter DataModelSchema
### 4. Denne DataModelSchema fil er metadata for pbixfil, som inkluderer all info om measure og kolonne.
### 5. Åpne denne filen via text editor, lagre som txt(UTF-8).
### 6. Derfor kan denne filen brukes for versjonkontroll via git
### 7. For å spore endring av hele pbixfil, kan pbitfil lastes opp på github for å lagre hele historikken til hvordan pbixfil har utviklet seg, og gå tilbake til hvilket som helst commit-punkt.

Denne jobben er inspirert av kildet: https://www.kasperonbi.com/how-to-change-the-dataset-script-in-power-bi-desktop/
