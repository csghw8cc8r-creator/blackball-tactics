BLACKBALL TACTICS — prototype PWA V1.1

TEST SUR MAC / WINDOWS
1. Décompresser le ZIP.
2. Ouvrir index.html pour un essai simple (le stockage des fichiers file:// dépend du navigateur).
3. Pour un test PWA fiable, ouvrir un terminal dans le dossier et lancer :
   python3 -m http.server 8080
   (Windows : py -m http.server 8080)
4. Ouvrir http://localhost:8080 dans Chrome ou Edge. Garder le terminal ouvert pendant le test initial.

INSTALLATION IPHONE / ANDROID
Une adresse HTTPS est nécessaire pour le service worker sur un téléphone. Aucun serveur de données n'est requis : publier uniquement les fichiers statiques du dossier sur un hébergement HTTPS, lorsque souhaité.
- iPhone/iPad : Safari, ouvrir l'adresse, Partager, Sur l'écran d'accueil (option ouvrir comme app web si proposée).
- Android : Chrome, menu, Installer l'application / Ajouter à l'écran d'accueil.
- Mac/Windows : Chrome/Edge, option d'installation dans le menu ou la barre d'adresse, si proposée.
Une fois le cache initial chargé, l'application peut fonctionner sans réseau. Les données restent propres à l'appareil et à l'adresse d'installation. Exporter les JSON avant de changer d'adresse ou d'effacer les données du navigateur.

OUTILS
Déplacer, trajectoires simples et multibandes (terminer le tracé), zones, contact, fantôme, texte, gomme, annuler/rétablir. Le quadrillage et les réglages sont sauvegardés automatiquement. La bibliothèque est locale. Export PNG de la table ou JSON réimportable. Pas de compte, de base distante, ni de dépendance externe.

LIMITES
Prototype graphique, modèles et marquages approximatifs ; numérotation Ultimate illustrative. Pas de moteur physique ni calcul automatique de rebonds. Les trajets sont dessinés manuellement. Pas de publication App Store/Google Play ni hébergement réalisé. Le code utilise JavaScript natif plutôt que React/TypeScript pour éviter toute installation de dépendances. La PWA reste évolutive. Tests sur appareils physiques à effectuer.
