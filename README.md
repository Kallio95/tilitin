# Tilitin

Tässä versiossa on lisätty mahdollisuus tuoda tilitapahtumia csv-tiedostosta ja päivitetty tilitin yhteensopivaksi Applen M-sarjan suorittimien kanssa.

Lataa valmis jar-paketti:
www.ekallio.fi/share/tilitin.jar

## Tilitapahtumien tuominen CSV tiedostosta:

Tilittimeen voidaan tuoda tilitapahtumat verkkopankin procountor yhteensopivasta csv-tiedostosta. Ennen tapahtumien tuomista kannattaa varmistaa, että tilittimestä löytyy kaikki csv-tiedostossa olevat tilit. Jos jotain tiliä ei löydy, tuonti jää kesken ja tilitin antaa virheilmoituksen.

Kaikki tapahtumat tuodaan nykyiselle tilikaudelle riippumatta tapahtumien päivämääristä. Mahdollisten ongelmien välttämiseksi uuden tiedoston tuontia kannattaa ensin testata luomalla uusi tilikausi ja tuomalla tapahtumat sinne. Tämän tilikauden voi sitten poistaa tarvittaessa.

Tapahtumia pääsee tuomaan valitsemalla: Muokkaa -> Procountor tuonti. Avautuvaan ikkunaan voi syöttää halutun tiedostopolun, jonka jälkeen painamalla OK tilitin yrittää tuoda tapahtumat, ilmoittaa tuonnin lopputuloksen ja palaa perusnäkymään. Tiedostopolku täytyy antaa absoluuttisena ja muoto riippuu käyttöjärjestelmästä, esimerkiksi:

Windows:

```
C:\Users\username\Desktop\tuonti.csv
```

Mac/Linux:

```
/Users/username/Desktop/tuonti.csv
```
