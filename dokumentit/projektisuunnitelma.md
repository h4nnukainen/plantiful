# Projektisuunnitelma

- [Projektisuunnitelma](#projektisuunnitelma)
  - [Projektin tiedot](#projektin-tiedot)
    - [Termit ja lyhenteet](#termit-ja-lyhenteet)
    - [Viitteet](#viitteet)
  - [Projektin sisältö](#projektin-sis%C3%A4lt%C3%B6)
    - [Johdanto](#johdanto)
    - [Projektin tausta ja tavoitteet](#projektin-tausta-ja-tavoitteet)
    - [Tuotokset](#tuotokset)
    - [Projektin hyväskyminen](#projektin-hyv%C3%A4skyminen)
  - [Toimintasuunnitelma](#toimintasuunnitelma)
    - [Projektin aloittamisesta](#projektin-aloittamisesta)
    - [Projektin toteuttamisesta](#projektin-toteuttamisesta)
    - [Projektin testaamisesta](#projektin-testaamisesta)
    - [Projektin lopettamisesta](#projektin-lopettamisesta)
  - [Projektin resurssit](#projektin-resurssit)
    - [Projektin organisaatio](#projektin-organisaatio)
    - [Ohjausryhmä](#ohjausryhm%C3%A4)
    - [Työryhmät](#ty%C3%B6ryhm%C3%A4t)
    - [Asiakkaan vastuut](#asiakkaan-vastuut)
    - [Työkalut](#ty%C3%B6kalut)
  - [Aikataulu](#aikataulu)
  - [Raportointi ja kommunikointi](#raportointi-ja-kommunikointi)
    - [Sisäinen raportointi](#sis%C3%A4inen-raportointi)
    - [Asiakasraportointi](#asiakasraportointi)
    - [Viikkopalaverikäytäntö/Daily Scrum](#viikkopalaverik%C3%A4yt%C3%A4nt%C3%B6daily-scrum)
    - [Kommunikointitavat](#kommunikointitavat)
  - [Dokumentointi](#dokumentointi)
    - [Dokumenttipohjat](#dokumenttipohjat)
    - [Dokumenttien hallinta](#dokumenttien-hallinta)
  - [Riskien hallinta](#riskien-hallinta)
  - [Avoimet asiat](#avoimet-asiat)

### Muutoshistoria
| Versio | Kuvaus | Tekijä | pvm
|---|---|---|---|
0.1d | Alustava luonnos | Santtu Sarlin | 21.1.2019
0.9p | Valmis proposal | Santtu Sarlin | 6.2.2019 

## Projektin tiedot

### Projektin nimi:
Plantiful

### Tekijät:
- Santtu Sarlin
- Miika Pollari
- Mikko Hannukainen
- Mikko Poutanen

### Termit ja lyhenteet

| Termi | Kuvaus |
|---|---|
GIT | Versionhallintajärjestelmä
GitHub | Palvelu joka on rakennettu GIT versionhallinnan ympärille
Markdown | Merkkauskieli
Scrum | Sovelluskehitysmuoto, jonka pääpointteina on Daily Scrumit tekä Sprintit
Daily Scrum | Päivittäinen tilannekatsaus
Sprint | Ajanjakso, jonka jälkeen tuotteesta on ainakin periaatteessa julkaisukelpoinen versio
Sprint Review | Sprintin jälkeen pidettävä sessio, jossa tutkitaan mitä on sprintin aikana saatu tehtyä
Retrospektiivi | Sprintin jälkeen pidettävä sessio, jossa tutkitaan miten sprintti on mennyt
Backlog | Lista asioista, mitä projektin aikana tullaan toteuttamaan
Branch | GitHub repositoryn haara
HLTP | High Level Test Plan

### Viitteet

| Viittaus | Materiaali |
|---|---|
HLTP | [HLTP.md](hltp.md)
Esitutkimus | [esitutkimus.md](esitutkimus.md)
Git-Ohje | [git-ohje.md](../git_ohjeet/git-ohje.md)
Git-Workflow | [github_workflow.png](../git_ohjeet/github_workflow.png)

## Projektin sisältö

### Johdanto

Plantiful on mobiiliapplikaatio joka toimii mielialapäiväkirjana. Sen päätoimintoihin kuuluu myös virtuaalinen kasvi, joka kasvaa jokaiselle käyttäjälle erilaiseksi käytön myötä. Tämän dokumentin tarkoituksena on selvittää, mitä vaaditaan projektin läpivientiin.

### Projektin tausta ja tavoitteet

Plantiful on tarkoitettu kaikille, jotka haluavat seurata mielialaansa ja tehdä itsereflektiota analysoimalla dataa joka näytetään käyttäjälle. Projektissa on kiinteä aikataulu, joten tarvittaessa toiminnallisuuksista tingitään, jotta aikaan saadaan julkaisukelpoinen tuote, jossa on toiminnallisuuksina toimiva mielialapäiväkirja, kalenteri josta voi seurata merkintöjä sekä erilaiseksi kasvava kasvi.

Tavoitteena on saada tuotettua kaikki tuotokset listattuna alempana:

### Tuotokset     

- Projektisuunnitelma
- HLTP
- Esitutkimus
- Sprint backlog
- Product backlog
- Dokumentointi
- Markkinointisuunnitelma
- Business model canvas
- Julkaisukelpoinen Demo-tuote
- Viikkopalaveri-pöytäkirjat
- Sprint Review-pöytäkirjat
- Sprint Retrospektiivi-pöytäkirjat


### Projektin hyväskyminen

Hyväksyminen voidaan todeta kun projektin tavoitteet ovat toteutuneet.

## Toimintasuunnitelma

### Projektin aloittamisesta
Projektin varsinainen tuotanto aloitetaan 28.1. Tätä ennen kuluva viikko menee esituotantoon, jonka aikana tuotetaan projektisuunnitelma, esitutkimus sekä high level test plan. Product owner luo myös alustavan backlogin.

### Projektin toteuttamisesta
Projektin toteutuksessa toimitaan SCRUM:in menetlmien mukaisesti. Pidämme säännöliset Daily Scrum palaverit, viikkopalaverit, sprint reviewit ja sprint retrospektiivit. Sprinttien kesto on 2 viikkoa. Gatet 4 viikon välein jossa esitellään demot. Tulevan sprintin aikana tehtävä työ suunnitellaan Sprint Planningissa, johon
osallistuu koko Scrum-tiimi.

Aluksi Scrum-tiimi määrittelee, mikä on tulevan Sprintin Sprint Goal ja kuinka paljon töitä tiimi pystyy tekemään Sprintin aikana.

Sitten Scrum-tiimi käy Product Ownerin johdolla läpi Product Backlogia ja valitsevat sieltä Sprint Goalin mukaiset User Storyt ja siirtävät ne Sprint Backlogiin.

Tämän jälkeen Scrum-tiimi käy läpi Sprint Backlogissa olevat User Storyt ja pilkkovat ne Taskeihin, jotka ovat tarkkoja kuvauksia yksittäisistä asioista, joita User Story sisältää. 
Taskeille voidaan myös tarvittaessa suunnitella tarkat määreet, miltä
lopputuloksen tulisi näyttää tai miten se tulisi toimia.

### Projektin testaamisesta
Testit tehdään high level test plan- dokumentin mukaisesti.

### Projektin lopettamisesta
Projekti loppuu projektin konkurssipäivänä 10.5.2019.
Projektista tuotetaan loppuraportti ja jatkokehitys-readme, jossa on lyhyt seloste projektin tekniikoista ja kehitysympäristöstä mahdollista projektin jatkoa varten. 

## Projektin resurssit
4 henkilöä, 6h 45min työtunteja per päivä. Keskiviikkoisin on Concept Lab 13.2 alkaen, joten päivät kestävät silloin klo 9-12

### Projektin organisaatio

| Nimi | Rooli(t) | Yhteystiedot
|---|---|---|
Santtu Sarlin | Tekniikka, Scrum Master | k8644@student.jamk.fi
Miika Pollari | Sisällöntuotto + tekniikka, Product Owner | k8461@student.jamk.fi
Mikko Hannukainen | Tekniikka, Testaus | l5159@student.jamk.fi
Mikko Poutanen | Sisällöntuotto, Liiketoiminta | l4305@student.jamk.fi
Henna Haarala | Ulkoistettu apu, Graafikko | k8301@student.jamk.fi

### Ohjausryhmä

| Nimi | Rooli(t) | Yhteystiedot
|---|---|---|
Teemu Pölkki | Ohjaaja, Labramestari | teemu.polkki@jamk.fi
Janne Hanhela | Ohjaaja | janne.hanhela@jamk.fi
Niko Kiviaho | Ohjaaja | niko.kiviaho@jamk.fi

### Työryhmät

Organisaatiossa ei toistaiseksi ole työryhmiä.

### Asiakkaan vastuut
Asiakasta ei ole, toistaiseksi.

### Työkalut

- Työasemat (läppärit)
- Visual Studio Code
- GitHub
- ZenHub
- InkScape
- GIMP
- Microsoft Teams

## Aikataulu

| Tapahtuma | Päivämäärä | Muut tiedot/osanottajat
|---|---|---|
Esituotanto | 21.1.2019 - 25.1.2019 | TC projektila
||||
Sprintti 1 | 28.1.2019 -  8.2.2019 | TC Projektitila
Sprint Planning | 28.1.2019 | TC Projektitila
Sprint Review | 8.2.2019 | TC Projektitila
Sprint Retrospektiivi | 8.2.2019 | TC Projektitila
||||
Sprintti 2 | 11.2.2019 - 22.2.2019 | TC Projektitila
Sprint Planning | 11.2.2019 | TC Projektitila
Gate 1 | 22.2.2019 | TC Projektitila
Sprint Review | 22.2.2019 | TC Projektitila
Sprint Retrospektiivi | 22.2.2019 | TC Projektitila
||||
Hiihtoloma | 25.2.2019 - 1.3.2019 | Loma
||||
Sprintti 3 | 4.3.2019 - 15.3.2019 | TC Projektitila
Sprint Planning | 4.3.2019 | TC Projektitila
Sprint Review | 15.3.2019 | TC Projektitila
Sprint Retrospektiivi | 15.3.2019 | TC Projektitila
||||
Sprintti 4 | 18.3.2019 - 29.3.2019 | TC Projektitila
Sprint Planning | 18.3.2019 | TC Projektitila
Gate 2 | 29.3.2019 | TC Projektitila
Sprint Review | 29.3.2019 | TC Projektitila
Sprint Retrospektiivi | 29.3.2019 | TC Projektitila
||||
Sprintti 5 | 1.4.2019 - 12.4.2019 | TC Projektitila
Sprint Planning | 1.4.2019 | TC Projektitila
Sprint Review | 12.4.2019 | TC Projektitila
Sprint Retrospektiivi | 12.4.2019 | TC Projektitila
||||
Sprintti 6 | 15.4.2019 - 26.4.2019 | TC Projektitila
Sprint Planning | 15.4.2019 | TC Projektitila
Pääsiäinen | 19.4.2019 - 22.4.2019 | Loma
Gate 3 | 26.4.2019 | TC Projektitila
Sprint Review | 26.4.2019 | TC Projektitila
Sprint Retrospektiivi | 26.4.2019 | TC Projektitila
||||
Jälkituotanto | 29.4.2019 - 10.5.2019 | TC Projektitila
Vappu | 1.5.2019 | Loma 
Projektin konkurssi | 10.5.2019 | Saunatila, tuothan oman pyyhkeen, paikalla kaikki

## Raportointi ja kommunikointi

### Sisäinen raportointi

Microsoft Teams toimii tiimin virallisena kommunikaatiovälineenä. Tuotettavat dokumentit uploadataan GitHubiin. Daily Scrumissa raportoidaan päivittäin tilannetta.

### Asiakasraportointi

Scrum Master raportoi projektin tilasta Niko Kiviaholle viikottain perjantaisin viikkopalaverin jälkeen, klo 16:00 mennessä.

Ohjausryhmä näkee tuotetut dokumentit GitHubista.

### Viikkopalaverikäytäntö/Daily Scrum

Viikkopalaveri pidetään perjantaisin klo 12:30. Palaverin aikana selvitetään tehdyt työt ja suunnitellaan tulevat. Palavereista tehdään pöytäkirja joita säilytetään projektihakemistossa.

Daily Scrum päivittäin klo 10:00 projektin toimitilassa whiteboardin edessä, käydään läpi nopeasti: Mitä tehtiin eilen? Mitä aiotaan tehdä tänään? Oliko ongelmia?

### Kommunikointitavat

Microsoft Teams toimii projektin virallisen kommunikaatiotyökaluna.

## Dokumentointi

### Dokumenttipohjat

Projektissa käytetään jamktiko github-organisaation alta löytyviä dokumenttipohjia.

### Dokumenttien hallinta

Käytämme versionhallintaan GitHubia, josta jokaisella tiimin jäsenellä on oikeus nähdä dokumentit. Käytämme versionhallintaan myös versionumeroita ja 1.0 julkaistaan vasta, kun tuote on hyväksyttävästi valmis.

Tiimi käyttää GitHubia tiimin oman git-ohjeen mukaan sovitulla tavalla.

## Riskien hallinta

Viikkopalaverissa havainnoidaan ja käydään läpi mahdollisia esille tulleita riskejä ja arvioidaan niiden todennäköisyys, impakti, ja mietitään toimenpiteet kuinka ne saadaan hallittua. Myös retrospektiivissä voidaan nostaa potentiaaliset riskit esille.


## Avoimet asiat
--