
# HOWTO: Introduktion till programmering i Scratch med animerade filmer

Det här är en metod för att introducera programmering till
mellanstadieelever genom att de får skapa animerade filmer i Scratch.

Metoden har utvecklats av Peter Liljenberg tillsammans med AV Media
Region Kronoberg, som även har finansierat arbetet.


## Introduktion

Scratch är en webbaserad grafisk programmeringsmiljö där man bygger
program genom att sätta ihop pusselbitar, ungefär som ett virtuellt
Lego.  Det är mycket lätt att komma igång med Scratch, samtidigt som
man kan göra väldigt ambitiösa program och lära sig mycket om
programmering och datalogi.

Det går att programmera många olika saker i Scratch, som animerade och
interaktiva filmer, spel, musik, eller utforska matematiska och
fysiska fenomen.

För en första introduktion till Scratch är det lämpligt att fokusera
på att göra en animerad film, vilket den här metoden gör.  Genom att
begränsa sig till det blir det möjligt att få en hel klass att kunna
programmera något de kan visa för kompisar och familj på en lång
lektion, och som de kan fortsätta med själva på raster eller hemma.

Avgränsningen gör att det bara är mycket enkla programmeringskoncept
som lärs ut med fokus på att lägga programpusselbitarna i rätt ordning
och hantera flera sprajtar som gör saker samtidigt.  Mer avancerade
koncept som villkor, loopar och variabler kan vänta till ett senare
tillfälle.

Målet med introduktionen är att ge eleverna ett positivt första
intryck av programmering som något roligt och pyssligt, och att visa
att det inte är krångligt och bara för experter utan något som **de**
kan göra.


## Målgrupp

Det här dokumentet är skrivet för mellanstadielärare som vill testa
det här i sina klasser, och för programmerare som vill hjälpa till med
det.

Det kan förstås också följas av en lärare som vill göra allt själv med
sin klass, eller av föräldrar som vill introducera sina barn till
programmering själva.


## Resurser

Film från en lektion där den här metoden används:
**TODO: filmen är inte färdigklippt än**

Exempelprogrammet från filmen kan undersökas och remixas här:
https://scratch.mit.edu/projects/147890744/


## Tack

Stort tack till de lärare och klasser som hjälpt till med utvecklandet
genom att låta oss testa vad som funkar i praktiken:

* Lenhovdaskolan
* Furutåskolan (Växjö)
* Nottebäckskolan
* Hjortsbergskolan (Ljungby)
* Åsedaskolan


## Licens

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Introduktion till programmering i Scratch: animerade filmer</span> av <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/petli/school-dev-howto" property="cc:attributionName" rel="cc:attributionURL">Peter Liljenberg</a> är licensierat enligt <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

Du får mycket gärna sprida det här dokumentet, redigera det och
översätta det så länge din remix också omfattas av licensen CC-BY-SA
4.0.


# Upplägg

Denna metod kan självklart följas av en programmeringsintresserad
lärare, men tanken är särskilt att läraren ska få hjälp av
yrkesprogrammerare som besöker klassen.  Att få träffa några som
jobbar med programmering ger ett extra fokus och intresse till
övningen.

Eleverna får väldigt gärna jobba i par, men då är det bäst att de
själva väljer partner så att de kan dela idéer och entusiasm.  Elever
som hellre jobbar ensamma får göra det, om antalet datorer räcker
till.

En duktig Scratchprogrammerare hinner med att hjälpa till omkring
10-12 elever eller par.  För en hel klass om 20-25 elever som alla
jobbar på en egen dator behöver det alltså vara med åtminstone två som
kan mycket om Scratch.

80-90 minuter är lagom lång tid, fördelat på 20 minuter introduktion
och en timmas programmerande.  Det brukar inte vara ett problem att
upprätthålla intresset, snarare är det svårt att få eleverna att vilja
sluta programmera.


## Teknikkrav

Datorer med Adobe Flash och internetåtkomst krävs för att kunna köra
Scratch.  Det går bra med Windows, MacOSX, Linux och ChromeBooks.

Det går i dagsläget inte att köra Scratch på iPads, Androidplattor
eller telefoner.

