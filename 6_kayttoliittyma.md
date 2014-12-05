## Käyttöliittymä

# käyttöliittymäluonnoksia (mockups)

(Kuva 1)Alkunäyttö

![Alkunäyttö](kuvat/alkunäyttö.png)


(Kuva 2)Näkymä kartasta (perusnäkymä), jossa valittuna luokka || (Kuva 3) Näkymä, kun tulee pop-up -ilmoitus kesken pelin (taustalla kartta)

![käyttöliittymäesimerkit](kuvat/kuvat2.png)


*(Kuva 4) Näkymä Menusta
 ![käyttöliittymäesimerkki](kuvat/menu.png) 


* (Kuva 5)Esimerkkinäkymä, mitä pelaajan omissa tiedoissa näkyy.

 ![Statsit](kuvat/Stats.png)



#---#


* listaa käyttöliittymän näkymät
   - Kirjautumisnäyttö
       - vaihtoehtoisesti kirjaudu/rekisteröidy
       - unohtunut salasana
   - loading screen, tulee kirjautumisen jälkeen, aivan pelin alussa
       - mainokset
   - kartta
      - ilmoitukset / pop upit
         - uudet daily questit; tietty merkki luokassa
         - tavoitteet suoritettu
         - spesiaalitehtävät 
              - pitää suorittaa tietyssä ajassa ennen kuin sulkeutuu
         - tiedot huoneista; mikä tunti, varaukset
      - oma paikka
      - search
      - menu-nappi

  - menu
    - omat tiedot 
      - tehtävät
            - esim. käy jossain luokassa ja tule takaisin viiden minuutin sisään
            - osaan tehtävistä tarvitsee parin / ryhmän
    - achievement (tavoitteet)
            - esim. kuinka paljon on tullut käveltyä; tietystä määrästä tiettyjä pisteitä
            - daily questien suorittaminen 
    - top list
            - kuka saanut eniten pisteitä 
              - eniten kävellyt
              - eniten pisteitä



###Näkymät

Kirjautumisnäytöstä on kolme vaihtoehtoa, joko voidaan syöttää käyttäjätunnuksesi ja salasanan, jolloin siirrytään suoraan Loading screeniin ja edelleen peliin, joko voit ilmoittaa unohtaneesi salasanan, jolloin käyttäjältä kysytään sähköpostia ja salasana lähetetään sinne tai vaihtoehtoisesti rekisteröityminen, jolloin siirrytään rekisteröitymistilaan, jossa valitaan oma käyttäjänimi, salasana, kieli ja sähköposti esimerkiksi salasanan unohtumisen varalta.

Loading screen tulee näkyviin vain alussa ja sisältää mainoksia; mahdollisuus painaa mainosta josta pääsee mainoksen         sivuille. Loading screenin jälkeen peli automaattisesti siirtyy perusnäkymään, eli Karttaan.

Karttanäkymässä näkyy oma liikkuminen, jolloin sitä voi käyttää myös suunnistamiseen koulussa, muutenkin kuin pelin käyttöön. Karttanäkymässä questit(tehtävät) näkyvät omalla merkillään tiloissa joissa niitä on. Karttanäkymän yläreunassa on menulle oma nappulansa, sekä search -palkki, josta voi hakea tarvittaessa esimerkiksi luokan nimellä. Lisäksi on mahdollista klikata luokkaa karttanäkymässä, jolloin saa tiedot luokan toiminnoista, aukeaa ilmoitusten kaltaisesti. (Kts Kuva 2)
Karttanäkymän päälle aukeavat myös ilmoitukset (pop up-ikkunat), josta ne voi sulkea.

Menussa on yläreunassa valikko, josta lyötyy omat tiedot, tehtävät, achievementit ja top list. 
Painamalla esimerkiksi omia tietoja alapuolelle aukeaa sisältö. (kts Kuva 5). Muut alasivut aukeavat samankaltaisesti. Omista tiedoista on mahdollista kirjautua pelistä ulos.
Menunäkymässä on yläkulmassa search palkki, sekä Map-nappi josta pääsee takaisin kartalle.

Näkymien väliset siirtymät seuraavat samaa kaavaa ja aina näkymää vaihtaessa on animaatio siitä, kun seuraava näkymä liukuu reunasta edellisen tilalle.



#### Käyttöliittymän tietosisältö näkymittäin

Loading screenin aikana käyttöliittymän on osattava hakea mainos latauksen ajaksi.

Perusnäkymässä tarvitaan kartta koulusta, luokkien tiedot (osaa näyttää klikattaessa tai hakua käyttäessä) sekä osaa näyttää uudet ilmoitukset.

Omat tiedot sisältää oman käyttäjänimen, pisteet kokonaisuudessaan, kuukaudessa, viikossa ja paivän aikana. Tiedoissa 	lukee myös kuinka paljon on kävellyt. Achievements käyttää osittain samoja tietoja kuin omat tiedot, esimerkiksi käyttäjän omista kävelymääristä ym. Esimerkiksi se osaa näyttää kuinka paljon tarvii vielä kävellä jotta saa achievementin "10km kävellyt".

Top listassa näkyy sata parasta pistemäärien mukaan, eniten kävelleiden kesken ja parhaat tänään kummastakin osiosta.




