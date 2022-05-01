# Booki

---
Booki is een online voorraad beheer systeem gespecialiseerd in nieuwe en tweedehandse publicaties. 
Booki maakt gebruik van een database waar alle ISBN registraties vanaf 1970 instaan. 
Elke avond worden daar de nieuwste boeken aan toegevoegd. 

>Een publicatie invoeren is heel eenvoudig

1. Selecteer of het gaat om een nieuw of tweedehandse publicatie, 
2. Scan de barcode en alle bij ons bekende gegevens worden vooraf ingevuld. 
3. Je hoeft dan alleen nog maar de inkoopprijs , verkoopprijs en de locatie waar het boek staat op te geven.

---

## Navigatie menu

![De Booki Navbar](img\BookiNavbar.png)

* **Home**
* **Voorraad** Hier kun je alle producten bekijken die ooit zijn ingevoerd.
* **Invoer** De plek om alle nieuwe producten snel en makkelijk in te voeren.
* **Uitgaand** Hiermee ga je naar het afboeken van producten.
*  **Sneluitvoer** Hier kun je meerdere producten tegelijk uitvoeren.
* **Orders** Naar orderoverzicht, hier kun je ook snel zien of er nieuwe orders zijn en of er nog orders liggen die verzonden moeten worden.
* **Jouw bedrijfsnaam** Hieronder staan alle instellingen voor het bedrijf
* **Uitloggen**

## Home

* De pagina waar alles begint, vanaf hier kun je overal snel naar toe.
* Bijv naar statistieken, voor meer details hierover, ga naar de statistieken pagina.
* Hier kun je ook in 1 oogopslag zien of er nog openstaande orders zijn, en wanneer je voor het laatst een upload hebt gedaan naar boekwinkeltjes.
* Onderaan staat een handige grafiek over een heel jaar van je omzet en verkopen per dag. Waarin je in 1 oogopslag kunt zien aan de hand van de kleur hoe goed die dag was.

## Voorraad

Als je naar deze pagina gaat, of als je op de refresh knop drukt, worden automatisch de 25 laatst gewijzigde producten getoond. 
Je kunt hier ook zelf zoeken, met nog 3 extra opties.

![De Booki voorraad search](img\VoorraadSearch.png)

* Zoeken 'alleen op voorraad', producten waar geen voorraad van is worden dan niet meer weergegeven.
* Zoeken op Conditie (Nieuw, Tweedehands of Ramsj).
* Zoeken op een zelftoegevoegde tag.
* Andere filter opties, hierin kan van alles worden toegevoegd. Is er iets waar je graag op zou willen zoeken, laat het ons weten.

Natuurlijk zijn deze opties te combineren.

Als er producten gevonden zijn, kun je de belangrijkste gegevens per product bekijken in de tabel. Wil je de samenvatting lezen van een
product, blijf dan met de muis even stil staan op het product van keuze, en een samenvatting zal te voorschijn komen. 

* Titel, auteur en ean.
* Type is de conditie, Nieuw, Ramsj of Tweedehands(Als nieuw, Goed, Redelijk, Matig)
* Aantal, is het actuele aantal op voorraad.
* Locatie, waar het boek wordt bewaard/staat in de winkel.
* En de verkoopprijs inclusief btw in euros.
* Onder acties staat de knop om naar de product detail pagina van dat product te gaan.

De gevonden producten staan gesorteerd op hoe goed ze voldoen aan jouw zoekopdracht. De best matchende staat bovenaan.

Voor meer informatie over hoe het beste te zoeken in Booki, ga naar de [FAQ pagina](faqs.md) en klik daar op het hoofdstuk "Zoeken in Booki voorraad".

## Product detail pagina

Hier kun je alle gegevens van je product terugvinden. Om hier te komen moet je eerst het product zoeken in voorraad. 
En dan op het boek icoontje klikken onder acties van je boek.

Als je wijzigingen wilt aanbrengen aan een product doe je dat hier, bijv prijs aanpassen, notities maken bij een product.

