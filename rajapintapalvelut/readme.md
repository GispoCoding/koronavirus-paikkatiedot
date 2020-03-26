# Paikkatiedon rajapintapalveluita QGISiin
QGIS mahdollistaa usean rajapintapalvelun hyödyntämisen näppärästi .qlr eli Layer Definition File -tiedostojen (suom. tason määrittelytiedosto) avulla. Ohesta löytyvien .qlr-tiedostojen avulla voi ladata useamman rajapintapalvelun Suomesta. Rajapintapalveluita on kerätty eri teemojen alle tarkoituksena helpoittaa paikkatietoaineistojen käyttöä QGISissä.

.qlr-tiedostoja ladataan QGISissa seuraavasti:

Tasot > Lisää tason määrittelytiedostona... (eng. Layer > Add from Layer Definition File)

![qlr-tiedoston lataaminen](/rajapintapalvelut/qlr_tiedostot.png?raw=true "qlr-tiedoston lataaminen")

## Rajapintapalveluiden lataaminen
.qlr-tiedoston laataminen saattaa kestää hetken, sillä aineistojakin on paljon. Kunkin organisaation osalta on ladattu muutama esimerkkiaineisto .qlr-tiedostoon. Jos käyttäjä haluaa tarkastella jonkin organisaation WFS- tai WMS-rajapintaa, on hänen lisättävä rajapintapalvelun (WFS/WMS/WMTS) osoite QGISiin. [QGISin dokumentaatio](https://docs.qgis.org/3.10/en/docs/user_manual/working_with_ogc/ogc_client_support.html#wfs-and-wfs-t-client) auttaa tämän toimenpiteen toteuttamisessa ja .qlr-tiedostosta löytyvien kunkin tason ominaisuuksista löytyy tieto rajapintapalvelun URL-osoitteesta, esimerkiksi näin:

![rajapintapalvelun URL-osoitteen tunnistaminen](/rajapintapalvelut/rajapintapalvelut_ominaisuudet.png?raw=true "rajapintapalvelun URL-osoitteen tunnistaminen")


## Rajapintapalveluiden URL-osoitteita
.qlr-tiedostoista löytyvien rajapintapalveluiden URL-osoitteet voi käydä katsastamassa Gispo Oy:n ylläpitämällä sivustolla avoimen datan paikkatiedon rajapintapalveluista:

https://gispohelp.zendesk.com/hc/fi/articles/208159815

Rajapintapalveluiden URL-osoitteiden lataamiseksi voi myös hyödyntää oheen ladattua .xml-tiedostoa, johon on tallennettu usean suomalaisen organisaation WFS-rajapintapalveluosoitteita. Näin käyttäjä säästyy kunkin rajapintapalveluosoitteen manuaaliselta tallentamiselta. Alla näytönkaappauksia QGISista rajapintapalveluiden lataamiseksi:

![Avataan tietolähteiden hallinta](/rajapintapalvelut/img/1_lataa_wfs_rajapinnat.png?raw=true "Avataan tietolähteiden hallinta")
![Valitaan haluamamme yhteydet](/rajapintapalvelut/img/2_lataa_wfs_rajapinnat.png?raw=true "Valitaan haluamamme yhteydet")
![Ladatut rajapinnat](/rajapintapalvelut/img/3_lataa_wfs_rajapinnat.png?raw=true "Ladatut rajapinnat")




