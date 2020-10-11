# Welcome to Booki

---
Booki is een online voorraad beheer systeem gespecialiseerd in publicaties. 
Dit voor zowel nieuwe als tweedehands publicaties.
Booki maakt gebruik van een database waar alle ISBN registraties vanaf 1970 instaan. 
Elke avond worden daar de nieuwste boeken aan toegevoegd. 

Een publicatie invoeren is dus supersimpel. Selecteer of het gaat om een nieuw of tweedehandse publicatie, 
scan de barcode en alle bij ons bekende gegevens worden vooraf ingevuld. 
Je hoeft dan alleen nog maar de inkoopprijs , verkoopprijs en de locatie waar het boek staat op te geven.
---

## Navigatie menu
* Home
* Voorraad - Hier kun je al jouw artikelen bekijken die ooit zijn ingevoerd.
* Invoer - De plek om al jouw nieuwe artikelen snel en makkelijk in te voeren.
* Uitgaand - Hiermee ga je naar het afboeken van artikelen.
* Orders - Naar orderoverzicht, hier kun je ook snel zien of er nieuwe orders zijn, en of er nog orders liggen die verzonden moeten worden.
* Jouw bedrijfsnaam - Hieronder staan alle instellingen voor jouw bedrijf
* Uitloggen

## Home

* De pagina waar alles begint, vanaf hier kun je overal snel naar toe.
* Hier kun je ook in 1 oogopslag zien of er nog openstaande orders zijn, en wanneer je voor het laatst een upload hebt gedaan naar boekwinkeltjes.


## Voorraad

Als je naar deze pagina gaat, worden automatisch de 25 laatst gewijzigde producten opgehaald.
Je kunt hier ook zelf zoeken, met nog 3 extra opties.

* Zoeken alleen op voorraad, producten waar geen voorraad van is worden dan niet meer weergegeven.
* Zoeken op Conditie (Nieuw of Tweedehands).
* Zoeken op een tag.

Natuurlijk zijn deze opties te combineren.

Als er producten gevonden zijn, kun je de belangrijkste gegevens zien. 

* Titel, auteur en ean.
* Type is de conditie, Nieuw of Tweedehands(Als nieuw, Goed, Redelijk, Matig)
* Aantal, is het actuele aantal op voorraad.
* Locatie, waar het boek wordt bewaard/staat in de winkel.
* En de verkoopprijs inclusief btw in euros.

## Invoer
 
 Voordat je kunt zoeken op Ean, moet je eerst het invoer type en conditie selecteren. Doe dit nauwkeurig, dit wordt allemaal bij de mutatie opgeslagen.
 
* Aankoop : Ingekocht bij externe partij.
* Correctie : Een boek dat kwijt was en weer wordt gevonden bijv.
* Gecreeerd : Denk aan kaartjes voor een lezing.
* Terug gebracht : Retour van verkocht artikel.
    
Als je je selecties hebt gemaakt, scan dan de barcode van je artikel. En Booki gaat voor je op zoek.

Als het boek al in je collectie is, dan worden de eerder ingevulde gegevens getoond. Staat het nog niet in je collectie dan worden 
de belangrijkste gegevens die booki heeft getoond.

Vul alleen nog de locatie, verkoopprijs, het aantal en de winstmarge in bij een nieuw product.

Bij tweedehands producten, moet ook nog de conditie en een omschrijving van de conditie worden ingevuld.    

Na het invoeren is er de mogelijkheid om labels uit te printen, en kun je daarna het volgende artikel invoeren.

## Uitgaand 

Als er een product uitgaat dat niet via de kassa of een online verkoop gaat. Of als er iets is misgegaan en je moet een product handmatig afboeken. 
Dan kun je dat hier doen. 

Kies je mutatie type. Dit is de reden van afboeken. Het kan om een verkoop gaan, maar ook om een boek dat kwijt is (Afschrijving).

Je kunt hier zoeken op ean, of op de uitgeprinte label die op het boek wordt geplakt.

Voordeel van de label is, dat er altijd maar 1 uniek product wordt gevonden. Je komt dus altijd meteen in het afboekscherm.

Zoek je op ean, dan kunnen er meerdere producten worden gevonden. Een zelfde boek kan namelijk een andere conditie hebben.
Als je dan een product hebt gekozen, kunnen er van dat product ook nog verschillende mutaties zijn. Hier moet je weer een keuze uitmaken.
Dan kom je in het afboekscherm.

In het afboekscherm staan weer de meest gebruikelijke gegevens van het product. 
Geef altijd aan hoeveel producten je wilt afboeken (standaard op 1) en een omschrijving van de mutatie.
    
## Orders

Een order kan 7 statussen hebben. De 5 waar iets meegedaan moet worden zijn hier in tabjes verdeeld :

* Wachten op betaling : Mensen hebben een order geplaatst, maar nog niet betaald. Er kan wat tijd zitten tussen bevestiging van betalen en order plaatsen. 
Orders die hier voor langere tijd staan kun je annuleren. De boeken in deze orders staan op gereserveerd. Die kunnen dus ook niet verkocht worden.
* Betaald : Nieuwe orders die betaald zijn, komen hier terecht. Als er een gele vrachtwagen staat achter het order Id, betekent dat dat het om een verzend order gaat.
Heb je de producten van de order verzameld, zet hem dan een status verder. De klant krijgt een mail, met order bevestiging. 
En als het een ophaal order is, dan bevestiging dat de order opgehaald kan worden.
* Klaar voor verzending : Als je de verzending hebt geregeld, dan zet je hem weer door, je kunt dan de track en trace invullen, 
die wordt weer in een mail naar de klant gestuurd.
* Wordt opgehaald : Deze orders liggen klaar om opgehaald te worden, worden ze opgehaald. Zet hem dan door, en de order komt op status afgehandeld en in het archief.
Er wordt nog een mail naar de klant gestuurd dat de order is opgehaald.
* Verzonden : Deze orders zijn verzonden, je kunt ze doorzetten of nog even laten staan tot het pakket is aangekomen.
    
De overige 2 statussen zijn :

* Afgehandeld
* Geannuleerd  
  
Deze kun je bekijken als je het order nummer weet, dit doe je door het ordernummer te typen in de zoekbar, boven de status tabs. Als er een order wordt gevonden met het Id,
dan kom je meteen in het detail overzicht van de order. Zie volgende onderwerp.

## Order detail scherm 

Hier zie je de details van de bestelling, de producten, de gegevens van de klant en de status van de order. De eerste regel bij de producten is de barcode.
Zorg ervoor dat je het juiste product uit de voorraad pakt. 

    Bijv barcode : 9789079677726-I-0000004489.
    De eerste 13 cijfers is het ean nummer, er tussen staat de -I- dit wil zeggen dat het volgende nummer 
    een mutatieIn Id is. Zorg ervoor dat je product dezelfde code heeft.
          
