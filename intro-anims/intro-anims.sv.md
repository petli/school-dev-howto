
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


## Tack

Stort tack till de lärare och klasser som hjälpt till med utvecklandet
genom att låta oss testa vad som funkar i praktiken:

* Lenhovdaskolan
* Furutåskolan (Växjö)
* Nottebäckskolan
* Hjortsbergskolan (Ljungby)
* Åsedaskolan


## Licens

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">Introduktion till programmering i Scratch: animerade filmer</span> av <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/petli/school-dev-howto/intro-anims/intro-anims.sv.md" property="cc:attributionName" rel="cc:attributionURL">Peter Liljenberg</a> är licensierat enligt <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

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

TODO: det här ska beskrivas utförligare

## Introduktion

* Vem är du/ni

* Vad är programmering, vad kan man programmera - klassdiskussion

* Programmmar -> program -> programspråk -> Scratch

* Datorer är dumma och begriper bara enkla instruktioner


## Demonstration

## Programmering

## Avslutning

* Spara

* Dela

* Remixa

* Logga ut

* Fortsätt hemma - Scratch, code.org
