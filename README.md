# Electricity Cost Calculator

En webbasert løsning for å beregne og dokumentere strømkostnader for en leietaker.

Prosjektet er allerede påbegynt og har et fungerende grunnlag, men skal videreutvikles med fokus på bedre brukervennlighet, tydeligere beregninger og enklere tilgang for flere brukere.

## Formål

Målet med løsningen er å gjøre det enkelt å beregne hvor mye en leietaker skal betale for sitt strømforbruk.

Løsningen skal være:

* enkel å forstå
* enkel å bruke
* tydelig på hvordan beløpet beregnes
* tilgjengelig på tvers av enheter
* mulig å dele med flere brukere
* egnet for videreutvikling

## Dagens status

Prosjektet har allerede et grunnlag for selve appen/nettsiden.

Neste fase handler hovedsakelig om å forbedre:

* brukergrensesnitt
* navigasjon
* tilgjengelighet
* beregningsflyt
* visning av resultater
* deling og publisering
* støtte for flere brukere

## Grunnidé

Brukeren skal kunne legge inn informasjon om strømforbruk og få beregnet kostnaden for en bestemt periode.

Eksempel på informasjon som kan legges inn:

* startdato
* sluttdato
* målerstand ved periodens start
* målerstand ved periodens slutt
* strømpris
* eventuelle faste kostnader
* nettleie
* andre relevante kostnader

Systemet skal deretter beregne forbruk og total kostnad.

## Eksempel

```text
Periode:
01.08.2026 – 31.08.2026

Målerstand start:
12 450 kWh

Målerstand slutt:
12 732 kWh

Forbruk:
282 kWh
```

Eksempel på resultat:

```text
Strømforbruk:
282 kWh

Strømkostnad:
243,18 kr

Nettleie:
171,40 kr

Andre kostnader:
44,92 kr

-------------------------

Totalt:
459,50 kr
```

## Transparente beregninger

En viktig del av prosjektet er at brukeren ikke bare skal få opp et sluttbeløp.

Løsningen bør også vise hvordan beregningen er gjort.

Eksempel:

```text
282 kWh × 0,862 kr/kWh = 243,08 kr
```

Dette gjør beregningen lettere å forstå, kontrollere og dokumentere.

## Funksjoner jeg ønsker å videreutvikle

### Beregning

* Automatisk beregning av forbruk
* Strømpris per kWh
* Nettleie
* Faste kostnader
* Avgifter
* Eventuell strømstøtte
* Totalbeløp
* Beregning for valgfri periode

### Brukervennlighet

* Enklere og mer intuitivt brukergrensesnitt
* Tydelige feltnavn
* Forklaring av hva som skal fylles inn
* Automatisk validering av tall
* Feilmeldinger som er enkle å forstå
* Tydelig resultatvisning
* God visning både på mobil og PC

### Historikk

På sikt kan løsningen lagre tidligere beregninger.

Eksempel:

| Periode        | Forbruk |   Kostnad |
| -------------- | ------: | --------: |
| August 2026    | 282 kWh | 459,50 kr |
| September 2026 | 315 kWh | 512,20 kr |
| Oktober 2026   | 401 kWh | 687,40 kr |

Dette kan gjøre det mulig å følge utviklingen i strømforbruk over tid.

### Dokumentasjon

På sikt kan brukeren få mulighet til å:

* skrive ut beregningen
* laste ned en oversikt
* generere PDF
* dele beregningen med leietaker
* se grunnlaget for alle kostnader

## Tilgjengelighet

Dagens løsning skal videreutvikles slik at den blir lettere tilgjengelig for flere enn bare personer som allerede har fått en direkte lenke.

Dette kan innebære:

* offentlig tilgjengelig nettside
* eget domenenavn
* bedre navigasjon
* tydelig startside
* responsivt design
* støtte for mobil, nettbrett og PC
* universell utforming
* bedre struktur og lesbarhet

## Flere brukere

På sikt kan prosjektet utvides slik at flere kan bruke løsningen selvstendig.

Mulige funksjoner:

* brukerprofiler
* flere leieforhold
* flere strømmålere
* egne beregningshistorikker
* innlogging
* lagring av tidligere data

Dette er ikke nødvendigvis nødvendig i første versjon.

## Personvern og sikkerhet

Dersom løsningen senere lagrer brukerdata, må personvern og datasikkerhet være en sentral del av videreutviklingen.

Det bør blant annet vurderes:

* hvilke data som faktisk trenger å lagres
* hvor lenge data lagres
* hvordan data beskyttes
* hvem som har tilgang
* om personopplysninger kan unngås helt

## Mulig utviklingsplan

### Versjon 1

Fokus på en enkel og stabil kalkulator.

* Legge inn målerstand
* Beregne forbruk
* Legge inn strømpris
* Beregne strømkostnad
* Vise resultat tydelig
* Gjøre siden mobilvennlig

### Versjon 2

Utvide beregningen.

* Nettleie
* Faste kostnader
* Avgifter
* Flere kostnadstyper
* Bedre forklaringer
* Detaljert beregningsoversikt

### Versjon 3

Gjøre løsningen mer tilgjengelig.

* Publisere som offentlig nettside
* Bedre navigasjon
* Eget domenenavn
* Forbedret design
* Universell utforming

### Versjon 4

Utvidede funksjoner.

* Historikk
* Lagring av beregninger
* PDF
* Eksport
* Flere brukere
* Flere leieforhold

## Videre utvikling

Noen områder jeg ønsker å utforske videre:

* Hvordan gjøre beregningen så enkel som mulig
* Hvordan forklare strømregningen på en forståelig måte
* Hvordan redusere antall felt brukeren må fylle inn
* Hvordan hente inn relevante priser automatisk
* Hvordan gjøre resultatet enkelt å dokumentere
* Hvordan publisere løsningen på en trygg og stabil måte
* Hvordan gjøre løsningen tilgjengelig for flere uten at den blir unødvendig komplisert

## Mål

Prosjektets mål er å utvikle en løsning som gjør strømoppgjør mellom utleier og leietaker enklere, mer transparent og mindre tidkrevende.

Brukeren skal kunne:

1. legge inn nødvendige tall
2. forstå hva tallene betyr
3. få riktig beregning
4. se hvordan beløpet er beregnet
5. dokumentere resultatet
6. dele resultatet på en enkel måte

## Status

🚧 Under aktiv videreutvikling

Grunnlaget for appen er allerede utviklet. Neste steg er å forbedre brukeropplevelsen, gjøre løsningen enklere å bruke og gjøre den mer tilgjengelig for flere brukere.