För demonstrationen behövs en projektor eller motsvarande så att det
går att visa hur man programmerar i Scratch.


# Förberedelser

## Lärare

Skapa ett lärarkonto på Scratch om du inte redan har det:
https://scratch.mit.edu/educators/register

> Ett lärarkonto skiljer sig från ett vanligt Scratchkonto genom att det
> enkelt går att lägga upp klasser, elevkonton och hålla koll på
> elevernas aktivitet på Scratch.  Det tar upp till en dag att få ett
> lärarkonto godkänt.

Använd lärarkontot för att lägga upp din klass och skapa ett konto för
varje elev.

> Kontonamnen för eleverna bör följa något mönster, t.ex. de två första
> bokstäverna från förnamnet och efternamnet följt av födelseåret.  Om
> det användarnamnet redan finns, så lägg på fler bokstäver från namnen
> till det accepteras av Scratch.  ÅÄÖ ersätts med AAO.

Kontona kan skapas med ett och samma lösenord, men uppmana gärna
eleverna att sedan byta dem till något hemligt.

> Om de tappar bort sitt lösenord kan du sätta ett nytt via lärarkontot.

På en lektion innan programmeringstillfället ska alla elever testa att
de kan logga in med sina konton, starta Scratcheditorn genom att
klicka på "Skapa", och sedan titta på vad det finns för bakgrunder och
sprajtar i Scratch genom att klicka på "Ny bakgrund" och "Ny sprite".
(De får förstås gärna testa att programmera med!)

Eleverna bör sedan skriva ett kort bildmanus med tre-fyra scener som
använder de färdiga bakgrunderna och sprajtarna.  Detta gör att de kan
sedan kan börja programmera direkt efter genomgången på
programmeringstillfället och utnyttja tiden där så mycket som möjligt.

> Mer om bildmanus (storyboards):
> https://en.wikipedia.org/wiki/Storyboard

> Mallar som kan skrivas ut:
> https://www.printablepaper.net/category/storyboard



## Programmerare

Du behöver ha en kort film att demonstrera med två scener och två
spritar.  Det går bra att använda exemplet i Resurser ovan, men hitta
gärna på något eget om du vill.

Den som leder programmeringen behöver kunna svara på de vanligaste
frågorna om Scratch som dyker upp, t.ex.:

* Hur man tar bort en sprajt man inte vill ha med

* Hur förminskar man en sprajt

* Hur gör man så en sprajt är vänd åt vänster (utan att vara roterad
  upp-och-ner)

* Hur återtar man en sprajt eller program som raderats av misstag

* Hur man sätter mittpunkten på en sprajt om man ritar den själv

* Hur en sprajt kan animeras med repetera-block för att snurra runt,
  röra sig eller byta klädslar

* Hur man kan styra sprajtar med tangentbordet

Det är rekommenderat att ägna några kvällar åt att programmera olika
saker i Scratch för att lära sig miljön.

Öva också på hur ni presenterar er själva och introducerar
programmering, samt givetvis på exemplet ni använder för att visa
eleverna hur de programmerar en film i Scratch.


# Genomförande

En 80-90 minuter lång lektion kan delas upp i de här ungefärliga
bitarna:

* 5 minuter: introduktion
* 10-15 minuter: demonstration
* 60 minuter: eleverna programmerar
* 5 minuter: avslutning

Inför början av lektionen bör alla datorer startas för att kontrollera
att de har nät och laddade batterier, och om det behövs koppla in
laddare.  Eleverna bör dock inte logga in på Scratch förrän de ska
börja programmera.


## Introduktion

Introduktionen är till för att ge en första förståelse för vad
programmering är.

Fråga eleverna om de vet vad programmering är, och vad man kan
programmera.  Svar kommer börja handla om spel och robotar, men försök
leda in dem på sånt man inte kan se.  Ett bra exempel är alla
dussintals, rent av hundratals, datorer som sitter i en bil.  Målet är
att få fram att datorer och programmering omger oss överallt, och att
eleverna kan ta kontrollen över detta med hjälp av programmering.

