### Beskrivelse af IT-systemet: Pong

**Pong** er et af de første videospil, som blev udviklet, og det er et enkelt, men ikonisk spil, der simulerer bordtennis. Lad os dykke ned i, hvordan Pong fungerer på et teknisk niveau.

#### 1. **Spilgrænseflade og hovedkomponenter**

Pong består af en simpel brugergrænseflade med følgende hovedkomponenter:

- **Spillebane:** En rektangulær skærm, der fungerer som banen, hvor spillet finder sted.
- **Bat/paddel:** To rektangulære objekter placeret på venstre og højre side af skærmen. De kontrolleres af spillerne.
- **Bold:** En cirkulær objekt, der bevæger sig rundt på banen og reflekteres af battene og banens kanter.
- **Pointscore:** Viser scoren for hver spiller.

#### 2. **Spilmekanik**

Spillet starter med, at bolden placeres midt på skærmen og begynder at bevæge sig i en vilkårlig retning (højre eller venstre) med en bestemt hastighed. Spillernes mål er at forhindre bolden i at passere forbi deres bat ved at bevæge deres bat op eller ned.

- **Boldens bevægelse:** Bolden bevæger sig i en lige linje, indtil den rammer enten et bat eller en kant. Når bolden rammer et bat, ændrer den retning afhængigt af batsets position og vinklen, hvormed den rammer bolden. Hvis bolden rammer en af banens øvre eller nedre kanter, reflekteres den tilbage med en modsat vertikal retning. Bolden's hastighed er konstant på x-aksen, hvilket betyder at en helt lige bevægelse med x-aksen vil resultere i en væseltligt lavere samlet hastighed end en diagonal bevægelse.

- **Scoring:** Hvis bolden passerer forbi en spillers bat og rammer den bagvedliggende kant (enten venstre eller højre side af skærmen), tildeles modspilleren et point. Bolden nulstilles derefter til midten af skærmen, og en ny runde begynder.

#### 3. **Input og kontrol**

Spillerne styrer deres respektive bat ved hjælp af input-enheder (f.eks. tastatur, joystick eller mus). I en simpel version af Pong kan det være:

- **Spiller 1:** Brug af op/ned-piletasterne for at bevæge battet op og ned.
- **Spiller 2:** Brug af W og S tasterne for at bevæge battet op og ned.

Inputtet fra spilleren oversættes direkte til en vertikal bevægelse af battet. Bevægelsen er begrænset til at være inden for spillebanens vertikale grænser.

### Analyse af IT-Systemet

#### 1. Gestaltlovene

* **Loven om nærhed:** Nærhedsloven viser sig i Pong ved, at padlen og scoren er placeret tæt på hinanden på hver side af skærmen. Dette gør det nemt for spilleren at associere sin padel med sin score og sin side af banen.

* **Loven om lighed**: Lighedsloven bruges ved, at begge padler er ens i form og størrelse. Dette gør det klart, at begge padler har samme funktion, uanset hvilken side de er på.

* **Loven om lukkethed**: Lukkethedsloven ses, når spillerne opfatter padlerne og bolden som komplette objekter, selvom de er enkle i designet. Den stiplede midterlinje opfattes også som en sammenhængende helhed, selvom den er brudt op.

* **Loven om forbundethed**: Forbundethedsloven ses i interaktionen mellem padlen og bolden. Når bolden rammer padlen, skabes der en tydelig forbindelse, som viser, at padlen styrer boldens bevægelse.

* **Loven om figur og baggrund**: Figur-baggrundsloven anvendes ved, at den sorte baggrund gør de hvide elementer som padler, bold og score tydelige. Dette gør det nemt for spillerne at fokusere på de vigtigste elementer i spillet.
