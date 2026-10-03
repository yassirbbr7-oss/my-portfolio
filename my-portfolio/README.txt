MON PORTFOLIO

Structure :
- api/index.php : page du portfolio, CSS et effets 3D.
- public/images/ : vos images.
- public/docs/ : votre CV et les documents des ateliers.
- vercel.json : votre configuration Vercel, conservée sans modification.

Personnalisation :
Ouvrez api/index.php et modifiez le tableau $profil au début du fichier.
Ajoutez vos travaux dans les sections des ateliers M201 à M207.
Les descriptions des ateliers sont indicatives ; aucun travail réalisé n’est inventé.

Images et documents :
Les dossiers sont prêts à recevoir vos vrais fichiers. Aucune photo, logo ou CV factice n’est ajouté.
Pour Vercel, les fichiers présents dans public sont généralement accessibles à la racine :
public/images/photo.jpg devient /images/photo.jpg.
public/docs/cv.pdf devient /docs/cv.pdf.

Local :
Avec PHP installé, ouvrez un terminal dans api :
php -S localhost:8000
Puis ouvrez http://localhost:8000.

Déploiement :
Placez le contenu de my-portfolio à la racine de votre dépôt GitHub.
Importez ce dépôt dans Vercel en conservant vercel.json.
Le runtime PHP utilisé est celui de votre fichier fourni. Le déploiement n’a pas été testé ici.