Förklara att när man programmerar skriver man ett program som talar om
för datorn hur den ska lösa ett problem.  För att datorn ska begripa
vad man säger måste man använda ett språk som den begriper - ett
programspråk.  Man måste vara jättenoga när man ger instruktioner till
datorn, för datorer är jättedumma!  Datorer förstår inte vad man
menar, utan gör bara exakt vad man säger.  Enda anledningen att
datorer verkar smarta är för att en smart programmerare lärt den vara
det.

> På den tidigare frågan kan ibland ett svar vara att man "programmerar
> mikron" eller liknande, och det är ett tillfälle att förklara
> skillnaden mellan att styra själv och att tala om för datorn hur den
> själv ska räkna ut vad som ska göras.

Och idag ska eleverna programmera i Scratch.  Det går att göra spel,
musik och mycket annat i det, men vi börjar med animerade filmer för
det är lätt att komma igång med och det kan sedan bygga vidare.


## Demonstration

Beskriv scenerna i exempelfilmen kort.

Logga in på ditt konto och öppna Scratcheditorn.  Visa de viktigaste
delarna av den:

* Ytan uppe till vänster där programmet visas
* Boxen med sprajtar under den
* Den tomma ytan till höger där man programmerar
* Pusselbitarna i mitten
* Att man kan byta språk på jordgloben uppe till vänster

Bygg upp din exempelfilm steg för steg och visa hela tiden vad som
händer.  Det är viktigt att inte göra klart allt på en gång, utan visa
vad som händer om man till exempel gömmer en sprajt och sedan glömmer
visa den igen, eller glömmer ange en startposition för en sprite med
`gå till x/y`.  Kör programmet två gånger vid sådana tillfällen för
att visa att det kanske blir rätt första gången, men inte andra.

De efterföljande sektionerna beskriver vad exemplet behöver visa och
varnar för vanliga fel som kan uppstå i elevernas program.


### Pusselbitar och funktioner som behövs

Exemplet behöver täcka in följande delar:

* Lägga till bakgrunder

* Lägga till sprajtar, och eventuellt ta bort defaultsprajten

* Händelser:
  * när grön flagg klickas på
  * när bakgrund växlar till

* Rörelse:
  * gå till x/y
  * glid N sek till x/y

* Utseende:
  * säg X i N sekunder
  * byt bakgrund till
  * visa
  * göm

* Kontroll:
  * vänta N sekunder


### Scener

Varje scen kopplas till en bakgrund.  Bakgrunderna kan namnges med
"Scen 1", "Scen 2" etc för att göra det enklare att hålla reda på
dem.

> Varning: om man byter namn på en bakgrund så uppdateras *inte*
> pusselbitarna `byt bakgrund till` eller `när bakgrund växlar till`
> utan de fortsätter använda det gamla namnet.  Det gör att programmet
> slutar fungera på svårförklarliga sätt.  Klicka på dropdownen i de
> pusselbitarna om en scen inte byts eller sprajtarna inte kör den nya
> scenens program för att se till att det nya namnet används.

Programmen för vad sprajtarna ska göra i scen ett kopplas till
`när grön flagg klickas på`.  Övriga sceners program kopplas till
`när bakgrund växlar till`.

> Det vore logiskare att låta programmen för den första scenen börja
> på `när bakgrund växlar till "scen 1"`, men det är enklare att börja
> programmera med `när grön flagga klickas på` när det bara finns en
> scen.  Det är sedan onödigt att riskera förvirra eleverna genom att
> ändra de programmen när man lägger till den andra scenen.

När den andra scenen läggs till och man använder
`byt bakgrund till "scen 2` och lägger till
`när bakgrund växlar till "scen 2"` för att börja programmera den är
det bra att påpeka skillnaden mellan ett kommando som byter bakgrund
och bara ska ges en gång, och händelser som startar nya program i
scenen (som kan användas flera gånger.)

> En del vill börja programmet under händelsen
> `när bakgrund växlar till "scen 2"` med
> `byt bakgrund till "scen 2"`, men då fastnar programmet i en oändlig
> loop där!  Det kan ses på att det programmet lyser gult men sprajten
> gör inget.

