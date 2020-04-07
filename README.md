# Ohjelmistotekniikka, harjoitustyö

## Dokumentaatio
[Vaatimusmäärittely](https://github.com/Valokoodari/tkt-ohte-ht/blob/master/dokumentointi/vaatimusmaarittely.md)  
[Työaikakirjanpito](https://github.com/Valokoodari/tkt-ohte-ht/blob/master/dokumentointi/tyoaikakirjanpito.md)
[Arkkitehtuuri](https://github.com/Valokoodari/tkt-ohte-ht/blob/master/dokumentointi/arkkitehtuuri.md)

## Komentorivitoiminnot
### Ohjelman suorittaminen
```
mvn compile exec:java -Dexec.mainClass=gui.Main
```

### Testaaminen
```
mvn test
```
### Testikattavuus
```
mvn test jacoco:report
```
Generoitunut testikattavuusraportti löytyy tiedostosta target/site/jacoco/index.html

### Checkstyle
```
mvn jxr:jxr checkstyle:checkstyle
```
Generoitunut raportti löytyy tiedostosta target/site/checkstyle.html

## Tunnetut bugit
- Ohjelman napeista piirtyy joillakin järjestelmillä vain tekstit. Ei vaikutusta ohjelman toiminnallisuuteen.
