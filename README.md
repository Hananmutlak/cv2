# webbplats för cv _hantering
Denna webbplats är en frontend-applikation som konsumerar ett REST API för hantering av arbetslivserfarenheter. Webbplatsen är byggd med vanlig HTML/CSS/JavaScript och använder Fetch API för kommunikation med backend-tjänsten.
## Live-demo
http://127.0.0.1:5501/index.html

## Funktioner
- Visa alla arbetslivserfarenheter i ett kortformat
- Lägga till nya erfarenheter via ett validerat formulär
- Ta bort befintliga erfarenheter
- Responsiv design
- Felhantering vid API-kommunikation
- Cross-Origin Resource Sharing (CORS.) stöd
## Teknologier
- **HTML5** - Semantisk struktur
- **CSS3** - Styling med flexbox och grid
- **JavaScript** - Dynamisk funktionalitet
- **Fetch API** - Kommunikation med backend
## Struktur
css/styles.css
about.html
add.html
index.html
### API-användning
Webbplatsen kommunicerar med följande APl

GET	    /api/work	Hämta alla erfarenheter
POST	/api/work	Skapa ny erfarenhet
DELETE	/api/work/   {id}	Radera erfarenhet
#### Utvecklingsmiljö
-Editor: VS Code med Live Server
-Node.js
### Relaterade repos
-https://github.com/Hananmutlak/cv2
-https://github.com/Hananmutlak/cv