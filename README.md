# CV Webbplats

En frontend-webbapplikation som konsumerar ett REST API för att visa och hantera arbetserfarenheter.

## Sidor

- **index.html** - Visar alla arbetserfarenheter hämtade från API:et
- **add.html** - Formulär för att lägga till en ny arbetserfarenhet
- **about.html** - Information om webbplatsen och dess syfte

## Funktionalitet

Webbplatsen använder Fetch API för att kommunicera med ett REST API kopplat till en MongoDB-databas.

GET – hämtar alla arbetserfarenheter
POST – lägger till en ny arbetserfarenhet
DELETE – tar bort en befintlig arbetserfarenhet

All data valideras i JavaScript innan den skickas till API:et för att säkerställa att inga tomma eller ogiltiga värden sparas.

## API

Webbplatsen kommunicerar med detta API:
https://backend-laboration3-uppgift1-production.up.railway.app/api/workexperience

## Tekniker

HTML, CSS och JavaScript
Backend: Node.js, Express
Databas: MongoDB (via Mongoose)
Deployment: Railway + GitHub Pages

## Publicerad webbplats
Webbplatsen publiceras automatiskt via **GitHub Pages**.
[Länk till den publicerade webbplatsen](https://aliatwood.github.io/Backend-laboration2-uppgift2/)
