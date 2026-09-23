# Site Faithfuldistribution

Ouvrez le dossier `outputs` dans VS Code, puis lancez `index.html` avec l’extension **Live Server**.

## Ajouter ou remplacer une photo

1. Copiez la nouvelle image dans le dossier `images`.
2. Donnez-lui un nom court, par exemple `feuilles-laurier.jpeg`.
3. Dans `index.html`, copiez un bloc `<article class="product-card">...</article>` et remplacez :
   - le chemin `images/nom-image.jpeg` ;
   - le texte `alt` ;
   - le nom et la description du produit.

Les photos utilisent `object-fit: contain` : elles restent entièrement visibles sans être coupées, quel que soit leur format.
