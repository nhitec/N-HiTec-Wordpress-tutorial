# WordPress Project

Bienvenue dans le dépôt de votre projet WordPress. WordPress est une plateforme de publication personnelle qui met l'accent sur l'esthétique, les standards web et l'expérience utilisateur.

## Introduction

WordPress est un système de gestion de contenu (CMS) open-source et gratuit, qui permet de créer des sites web et des blogs de manière simple et rapide. Créé pour offrir une grande flexibilité, il est également extensible grâce à des thèmes et des plugins.

## Installation : La célèbre installation en 5 minutes

### Instructions d’installation

1. **Téléchargez et décompressez** le package dans un répertoire vide.
2. **Transférez** tous les fichiers dans votre répertoire de serveur web.
3. Ouvrez `wp-admin/install.php` dans votre navigateur pour lancer l’installation.
   - Si la configuration automatique échoue, ouvrez `wp-config-sample.php`, ajoutez vos informations de base de données et enregistrez-le sous `wp-config.php`.
4. Une fois le fichier de configuration prêt, le programme d'installation créera les tables nécessaires pour votre site. Suivez les instructions affichées.
5. Connectez-vous avec les informations d'identification choisies pendant l'installation.

### Configuration requise

Pour utiliser WordPress, il vous faut :
- **PHP** version 7.2.24 ou supérieure
- **MySQL** version 5.5.5 ou supérieure, ou **MariaDB** version 10.5 ou supérieure
- **HTTPS** supporté pour une meilleure sécurité
- Serveur web Apache avec le module `mod_rewrite` ou NGINX

Si vous utilisez un service d’hébergement, vérifiez que ces exigences sont bien respectées avant l'installation.

## Mise à Jour

### Mise à jour automatique
1. Connectez-vous à l’interface d’administration et rendez-vous dans `wp-admin/update-core.php`.
2. Cliquez sur "Mettre à jour" pour installer la dernière version.

### Mise à jour manuelle
1. **Sauvegardez** vos fichiers modifiés, y compris `index.php`.
2. Supprimez vos anciens fichiers WordPress, excepté ceux modifiés.
3. Téléchargez la dernière version et transférez les nouveaux fichiers.
4. Ouvrez `/wp-admin/upgrade.php` pour finaliser la mise à jour.

## Migration à partir d'autres systèmes

WordPress inclut des outils d'importation qui facilitent la migration depuis plusieurs autres plateformes (Blogger, Tumblr, Movable Type, etc.). Rendez-vous sur `wp-admin/import.php` pour accéder aux options disponibles.

## Découverte de WordPress

### Thèmes et Plugins

- **Thèmes** : Modifiez l'apparence de votre site en utilisant des thèmes. Pour explorer les options, rendez-vous dans `Apparence > Thèmes`.
- **Plugins** : Ajoutez des fonctionnalités avec des plugins. Installez-en de nouveaux depuis `Extensions > Ajouter`.

Des milliers de thèmes et de plugins gratuits et payants sont disponibles sur le site officiel WordPress.org.

### Réglages personnalisés

Après l'installation, explorez les options de personnalisation de votre site dans le tableau de bord (`wp-admin`). Configurez les réglages de lecture, d'écriture, de discussion, de permaliens, etc.

### Utilisation des Widgets et Menus

Personnalisez votre site en ajoutant des widgets (comme des menus de navigation, archives, et flux RSS) et en gérant les menus dans l'onglet Apparence.

## Ressources et Documentation

Pour en savoir plus et trouver des réponses aux questions courantes, consultez les ressources suivantes :
- [HelpHub](https://wordpress.org/documentation/) : Documentation officielle.
- [Forums de support](https://wordpress.org/support/forums/) : Trouvez des réponses et partagez des solutions avec la communauté.
- [Canal IRC sur Libera Chat](https://web.libera.chat/#wordpress) : Rejoignez des discussions en temps réel.
- [Développement et Bugs](https://core.trac.wordpress.org/) : Si vous êtes développeur, contribuez au code source ou signalez des bugs.

## Licence

WordPress est un logiciel libre et gratuit distribué sous la **GNU General Public License** version 2 ou ultérieure. Pour en savoir plus, consultez le fichier `license.txt`.

## Contribuez

WordPress est développé par une communauté internationale. Vous pouvez contribuer en :
- Signalant des bugs
- Développant des fonctionnalités
- Améliorant la documentation

Pour contribuer, rendez-vous sur [le site de développement de WordPress](https://make.wordpress.org/).

---

Merci d'utiliser WordPress ! Nous espérons que cette plateforme vous apportera satisfaction pour vos projets web.