Grijs gekleurde gegevens zijn niet wijzigbaar. De gegevens die je hier ziet zijn product eigen. Aantal bijvoorbeeld, is het totale aantal op
voorraad, van alle leveranciers. Wil je weten van welke leveranciers je dit boek hebt, kijk dan in het log, De blauwe button met 
de tekst "Toon log". Hier zie je precies welke in mutaties en uit mutaties er voor dit product zijn gedaan. 

Boven de "Toon log" button, is de "Print label" button. Als je hier op klikt kun je labels uitprinten voor je product. 

!!! danger "Let op!"
	hier weten we dus niet voor welke mutatie je een label wilt printen. Je kunt van meerdere mutaties voorraad hebben. Kijk bij meerdere opties goed welke je moet hebben. 

Hier kun je ook een aanbieding maken van je product. Als je een aanbieding maakt van je product, wordt dit op de label en op de website weergegeven.

![De Booki voorraad search](img\AanbiedingLabel.png) ![De Booki voorraad search](img\WebshopDiscountProduct.png)

Als je wijzigingen maakt in gegevens die op het label staan, zul je dus voor elk product een nieuw label moeten uitprinten. Maar dit hoeft niet. De barcode veranderd namelijk niet.

De verandering op de website hoef je helemaal niks voor te doen, dat gaat allemaal automatisch.

## Invoer
 
 Voordat je kunt zoeken op Ean, moet je eerst het invoer type en conditie selecteren. Doe dit nauwkeurig, dit wordt allemaal bij de mutatie opgeslagen.
 
* **Aankoop** : Ingekocht bij externe partij.
* **Correctie** : Een boek dat kwijt was en weer wordt gevonden bijv.
* **Gecreëerd** : Denk aan kaartjes voor een lezing.
* **Terug gebracht** : Retour van een verkocht artikel.

Hier is ook de mogelijkheid om 'Snelle locatie' aan te zetten. Ga je een hele reeks boeken voor 1 locatie invoeren, zet dit dan aan. Zodat je de locatie maar 1x hoeft te selecteren. Maar **LET OP** vergeet dit niet weer uit te zetten als je boeken gaat invoeren voor een andere locatie.
    
Als je je selecties hebt gemaakt, scan dan het ean nummer van je product. En Booki gaat voor je op zoek.

Als het product al in je collectie zit, dan worden de eerder ingevulde gegevens getoond. Staat het nog niet in je collectie dan worden 
de belangrijkste gegevens die Booki heeft getoond.

Vul alleen nog de locatie, verkoopprijs, het aantal en de winstmarge in bij een nieuw product.

Bij tweedehands producten, moet ook nog de conditie en een omschrijving van de conditie worden ingevuld.    

Hier is ook de mogelijkheid om meteen een kortings product te maken. Vul dan ook de originele prijs is. Zorg er wel voor dat de verkoopprijs lager is dan de originele prijs.

Na het invoeren is er de mogelijkheid om labels uit te printen, en kun je daarna het volgende artikel invoeren.

## Uitgaand 

Als er een product uitgaat dat niet via de kassa of een online verkoop gaat. Of als er iets is misgegaan en je moet een product handmatig afboeken. 
Dan kun je dat hier doen. 

Kies je mutatie type. Dit is de reden van afboeken. Het kan om een verkoop gaan, maar ook om een boek dat kwijt is (Afschrijving).

Je kunt hier zoeken op ean, of op de uitgeprinte label die op het boek wordt geplakt.

Voordeel van de label is, dat er altijd maar 1 uniek product wordt gevonden. Je gaat dan altijd meteen naar het afboekscherm.

Zoek je op ean, dan kunnen er meerdere producten worden gevonden. Een zelfde product kan namelijk een andere conditie hebben. Booki maakt hier onderscheid in.
Maak een keuze als er meerdere producten zijn gevonden en vervolgens kan het nog zijn, dat er meerdere mutaties van je gekozen product op voorraad zijn.
Als je al nieuwe producten hebt binnengekegen voordat de oude op zijn bijv. Maak een keuze uit de mutaties en dan kom je in het afboekscherm. Wordt er maar 1 product
of mutatie gevonden, dan slaat Booki deze stappen automatisch over.

