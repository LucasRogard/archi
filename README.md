Problèmes :
- Pas de Get à la racine
- La commande run dev inscrite dans le package.json utilise nodemon qui n'est pas importé
- Toutes les routes sont dans le même fichier

Solution :
- Installation de nodemon/ ajout dans le package.json pour le npm install
- Mettre les routes dans des fichiers séparées dans un dossier routes

Avantages :
- Il est maintenant possible de lancer le fichier app.js en hot reload
- Il est plus facile de retrouver les différentes routes 