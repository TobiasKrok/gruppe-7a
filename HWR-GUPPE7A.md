# How We Roll - Gruppe 7A

### Utførte oppgaver
 - [x] Utviklet How We Roll nettside for Gruppe 7A
 - [x] Opprettet Github Pages environment til [How We Roll](https://tobiaskrok.github.io/gruppe-7a/)
 - [x] Fulført alle tasks i [Projects](https://github.com/TobiasKrok/gruppe-7a/projects/1)
 - [x] Skrevet dokumentasjon 


## Organisering 

For å sette igang arbeidet med oppgaven diskuterte vi først hvilket type innhold vi måtte ha, og med tilleggs detaljene til oppgaven med “IS-114 Tillegg til HowWeRoll -oppgaven.pdf “ fordelte vi oss på tre grupper. To begynte på index, tre begynte på how-we-roll(registreringsside) og to begynte på Hwr-rapport(canvas/JS). 
Gruppen består av syv personer med ulike bakgrunnskunnskap, men ved at alle sidene inneholdere former for Html og CSS så vi for oss at de med best kjennskap til kode burde prøve seg på Javascript og JSON koblingen. 

Arbeidet i de ulike gruppene foregitt noe forskjellig, noen satt på skolen sammen og push/pullet med Git bash på samme maskin. Noen satt på Discord med delt skjerm og noen prøvde seg på “intelliJ” sin live kode deling. Gruppene og enkeltpersoner hadde eget ansvar for å vise til kjennskap ved push og pull i github, men vi hadde som et organisering mål i “projects(github)” at alle skulle gjennomføre minst en push/pull så gruppeleder kunne ha noe oversikt på hvordan medlemmene lå an. 


Fordelingen av arbeid i prosjektoppgaven har vært ganske effektiv og løsningsorientert.  ved å arbeide i mindre grupper er det lettere å arbeide med konkrete oppgaver individuelt og få tilbakemelding/ åpne diskusjoner på enkelte aspekter som design og funksjon. 
### Oversikt over medlemmers ansvar i prosjektet
 Navn | Arbeidsoppgave | Tildelt side
------------ | ------------- | ------------
 Joakim  |    Utvikle hovedsside        |  index.html
 Pål     |    Utvikle hovedsside        |  index.html
 Edi     |    Utvikle registreringsside |  HowWeRoll.html
 Shlirim |    Utvikle registreringsside |  HowWeRoll.html
 Markus  |    Utvikle registreringsside |  HowWeRoll.html
 Fredrik |    Utvikle HWR rapportside   |  hwr-report.html
 Tobias  |    Utvikle HWR rapportside   |  hwr-report.html

## Hvordan jobbet vi?
Måten vi startet med oppgaven var å be hele gruppen om å sette seg inn i HTML og CSS. Vi satt deadlines på når alle medlemmene måtte ha tatt initiativ til å lære seg det grunnleggende. Deretter satt vi oss sammen og lagde mockup til hvordan sidene skulle se ut. Her er et eksempel av vårt første utdrag, før vi hadde begynt å kode:\
![Mockup](https://media.discordapp.net/attachments/881861898340007966/889872086372343818/unknown.png)

Vi ble enig om en felles bakgrunnsfarge og tekstfarge som alle sidene skulle brukes, og vi holdt oss til dette under utviklingen av nettsiden. Når vi hadde blitt enig om design så delte vi inn i tre grupper, en for hver side som skulle bli laget. Vi drev da med parprogrammering og fordelte oppgaver innenfor gruppen slik det passet. 
Vi forholdt oss til utviklingen av sidene ved å referere til wireframes som vi har utviklet på UXpin. Se bunn av oppgaven for wireframes (1),(2) og (3)*.

## Github Regler
Github repositoret ble satt opp med tre hovedregler:

1. Kode kan ikke pushes rett til main. Main branch har blitt satt til "protected"
2. En Pull Request **må** opprettes for å merge kode inn til main.
3. Pull Requests må gjennomgåes av gruppen før den godkjennes.

Disse reglene fulgte vi gjennom hele utviklingsprosessen. I Github ble “main” branch satt til en beskyttet branch som betyr at man ikke kan pushe endringer direkte til branchen. For å merge sin kode inn i main branch, må man opprette en Pull Request. En PR må godkjennes av et annet gruppemedlem enn personen som opprettet PR for at den skal kunne merges. Oppsettet vi da brukte var å lage en branch for hver side som skulle lages. Gruppen pushet all sin kode inne i den branchen og inneholdt bare de filene som gruppen trengte å jobbe med. Når vi følte at prosjektet var ferdig, åpnet vi pull requests på alle branchene slik at de kunne merges inn i main branch. Her er et screenshot av siste innspurt av git merges:\
![Git merges](https://i.imgur.com/UVPGnXX.png)

### Utfordringer knyttet til github.
Ettersom kun en i gruppen hadde kjennskap til github fra før, var det utfordrende å implementere daglig/ukentlig bruk av “project(kanban)” bordet i gruppen./

Etter at vi fordelte gruppen i delgrupper var det opp til enkelte medlemmer å opprette oppgaver som enten ble påtatt eller fordelt enkeltvis. Samtidig opplevde vi at alle gruppene hadde forståelse for overordnet målsetting for oppgaven og sammenheng mellom sidene. Vi innså at det var et fint design og utviklingsperspektiv ved å bruke wireframes som noenlunde lignet på hverandre, da ble det enklere for hver enkelt medlem å se konkret sammenheng./

I etterkant av prosjektet har vi også pratet om at flere grupper brukte kommentarfunksjonen i kodefelt øverst på html dokumentet. Der ble det lagt til arbeidsbeskrivelser og oppgaver. Disse kunne ha hatt nytte av å løftes ut i “project” bordet på github. 

## Tekniske detaljer

Gruppen brukte forskjellige IDE verktøy. Noen brukte Visual Studio Code og andre brukte IntelliJ IDEA. Det ble eksperimentert med å bruke IntelliJ’s Code With Me, men det ble stort sett brukt push og pull i Git for å dele kode med gruppen sin. Vi brukte en blanding av HTML, CSS og Javascript for å utvikle nettsiden. Javascript ble brukt til registrering og visualisering av data

For testing av sider og funksjoner har vi brukt intern side på intelliJ(Ultimate Edition 2021,2)/ (Community Edition 2021,2) og VSC(Version: 1.53.2).
Samt GoogleChrome((Version 94.0.4606.71 (Official Build) (x86_64)) og Firefox developer Edition(94.0b3 (64-bit)). 

Etter å ha sett gjennom validator sin site-checker for error og diverse småfeil, har vi ingen nevneverdige ting å kommentere.
https://validator.w3.org (sist sett 09.10.21)

## Canvas-element i hwr-rapport.html
Vi tok inspirasjon fra den visuelle delen av “slider data” fra “How-we-roll fra P2 teamet(1)”. Noe utfordrende var det å skape funksjoner i JS, men en i gruppen hadde forkunnskap i Javascript så vi fikk utviklet en egen løsning. Vi brukte Canvas i HTML og tegnet alle streker, sirkler, tabeller og tekst ved bruk av JS. Koden henter først all data fra JSON filene som inneholder HWR data, og prosesserer det slik at det først blir opprettet objekter med JSON verdiene, og deretter tegnes de ut på Canvas elementet. Det ble brukt Javascriptfunksjoner som Promises (med Promises.all()) og Arrays.prototype.map(). Koden har blitt delt inn i funksjoner som gjør koden gjenbrukbar. Koden er nærmere forklart i kodekommentarer. 


Vi brukte inspirasjon til kode fra både W3Schools og Developer.mozilla sine læringsplattformer. 

### Kilder til kode
(1)https://automatticp2demo.wordpress.com/about-team-p2/how-we-roll/  (sist sett 09.10.21)  
https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial (sist sett 09.10.21)  
https://www.w3schools.com/html/html5_canvas.asp (sist sett 09.10.21)  
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map (Sist sett 10.10.21)  
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/all (Sist sett 10.10.21)  

## Wireframes
![Hovedsside](https://i.imgur.com/zIiOBeK.png)
![Registrering](https://i.imgur.com/wqg8nuu.png)
![HWR Rapport](https://i.imgur.com/cEuAdLI.png)