In het afboekscherm staan weer de meest gebruikelijke gegevens van het product. 
Geef altijd aan hoeveel producten je wilt afboeken (standaard op 1) en een omschrijving van de mutatie.
  
## Sneluitvoer

Deze uitvoer van producten werkt alleen met Booki-barcodes. Het voordeel is wel dat je hier meerdere producten in 1x kunt afboeken.

Voordat je begint, moet je er wel voor zorgen dat je het juiste mutatie type hebt gekozen, dit kun je tijdens het proces niet meer wijzigen.

Elk gescand boek wordt in de lijst gezet. Heb je meerdere dezelfde producten, uit dezelfde mutatie, dan wordt het aantal verhoogd. Let op dezelfde producten kunnen een verschillende mutatie hebben. En dus apart in de lijst staan.

Alle boeken gescand? Dan zie je de totaal prijs, en het totaal aantal gescande producten. Je kunt nu ook eventuele kortingen toepassen. Bookie voert deze kortingen automatisch door over alle gescande producten. Je kunt natuurlijk ook op een product zelf een korting doorvoeren, **let wel op**, dit moet je doen voordat je korting geeft op de totaalprijs. 
Als je korting invuld , en weer scant wordt de korting gereset. Gebruik dus alleen korting als je helemaal klaar bent met scannen. Zo gauw je op de knop afhandelen drukt, worden al je gescande producten afgeboekt.
  
## Orders

Een order kan 7 statussen hebben. De 5 waar iets meegedaan moet worden zijn hier in tabjes verdeeld :

* **Wachten op betaling** : Een klant heeft een order geplaatst, maar nog niet betaald. Er kan wat tijd zitten tussen bevestiging van betalen en order plaatsen. 
Orders die hier voor langere tijd staan kun je annuleren. De boeken in deze orders staan op gereserveerd. Ze zijn specifiek voor deze order en kunnen dus ook niet verkocht worden tot dat je de order annuleert.
Als je een order annuleert, geef dan een reden op, deze reden wordt naar de klant gestuurd in een mail.
* **Betaald** : Nieuwe orders die betaald zijn, komen hier terecht. Als er een gele vrachtwagen staat achter het order Id, betekent dat dat het om een verzend order gaat.
Heb je de producten van de order verzameld, zet hem dan een status verder. De klant krijgt een mail, met order bevestiging. 
En als het een ophaal order is, dan bevestiging dat de order opgehaald kan worden.
* **Klaar voor verzending** : Als je de verzending hebt geregeld, dan zet je hem weer door, je kunt dan de track en trace invullen, 
die wordt weer in een mail naar de klant gestuurd.
* **Wordt opgehaald** : Deze orders liggen klaar om opgehaald te worden. Worden ze opgehaald, zet ze dan door, en de order komt op de status afgehandeld en in het archief.
Er wordt nog een mail naar de klant gestuurd dat de order is opgehaald.
* **Verzonden** : Deze orders zijn verzonden, je kunt ze doorzetten of nog even laten staan tot het pakket is aangekomen.
    
De overige 2 statussen zijn :

* **Afgehandeld**
* **Geannuleerd**  
  
Deze kun je bekijken als je het order nummer weet, dit doe je door het ordernummer te typen in de zoekbar, boven de status tabs. Als er een order wordt gevonden met het Id,
dan kom je meteen in het detail overzicht van de order. Zie volgende onderwerp.

## Order detail scherm 

Hier zie je de details van de bestelling, de producten, de gegevens van de klant en de status van de order. De eerste regel bij de producten is de barcode van het product.
Zorg ervoor dat je het juiste product uit de voorraad pakt. 

    Bijv barcode : 9789079677726-I-0000004489.
    De eerste 13 cijfers is het ean nummer, er tussen staat de -I- dit wil zeggen dat het volgende nummer 
    een mutatieIn Id is. Zorg ervoor dat je product dezelfde code heeft.

Als je een order annuleert worden de artikelen uit die order weer terug op voorraad gezet, in het orderstatus log van de order, komen de gegevens van de geannuleerde producten te staan. Zodat je altijd kunt zien wat er besteld was.