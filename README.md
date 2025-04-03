# Star Wars - Challenges JavaScript

## Structure du projet

- `index.html`  
  Page HTML principale.  
  Elle importe Bootstrap via CDN et inclut les scripts `utils.js` et `script.js`.

- `heroes.json`  
  Fichier contenant les données des héros (tableau d’objets JSON avec leurs caractéristiques).

- `utils.js`  
  Contient une classe `Utils` avec 10 méthodes statiques correspondant à chaque challenge.  
  Chaque méthode reçoit le tableau de héros et renvoie un héros ou un index selon les critères demandés.

- `script.js`  
  Charge le fichier `heroes.json` avec `fetch()`.  
  Génère dynamiquement un bouton pour chaque challenge.  
  Lors d’un clic sur un bouton, la méthode correspondante de `Utils` est appelée et le résultat est affiché dans un tableau HTML.  
  Le résultat est aussi affiché dans la console.

