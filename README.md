# 🌦️ Weather Today : Votre assistant météo moderne

**Weather Today** est une application Android élégante et performante, conçue pour offrir des prévisions météorologiques précises en temps réel. Grâce à l'intégration de l'API OpenWeatherMap, elle fournit des informations détaillées sur la météo actuelle et les prévisions, le tout dans une interface moderne et intuitive. Développée avec **Kotlin**, cette application allie fonctionnalité, esthétique et fluidité pour une expérience utilisateur optimale.

---

## ✨ Fonctionnalités principales

- 🌡️ **Météo actuelle :** Consultez la température, l'humidité, la vitesse du vent et l'indice de qualité de l'air.
- 📅 **Prévisions horaires :** Obtenez des prévisions détaillées pour chaque heure.
- 📱 **Widgets personnalisables :** Affichez en temps réel les informations météo directement sur votre écran d'accueil.
- 🔄 **Mises à jour automatiques :** Les données sont rafraîchies toutes les 15 minutes grâce à **WorkManager**.
- 📍 **Gestion de la localisation :** Détecte votre position pour des prévisions précises et gère intelligemment les permissions GPS.

---

## 🔑 Permissions requises

Pour fonctionner de manière optimale, **Weather Today** nécessite les permissions suivantes :

- **`ACCESS_FINE_LOCATION`** : Pour localiser précisément votre appareil.
- **`ACCESS_COARSE_LOCATION`** : Pour une localisation approximative, optimisant l'économie d'énergie.
- **`INTERNET`** : Pour récupérer les données météorologiques en ligne.
- **`SCHEDULE_EXACT_ALARM`** : Pour programmer des alarmes de mise à jour précises.
- **`RECEIVE_BOOT_COMPLETED`** : Pour relancer les mises à jour après le redémarrage de l'appareil.

---

## 🖼️ Aperçu de l'application
[🎥 Télécharger et visionner la vidéo](./videos/weather_app_video.mp4)

---

## 🚀 Utilisation

1. Clonez ce projet depuis son dépôt GitHub.
2. Importez-le dans **Android Studio**.
3. Ajoutez votre clé API OpenWeatherMap dans le fichier `MainActivity.kt` :

```kotlin
private val _openWeatherMapApiKey = "votre_cle_api_ici"


