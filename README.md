# University – oppilasrekisterin projektisuunnitelma

## Tavoite

Projektissa kehitetään oppilaitokselle oppilasrekisteri, jossa opiskelijat voivat tarkastella omia tietojaan ja henkilökunta ylläpitää opiskelija-, kurssi- ja suoritustietoja. Tavoitteena on ajantasainen, helppokäyttöinen järjestelmä, jossa käyttäjät näkevät ja muuttavat tietoja vain omien oikeuksiensa mukaisesti.

## Laajuus ja rajaukset

Ensimmäisen version suunnitellut ominaisuudet ovat:

- Kirjautuminen ja käyttäjäroolit: opiskelija, opettaja ja opintosihteeri.
- Opiskelijan perustietojen lisääminen, hakeminen ja päivittäminen.
- Kurssien ja kurssi-ilmoittautumisten hallinta.
- Opettajan mahdollisuus kirjata oman kurssinsa arvosanat.
- Opiskelijan mahdollisuus tarkastella omia tietojaan ja suorituksiaan.

Toiminnallisuudet tarkennetaan vaatimusmäärittelyssä ja priorisoidaan Product Backlogissa. Ensimmäisestä versiosta rajataan pois integraatiot muihin oppilaitosjärjestelmiin ja laaja raportointi. Kehityksessä ja testauksessa käytetään kuvitteellisia henkilötietoja.

## Työskentely ja vastuut

Projekti toteutetaan Scrum-viitekehyksellä alustavasti kahden viikon Sprinteissä. GitHub Projectsissa ylläpidetään User Storyja, hyväksymiskriteerejä, taskeja ja työn tilaa. Koodi ja projektin dokumentit säilytetään tässä repositoriossa.

Product Owner vastaa tavoitteista ja Backlogin järjestyksestä, Scrum Master tukee työskentelyä ja kehittäjät vastaavat suunnittelusta, toteutuksesta ja testauksesta. Vastuuhenkilöt nimetään projektin alussa. Teknologiat ja kehitysympäristö valitaan alustavan vaatimusmäärittelyn yhteydessä.

## Vaiheet ja aikataulu

1. **Valmistelu:** tarkennetaan käyttäjäryhmät, vaatimukset ja rajaukset sekä sovitaan vastuut, teknologiat ja valmistumisen ehdot.
2. **Ensimmäinen Sprint:** tavoitellaan pientä toimivaa kokonaisuutta, esimerkiksi opintosihteerin mahdollisuutta lisätä ja hakea opiskelijan perustiedot tarvittavine käyttöoikeuksineen.
3. **Seuraavat Sprintit:** toteutetaan tärkeimmät jäljellä olevat ominaisuudet ja parannukset saadun palautteen perusteella.
4. **Ensimmäisen version julkaisu:** tarkistetaan sovittu kokonaisuus, viimeistellään asennus- ja käyttöohjeet sekä sovitaan ylläpidosta.

Sprinttien lukumäärä ja julkaisupäivä sovitaan työmääräarvioiden ja tiimin käytettävissä olevan ajan perusteella. Jokaisen Sprintin lopussa tarkastellaan tuotetta Sprint Reviewssa ja toimintatapoja Sprint Retrospectivessa.

## Laatu, riskit ja seuranta

Jokaiselle User Storylle määritellään todennettavat hyväksymiskriteerit. Toteutuksessa tarkistetaan erityisesti tietojen validointi ja käyttöoikeudet, katselmoidaan koodi ja testataan keskeiset käyttäjäpolut. Yhteiset valmistumisen ehdot kirjataan Definition of Doneen ennen toteutusta.

Keskeisiä riskejä ovat liian laaja tavoite, epäselvät vaatimukset ja käyttäjätietojen luvaton näkyminen tai muuttaminen. Niitä hallitaan rajaamalla ensimmäinen versio, tarkentamalla pieniä User Storyja palautteen avulla ja testaamalla oikeudet myös palvelinpuolella.

Työn etenemistä seurataan GitHub Projectsissa suhteessa Sprint Goaliin ja tuotteen tavoitteeseen. Muutokset priorisoidaan Backlogissa, ja Sprinttien tavoitteet, tulokset sekä sovitut parannukset kirjataan Sprint-muistioihin.

## Projektin dokumentit

- [Definition of Done](docs/definition-of-done.md) – yhteiset valmistumisen ehdot; täydennetään ennen toteutusta.
- [Vaatimusmäärittely](docs/requirements.md) - tuotteelle asetettavat vaatimukset; täydennetään tarvittaessa
- [Sprint 1:n tavoite ja muistiot](docs/sprints/sprint-1.md) – täydennetään Sprint Planningissa ja Sprintin edetessä.

Vaatimusmäärittely, tekninen dokumentaatio sekä asennus- ja käyttöohjeet lisätään `docs`-kansioon projektin edetessä.
