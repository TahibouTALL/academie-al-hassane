# Académie Al Hassane

Site de l'Académie Al Hassane : encadrement en ligne en Sciences Physiques avec M. Ba, livres d'exercices corrigés, test de niveau et inscription par WhatsApp.

Domaine prévu : www.academie-al-hassane.com

## Contenu du dépôt

- `index.html` : le site complet, sur une seule page (accueil, encadrement, livres, test de niveau, contact)
- `favicon.svg` et `apple-touch-icon.png` : les icônes du site
- `og-image.jpg` : l'image qui s'affiche quand on partage le lien sur WhatsApp ou Facebook
- `robots.txt` et `sitemap.xml` : pour que Google trouve le site

Le site n'a besoin d'aucun serveur particulier : un hébergement de fichiers statiques suffit. Pour le voir sur son ordinateur, il suffit d'ouvrir `index.html` dans un navigateur.

## Modifier les informations

Ouvrir `index.html` avec un éditeur de texte (VS Code, Notepad++...).

Dans le script en bas du fichier, le bloc `SITE` regroupe les réglages :

- `whatsapp`, `tel`, `telAffiche` : le numéro de M. Ba
- `email` : l'adresse e-mail du site (laisser vide pour la masquer)
- `prix` : le prix des livres de physique et de devoirs (laisser vide pour afficher « Prix sur WhatsApp »)

Les textes (formules d'encadrement, niveaux, description des livres, questions fréquentes) se modifient directement dans le HTML.
Les formulaires ne passent par aucun serveur : ils préparent un message WhatsApp que l'élève envoie lui-même.

## Mettre le site en ligne

Au choix :

1. **GitHub Pages** (gratuit) : dans Settings > Pages, choisir « Deploy from a branch », branche `main`, dossier `/ (root)`. Le site est alors visible sur `https://tahiboutall.github.io/academie-al-hassane/`.
2. **Vercel** ou **Netlify** (offre gratuite) : importer ce dépôt GitHub. Chaque push met le site à jour automatiquement.
3. **Hébergeur classique** (cPanel, o2switch, Hostinger...) : envoyer les fichiers dans le dossier `public_html`.

Puis brancher le domaine : ajouter `academie-al-hassane.com` et `www.academie-al-hassane.com` dans les réglages de l'hébergement, et créer chez le registraire du domaine les enregistrements DNS indiqués par l'hébergeur.

## À vérifier avec M. Ba avant la mise en ligne

- Les niveaux enseignés (3ème, Seconde, Première, Terminale S1 et S2)
- Les trois formules d'encadrement et ce qu'elles contiennent
- Le déroulement des cours en ligne (visioconférence, groupe WhatsApp de la classe)
- Les titres exacts des livres, leurs prix et leur disponibilité
- Les couvertures : celles du site sont des illustrations, à remplacer par les photos des vrais livres
- Une photo de M. Ba, si possible, pour la section « Le professeur »