Det är bara en sprajt som kan byta till en given scen.  Typiskt är det
alltid någon sprajt som gör den sista handlingen i en scen, och då är
det också den som vet när det är dags att fortsätta till nästa.

> Ett vanligt misstag är att flera sprajtar byter till samma scen.  Då
> kommer programmen för den scenen startas om och köra flera gånger,
> samtidigt som program för den tidigare scenen inte ännu är klara.

För att filmen ska starta med rätt scen måste en av sprajtarna börja
sitt program under `när grön flagg klickas på` med `byt bakgrund till
"scen 1"`.

> Det här är en bra sak att låta bli fel i programmet efter att man
> visat hur man byter till scen 2, och fråga klassen hur man ser till
> att filmen börjar med rätt scen.


### Rörelse

Visa sprajten vad den ska göra: dra den till den plats på skärmen där
den ska börja scenen, och dra sedan in `gå till x/y` i programmet.  Då
är koordinaterna ifyllda med sprajtens position och man behöver inte
räkna ut rätt plats.  Dra sedan sprajten dit den ska röra sig och dra
in `glid N sekunder till x/y`.

> Här kan man förklara att `gå till x/y` egentligen borde heta
> `ställ dig på x/y`, för det sker omedelbart och man ser inte att
> sprajten går.

Det räcker att säga att x/y är vågrätt/lodrätt och att man kan se x/y
för en plats på skärmen genom att dra muspekaren över visningsytan, då
uppdateras x/y under den.


### Dialog

Använd `säg X i N sekunder` och `vänta N sekunder` för att programmera
dialoger eller andra interaktioner mellan sprajtar.


### Visa/göm

När man har flera sprajtar bör någon av dem bara vara med i en scen,
och behöver alltså programmeras med `visa` och `göm` i scenerna
beroende på om de ska vara med eller inte.

> Det här kan demonstreras genom att inte ha med de här bitarna först
> och därmed få sprajtar som är med i fel scener.  Se sedan till att
> de göms men glöm att lägga in `visa`, och kör sedan filmen en andra
> gång för att visa att sprajten fortsätter vara gömd.  Peka ut
> `visa`-biten men fråga klassen var den behöver läggas in för att
> sprajten ska synas vid rätt tillfälle.


## Programmering

Efter demonstrationen är det dags för eleverna att logga in på Scratch
och börja programmera, och ni kommer få springa omkring och svara på
deras frågor och lösa problem.

**Ta aldrig över en elevs dator när du hjälper till med ett problem.**
Resonera med dem och peka på skärmen om det behövs, men lösningen ska
så mycket som möjligt komma från dem själva, och allra minst ska de
klicka sig igenom den själva.


## Avslutning

Det kommer vara svårt att få klassen att sluta programmera, men se
till att hinna säga några avslutande viktiga saker om Scratch:

* När de är inloggade sparas det automatiskt, men man kan för
  säkerhets skull klicka på "Spara nu" längst uppe till höger.

* De kan sedan fortsätta på någon annan dator på en rast eller hemma
  genom att logga in på Scratch igen och klicka på "Mina grejer".

* Om de vill visa upp vad de gjort för världen kan de dela med sig av
  filmen.  Då blir det ett av över 20 miljoner delade Scratchprojekt.
  Vem som helst kan titta på filmen, titta inuti projektet för att se
  hur det är byggt, och remixa projektet.

* Eleverna kan också titta i andras delade projekt, och remixa dem.
  Då får de en kopia av projektet, som de kan dela i sin tur.  (Visa
  gärna det här på Scratchstartsidan)

* **Kom ihåg att logga ut från Scratch**


Ge gärna tips på hur eleverna kan fortsätta utforska programmering
själva:

* Klicka på frågetecknet längst upp till höger i programytan i
  Scratcheditorn för att få fram utmaningar, tips och tricks.

* Lös pussel på "Timmen med kod" på https://code.org/ Det är block
  liknande Scratch, men det här funkar även på iPads och
  androidplattor.

* Det finns massor med Youtubefilmer som visar hur man kan göra olika
  saker i Scratch.  AV-Media har spelat in filmer och samlat andra på
  svenska här: **TODO: inte publicerat än, länk och navigering
  kommer**
