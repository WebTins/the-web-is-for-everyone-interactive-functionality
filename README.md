# Bloemenveld Frankendael
Ik heb in sprint 8 de opdracht gekregen om een webapp/website te maken voor het Bloemenveld Frankendael waar bezoekers de planten kunnen ontdekken die in de bloei staan in het bloemenveld. Het doel is niet alleen om gebruikers planten laten ontdekken maar dat ze ook iets kunnen doen doormiddel van opdrachten uit te voeren waar gebruikers dan de kenmerken van een plant zien.

In sprint 9 heb ik mijn focus vooral gelegd bij het ophalen en versturen van data doormiddel van een GET en POST methode te gebruiken. Als POST methode heb ik bedacht dat gebruikers een opmerking kunnen achterlaten op een artikel (detailpagina) en dat je de opmerking kan verwijderen. Het verwijderen van een opmerking is eigenlijk alleen bedoeld voor de admin maar ik heb het toegevoegd zodat ik lange comments weg kan halen.

Bij dit project probeer ik alles aan het design te houden, omdat de opdrachtgever dat graag wilt samen met een vormalige student die het design heeft gemaakt. Zelf heb ik ook de mogelijkheid gekregen om mijn eigen ideeën toe te voegen aan het design als ik een goede reden heb dat de website beter maakt.

**Developer**

In dit project werk ik in mijn eentje 

- [Tin Nguyen](https://github.com/WebTins)

## Inhoudsopgave

## Beschrijving

[Website](https://the-web-is-for-everyone-interactive-6f4w.onrender.com/)

**Homepage**

De website is eerst ontworpen en daarna gebouwd met data die wordt opgehaald en ook data die wordt verstuurd. De homepagina toont op dit moment de collectie van de gebruiker en nieuws artikelen die de gebruiker kan lezen. De veldverkenner laat de flipcard zien van een plant.

<img width="150" height="300" alt="mobile-black" src="https://github.com/user-attachments/assets/0d32ae1a-e99e-4b18-9b60-f6af38161bd4" />

<img width="280" height="400" alt="tablet-black" src="https://github.com/user-attachments/assets/7cba5b1e-ebb0-4699-8076-dc81821c00ff" />

> Mockup van de homepagina

---

**Veldverkenner**

Op de veldverkenner heb ik zelf de veldverkenner nog niet in staan maar wel de flipcard die kan draaien om de gehele informatie van de plant te kunnen zien

<img width="138" height="400" alt="mobile-black (1)" src="https://github.com/user-attachments/assets/1425f976-07ec-49c5-bf56-c78e3f76ae7c" />
<img width="250" height="700" alt="tablet-black (4)" src="https://github.com/user-attachments/assets/08b3f1d8-0011-47c1-94aa-6137ecf8e6bb" />


> Mockup van de veldverkenner flipcard

https://github.com/user-attachments/assets/2f780256-bca0-4399-8308-0d00ad5bd0f6

---

**Nieuwsveld**

Bij het nieuwsveld is de bedoeling dat de gebruiker alle artikelen kan zien en kan lezen wanneer ze op een artikel drukken. Ik heb de artikel pagina gemaakt waar ook alle data opgehaald wordt vanuit de database.

<img width="138" height="300" alt="mobile-black (2)" src="https://github.com/user-attachments/assets/e6ae0fa1-ff1b-453f-9a8f-15c7beab48f6" />
<img width="241" height="600" alt="tablet-black (2)" src="https://github.com/user-attachments/assets/a66de3ad-bf2e-4138-9baa-43ffc9a2415c" />

https://github.com/user-attachments/assets/bfe887e2-e4f4-4529-bc91-df3227bc589e

---

**Artikel**

Nadat je bij het nieuwsveld op een artikel heb gedrukt dan kom je bij het volledige artikel terecht waar je de details kan lezen

<img width="241" height="600" alt="tablet-black (5)" src="https://github.com/user-attachments/assets/15bb93c4-8b64-434b-a875-391333084f4b" />

## Comment plaatsen

Wanneer je een artikel aan het lezen bent is het ook fijn om je mening te kunnen delen met anderen. En ik heb in Sprint 9 mijn focus gelegd met het versturen van data doormiddel van een POST te gebruiken. Het vesturen van een comment is gemaakt met [routes](https://github.com/WebTins/the-web-is-for-everyone-interactive-functionality/blob/56360eedd883659c206f05320142d46e9406dda1/server.js#L96-L134) die in NodeJS staan.

#### <ins>Feedforward & Feedback</ins>

Feedforward versturen van comment:

- Er zijn nog geen opmerkingen (Empty state)
- Met een hover over de "Verstuur" knop, krijgt de knop een donkere kleur

Feedback versturen van comment:

- Empty state verdwijnt
- Er staat een opmerking met een Naam, bericht en datum

https://github.com/user-attachments/assets/096b33ef-ed77-41de-813f-d66390906aaa

## Comment verwijderen

Wanneer je een opmerking hebt/ziet die niet toepasselijk is of op spam lijkt, is het fijn om als gebruiker/admin de comment te kunnen verwijderen. Ik heb mij deze sprint ook gefocust met het verwijderen van data dat ik mogelijk heb gemaakt met een POST [routes](https://github.com/WebTins/the-web-is-for-everyone-interactive-functionality/blob/56360eedd883659c206f05320142d46e9406dda1/server.js#L96-L134) waar de DELETE method wordt gebruikt.

#### <ins>Feedforward & Feedback</ins>

Feedforward verwijderen van comment:

- Er is een opmerking
- Met een hover over de "Verwijder" knop, krijgt de knop een lichtere kleur

Feedback verwijderen van comment:

- Opmerking verwdijnt
- Als er maar 1 opmerking was en is verwijderd, dan komt de empty state tevoorschijn

https://github.com/user-attachments/assets/96d34cfa-e4cc-415c-8bef-6798d9f9eb35



