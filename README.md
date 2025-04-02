# Bieb in bloei - Like Button/functie

![Screenshot 2025-04-02 124306-left](https://github.com/user-attachments/assets/9babe06a-267d-47b8-934e-a50e98a797cd)

![Screenshot 2025-04-02 124331-portrait](https://github.com/user-attachments/assets/7f1453f8-263f-4ae4-ae24-5f3321769a0c)

## Projectdoel
In dit project heb ik een interactieve like-button toegevoegd aan de stekjes collectie. Deze functie maakt het mogelijk voor gebruikers om stekje te liken.

## Oplevering
Geef hier aan wat je concreet hebt gemaakt tijdens de sprint:
- Een werkende like-knop toegevoegd aan stekje collectie.
- Een werkende loading state
- De knop is visueel herkenbaar en geeft feedback als het geliked is.
- Een werkende error state.
- Mobile Design
- breakpoints/CSS

## Technologieën
Noem hier de gebruikte technologieën:
- **Express.js & Node.js** – voor de backend en routing
- **Liquid** – voor het genereren van dynamische HTML
- **HTML, CSS & JavaScript** – voor de opbouw, styling en interactie aan de frontend

## Kenmerken

### HTML & Liquid Templates
Ik heb de onderdelen die ik nodig heb verdeeld in partials, zodat ik die apart kan inladen als ik die nodig heb in mijn pagina.
#### Partials voor playlists
https://github.com/SuleymanHG/the-web-is-for-everyone-interactive-functionality/blob/35f54988cd2e6917713a7b39c48a7cc3678d5761/views/partials/playlists.liquid#L1-L32

#### Partials voor liked functie
[https://github.com/SuleymanHG/the-web-is-for-everyone-interactive-functionality/blob/35f54988cd2e6917713a7b39c48a7cc3678d5761/views/partials/likedplaylist.liquid#L1-L33](https://github.com/Keremttc/the-web-is-for-everyone-interactive-functionality/tree/main/views/partials)

### Style guide 
https://github.com/Keremttc/the-web-is-for-everyone-interactive-functionality/tree/main/public/styles

### CSS
Ik heb in mijn css gebruik gemaakt van custom proerties om de huisstijl van Bieb in bloei te behouden. Verder heb ik gebruik gemaakt van nesting in de css, zodat de code makkelijker lezen en veranderen is. Ook maak ik gebruik van keyframes voor mijn loading state. En ik pas de rooting toe.
https://github.com/Keremttc/the-web-is-for-everyone-interactive-functionality/tree/main/public/styles


### JavaScript

#### De GET
Om de data kunnen ophalen van de directus data base heb ik get request uitgevierd in mijn Server.js 
https://github.com/SuleymanHG/the-web-is-for-everyone-interactive-functionality/blob/4b341bbe56527ed4b8a015aa6d524832c81b05ca/server.js#L82-L92

#### De POST
https://github.com/Keremttc/the-web-is-for-everyone-interactive-functionality/blob/main/server.js#L23-L33


# Website link
https://the-web-is-for-everyone-interactive-bm62.onrender.com/
![Screenshot 2025-04-02 141106-portrait](https://github.com/user-attachments/assets/58e409cc-333a-4fe3-b87e-f9d2e9e18e34)


