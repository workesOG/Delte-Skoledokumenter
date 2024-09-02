### Beskrivelse af IT-systemet: Pong

**Pong** er et af de første videospil, som blev udviklet, og det er et enkelt, men ikonisk spil, der simulerer bordtennis, men hvordan Pong fungerer på et teknisk niveau?

#### 1. **Spilgrænseflade og hovedkomponenter**

Pong består af en simpel brugergrænseflade med følgende hovedkomponenter:

- **Spillebane:** En rektangulær skærm, der fungerer som banen, hvor spillet finder sted.
- **Bat/paddel:** To rektangulære objekter placeret på venstre og højre side af skærmen. De kontrolleres af spillerne.
- **Bold:** Et cirkulært objekt, der bevæger sig rundt på banen og reflekteres af battene og banens kanter. I det helt originale pong fra 1972 var bolden kvadratisk.
- **Pointscore:** Viser scoren for hver spiller.

#### 2. **Spilmekanik**

Spillet starter med, at bolden placeres midt på skærmen og begynder at bevæge sig i en vilkårlig retning (højre eller venstre) med en bestemt hastighed. Spillernes mål er at forhindre bolden i at passere forbi deres bat ved at bevæge deres bat op eller ned og reflektere bolden, mod deres modstander.

- **Boldens bevægelse:** Bolden bevæger sig i en lige linje, indtil den rammer enten et bat eller en kant. Når bolden rammer et bat, ændrer den retning afhængigt af kontaktpunkt mellem bolden og battet, samt boldens indfaldsvinkel. Hvis bolden rammer en af banens øvre eller nedre kanter, reflekteres den tilbage med en modsat vertikal retning. Bolden's hastighed vil langsomt øges på x-aksen, hvorimod boldens hastighed på y-aksen ikke justeres, hvilket betyder at en helt lige bevægelse med x-aksen vil resultere i en væseltligt lavere samlet hastighed end en diagonal bevægelse.

- **Scoring:** Hvis bolden passerer forbi en spillers bat og rammer den bagvedliggende kant (enten venstre eller højre side af skærmen), tildeles modspilleren et point. Bolden nulstilles derefter til midten af skærmen, og en ny runde begynder.

#### 3. **Input og kontrol**

Spillerne styrer deres respektive bat ved hjælp af input-enheder (f.eks. tastatur, joystick eller mus). I en simpel version af Pong kan det være:

- **Spiller 1:** Brug af op/ned-piletasterne for at bevæge battet op og ned.
- **Spiller 2:** Brug af W og S tasterne for at bevæge battet op og ned.
- **Originalt:** I det originale 1972 pong, ville det spilles med joysticks, enten fra en arkademaskine eller en "Atari game console". 

Inputtet fra spilleren oversættes direkte til en vertikal bevægelse af battet. Bevægelsen er begrænset til at være inden for spillebanens vertikale grænser.

### Analyse af IT-Systemet

#### 1. Gestaltlovene

* **Loven om nærhed:** Nærhedsloven viser sig i Pong ved, at padlen og scoren er placeret tæt på hinanden på hver side af skærmen. Dette gør det nemt for spilleren at associere sin padel med sin score og sin side af banen.

* **Loven om lighed**: Lighedsloven bruges ved, at begge padler er ens i form og størrelse. Dette gør det klart, at begge padler har samme funktion, uanset hvilken side de er på. Spilleområdet er også opdelt i 2 lige store dele, hvilket giver en forståelse for at begge spillere har lige muligheder.

* **Loven om lukkethed**: Lukkethedsloven ses, når spillerne opfatter padlerne og bolden som komplette objekter, selvom de er enkle i designet. Den stiplede midterlinje opfattes også som en sammenhængende helhed, selvom den er brudt op.

* **Loven om forbundethed**: Forbundethedsloven ses i interaktionen mellem padlen og bolden. Når bolden rammer padlen, skabes der en tydelig forbindelse, som viser, at padlen styrer boldens bevægelse.

* **Loven om figur og baggrund**: Figur-baggrundsloven anvendes ved, at den sorte baggrund gør de hvide elementer som padler, bold og score tydelige. Dette gør det nemt for spillerne at fokusere på de vigtigste elementer i spillet.

#### 2. UX-Trekanten

* **Nyttig:** Pong løser et behov for simpel underholdning og konkurrencemæssig leg. Det tilbyder en hurtig og let tilgængelig måde at spille et spil, der simulerer bordtennis, og det adresserer et ønske om at udfordre venner eller sig selv på en enkel platform.

* **Brugervenlig:** Pong er ekstremt intuitivt og nemt at lære. Spillet har få kontroller, hvilket gør det hurtigt at forstå og spille. Den enkle grafik og klare regler gør det let at huske, selv efter lang tid uden spil.

* **Engagerende:** Selvom Pong er enkelt og hurtigt at komme i gang med, kan det hurtigt blive ensformigt, da der ikke er nogen udvikling i spillet. Det kan være underholdende i korte perioder, men manglen på progression eller nye udfordringer kan gøre det mindre engagerende over tid.

#### 3. Hvad der kommer let går let

Pong er et spil, der er ekstremt let at få adgang til og starte med. Det kræver ingen komplicerede installationer eller læringskurver – du kan komme i gang med det samme. Men på grund af sin enkelhed kan interessen for spillet hurtigt dale. Hvad der kommer let, går let; spillere kan hurtigt miste interessen, da spillet ikke tilbyder nogen     form for udvikling eller nye udfordringer efter de første par runder. 

### Pongs historie

#### 2. Kontekst og Betydning

Pong, lanceret i 1972 af Atari, er bredt anerkendt som en af de mest indflydelsesrige titler i videospilsindustrien. Selvom Pong ikke var det første videospil nogensinde, markerede det en milepæl som det første spil, der opnåede mainstream succes og dermed kickstartede hele videospilsindustrien. Pongs simple, men let-forståelige gameplay, der simulerer bordtennis, gjorde det hurtigt til en favorit blandt både casual og rutinerede gamere, og dette bidrog væsentligt til spillets enorme kommercielle succes.

#### 1. Indflydelse på Spilindustrien

Pong satte en standard for fremtidige videospil og blev et forbillede for kommende udviklere. Spillets succes kastede lys over arkadespil som en lukrativ forretningsmodel og inspirerede udviklingen af andre sports- og simulationsspil. Pong introducerede et simpelt, men effektivt gameplay-design, som blev et grundlæggende komponent i spiludvikling. Denne standard blev bygget videre på i løbet af 1970'erne og 80'erne, hvor arkadekulturens vækst blev drevet af titler som *Space Invaders* (1978) og *Pac-Man* (1980), der fulgte i Pong's fodspor med fokus på enkelt og engagerende gameplay. Pong var en forløber for arkadekulturen, samt dens vækst og udbredelse til hele Verden. Pongs simple men konkurrenceorienterede gameplay gjorde det hurtigt populært i sociale sammenhæng og formede arkade til sociale mødestedder.
