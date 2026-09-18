# Politique de confidentialité

**Dernière mise à jour : 18 septembre 2026**

Cette politique de confidentialité explique comment le développeur (« nous ») traite les informations dans Oh!MyMeds (« l’application »).

---

## 1. Données relatives aux médicaments et aux prises

L’application ne nécessite ni inscription ni création de compte.

- **Stockage sur l’appareil** : les médicaments ou compléments enregistrés, horaires et historiques de prise, informations de stock et notes sont en principe stockés sur votre appareil.
- **Pas de synchronisation cloud continue** : l’application ne synchronise pas en permanence ces données personnelles avec notre cloud.
- **Exclusion des champs personnalisés d’analyse et de diagnostic** : l’application est conçue pour ne pas envoyer les noms de médicaments, notes libres, notes de symptômes ni termes de recherche bruts comme champs personnalisés Firebase Analytics ou Crashlytics.

## 2. Changement d’appareil

Uniquement lorsque vous lancez explicitement le changement d’appareil depuis les réglages, l’application chiffre sur votre appareil vos données relatives aux médicaments et aux prises, puis envoie ces données chiffrées vers un service de transfert temporaire.

- Le contenu du transfert est chiffré avec une clé dérivée localement du code de récupération. Le traitement normal de nos serveurs ne reçoit pas en clair les noms de médicaments, l’historique des prises, les notes ou les symptômes.
- Les données chiffrées restent disponibles pendant au maximum **72 heures**. Après une restauration réussie ou une révocation, elles sont rendues indisponibles et supprimées dès que possible. En cas de problème temporaire de communication ou de suppression, l’expiration à 72 heures reste la garantie finale de conservation limitée.
- Le code de récupération est indispensable pour déchiffrer les données sur le nouvel appareil. Nous ne le conservons pas et ne pouvons ni récupérer ni réémettre un code perdu.
- Nous utilisons Firebase App Check et des limites de requêtes contre les abus. Des informations réseau peuvent être traitées à cette fin ; les métadonnées opérationnelles conservent un identifiant dérivé à sens unique plutôt que l’adresse IP brute.
- Le changement d’appareil est un transfert explicite et temporaire, et non une sauvegarde liée à un compte ni une synchronisation cloud continue.

## 3. Recherche de médicaments et suggestions

Pour les pays pris en charge, le terme recherché peut être transmis à un service public ou tiers d’information sur les médicaments, ou à un proxy de recherche exploité par nous, afin de retourner des suggestions.

L’application n’ajoute pas l’historique des prises, les informations de stock, les notes ni les notes de symptômes à ces requêtes.

## 4. Analyse de l’utilisation

L’application utilise **Google Firebase Analytics** afin de comprendre l’utilisation des fonctionnalités et d’améliorer la qualité. Les informations transmises peuvent inclure la version de l’application, la langue ou les paramètres régionaux, les interactions avec les fonctionnalités, des nombres regroupés et des informations techniques.

Nos événements personnalisés ne doivent pas contenir de noms de médicaments, notes libres, notes de symptômes, termes de recherche bruts, codes de récupération, capacités de transfert ni contenu du transfert. Analytics n’est pas utilisé pour la publicité ou le suivi des utilisateurs.

## 5. Diagnostic des plantages et erreurs

L’application utilise **Google Firebase Crashlytics** pour analyser les plantages et erreurs graves. Crashlytics peut collecter des traces de pile et des informations techniques sur l’application, le système et l’appareil.

Les diagnostics non fatals ajoutés par l’application sont limités à des noms d’opérations, étapes, classifications d’erreurs et codes numériques prédéfinis. Ils ne doivent pas contenir le message d’erreur d’origine, un chemin de fichier, une URL, un nom de médicament, une note, un terme de recherche, un code de récupération, une capacité de transfert ou le contenu du transfert. Aucun identifiant utilisateur Crashlytics personnalisé n’est défini.

Vous pouvez désactiver la collecte Crashlytics via **Partager les diagnostics de plantage** dans les réglages. Une modification peut prendre pleinement effet au prochain lancement.

## 6. Publicité et suivi

L’application n’affiche actuellement aucune publicité et n’utilise pas Google AdMob. Nous n’effectuons pas de suivi publicitaire via App Tracking Transparency (ATT).

## 7. Services tiers et infrastructure cloud

L’application utilise Firebase et Google Cloud. Les données chiffrées de changement d’appareil et les métadonnées opérationnelles minimales sont temporairement traitées et stockées sur une infrastructure Google Cloud gérée par nous.

- [Politique de confidentialité de Google](https://policies.google.com/privacy)
- [Confidentialité et sécurité Firebase](https://firebase.google.com/support/privacy)
- [Avis de confidentialité Google Cloud](https://cloud.google.com/terms/cloud-privacy-notice)

## 8. Modifications de cette politique

Nous pouvons mettre à jour cette politique lorsque les fonctionnalités de l’application ou les services tiers utilisés évoluent.

## 9. Nous contacter

- **Email** : k.lifetime.app+ohkusuri-support@gmail.com

---
*La version japonaise de cette politique de confidentialité fait foi.*
