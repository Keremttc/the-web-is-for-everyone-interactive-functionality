# Bieb in bloei - Like Button/functie 💯

<img width="350" alt="Image" src="https://github.com/user-attachments/assets/9babe06a-267d-47b8-934e-a50e98a797cd"/>

<img width="350" alt="Image" src="https://github.com/user-attachments/assets/7f1453f8-263f-4ae4-ae24-5f3321769a0c"/>

## Projectdoel 🚀 
In dit project heb ik een interactieve like-button toegevoegd, waarmee gebruikers stekjes kunnen liken. Daarnaast heb ik een POST-functie geïmplementeerd, waarmee gebruikers stekjes kunnen liken.

## Inleiding 🪴

Bieb in bloei is een nieuw initiatief dat bibliotheken en tuinen samenbrengt om de kracht van lezen, leren en natuur te combineren. De belangrijkste focus van Bieb in bloei is het verder brengen van kennis en inspiratie door het aanbieden van lees en tuinactiviteiten voor jong en oud. Zij bieden een unieke gelegenheid om de voordelen van boeken en groen met elkaar te combineren. Bieb in bloei biedt een platform voor educatie, ontspanning en creativiteit.

## Beschrijving 📚

Op de Bieb in bloei stekjes pagina kunnen gebruikers hun favoriete stekje een like geven. Wanneer een gebruiker op het hartje klikt, wordt er een laadanimatie weergegeven om aan te geven dat de like in verwerking is. Deze laadanimatie wordt getoond door middel van een loading state. Dit helpt de gebruiker te begrijpen dat de actie is ontvangen en in behandeling is, zonder dat er verwarring ontstaat. De toevoeging van een loading state is een klein maar belangrijk en handig onderdeel van het verbteren van de gebruikerservaring op de website. [Bekijk de live site](https://the-web-is-for-everyone-interactive-bm62.onrender.com/)

## HTML Beschrijving 📚

## Responsive 🎨

De website is ontwikkeld volgens het mobile-first principe, waarbij de layout begint met één kolom op het kleinste formaat. Naarmate de schermgrootte toeneemt, wordt de content horizontaal gepositioneerd. Bij de verschillende formaten ziet de indeling er als volgt uit: op formaat S is er één kolom, op M worden de stekjes in twee kolommen naast elkaar weergegeven, op L in drie kolommen en op XL in vier kolommen. 

<img width="350" alt="Image" src="https://github.com/user-attachments/assets/01223f5b-1927-4734-a97a-5e5295ddfcbc"/>

## Ontwerpkeuzes ✏️

Deze sprint heb ik me gefocust op het herontwerpen van de stekjes pagina, met name heb ik mij gericht op de accent kleuren van de huidige website. Het was belangrijk om de kleuren van "Bieb in Bloei" toe tr passen. Ik heb hierbij inspiratie gehaald uit de bestaande pagina’s van Bieb in bloei.

<img width="350" alt="Image" src="https://github.com/user-attachments/assets/17cdae11-260b-4e58-8f14-ddede91a07d5"/>

## Color contrast analyser 🎨

Voor dit herontwerp was het van belang om het kleurcontrast te testen in verband met de toegankelijkheid. Op basis van de testresultaten heb ik enkele teksten aangepast naar een andere kleur om te voldoen aan de toegankelijkheidsrichtlijnen, zodat de leesbaarheid en gebruiksvriendelijkheid voor iedereen juist is.

<img width="350" alt="Image" src="https://github.com/user-attachments/assets/84864fc2-e7a5-4e02-af8f-74af24465045"/>

<img width="350" alt="Image" src="https://github.com/user-attachments/assets/69aa2a0c-9f7d-46d9-951f-65b46208e9d3"/>

## UI states

In deze sprint heb ik ook gewerkt aan verschillende UI-states, zoals een loading state en error state. Hieronder staan een aantal voorbeelden van de uitgewerkte states. Sommige states heb ik al volledig uitgewerkt, daarin tegen heb ik nog geen 'succesion-state'. Zo wil ik bijvoorbeeld de succesion-state nog toevoegen aan de 'loading-state' knop om te zorgen voor een duidelijke feedback.


<img width="350" alt="Image" src="https://github.com/user-attachments/assets/96983e91-a52e-40ee-bbaf-056e41b11a4a"/>

<img width="350" alt="Image" src="https://github.com/user-attachments/assets/00c1a63d-5bb0-4592-9f43-81dfd5351135"/>

## featers

Binnen de interactie geef ik zowel feedback als feedforward aan de gebruiker, zo weet de gebruiker duidelijk wat hen te verwachten staat. De muis verandert in een pointer zodra hij op de like terrecht komt. Bij een klik krijg je een 'Loading' animatie te zien. Dit geeft feedback aan de gebruiker dat er iets gebeurt op basis van de klik en feedforward door een laadanimatie. 

## Progressive Enhancement

Progressive enhancement bestaat uit drie stappen. De eerste stap is ervoor zorgen dat de functie werkt zonder enige styling of extra’s, zodat het op elk apparaat of in elke browser bruikbaar is. In de tweede stap voeg je eenvoudige styling toe, zoals fonts, kleuren en afmetingen, om de uitstraling te verbeteren zonder de functionaliteit te verstoren. De derde stap omvat het toevoegen van animaties en andere visuele verbeteringen. Dit doe je als laatste, omdat je ervoor wilt zorgen dat de basisfunctionaliteit eerst goed werkt. Bij deze stap houd je rekening met het gebruik van @supports, zodat als de browser de animatie of styling niet ondersteunt, de functionaliteit van stap 1 alsnog werkt.


