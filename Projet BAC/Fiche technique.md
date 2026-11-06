**

Spécifications Techniques : AppSwipe

Ce document définit les fondations techniques et l'environnement de développement requis pour la réalisation du projet AppSwipe.

# Titre du projet

AppSwipe

# Description du projet

AppSwipe est une application mobile centrée sur l'interaction utilisateur via une interface de navigation gestuelle. Le concept repose sur un système de cartes interactives permettant une prise de décision rapide et intuitive. L'application intègre des fonctionnalités de mise en relation en temps réel, un système de messagerie et une gestion de profils personnalisés. L'objectif principal est d'offrir une expérience utilisateur fluide avec un temps de réponse minimal.

# Langage de programmation et Framework

Le développement repose sur une architecture cross-platform pour optimiser la maintenance et le déploiement sur les différentes plateformes mobiles.

  

- Framework principal : React Native (version 0.7x)
    
- Langage : TypeScript
    
- Gestion d'état : Redux Toolkit ou TanStack Query
    
- Moteur de rendu : Hermes
    

# Environnement de développement

L'écosystème de développement est configuré pour supporter le cycle de vie complet du produit, de l'écriture du code au débogage matériel.

  

- Éditeur de code : Antigravity.
    
- Gestionnaire de paquets : npm ou yarn.
    
- Outils natifs :
    

- Xcode (pour la compilation iOS).
    
- Android Studio / SDK Manager (pour la compilation Android).
    

- Émulateurs : Simulateurs iOS (via Xcode) et Emulateurs Android (via AVD Manager).
    

# Système d'exploitation de développement

Pour assurer une compatibilité totale avec les outils de compilation requis par Apple et Google, le système d'exploitation utilisé est le suivant :

  

- Système : macOS (version 14 Sonoma ou ultérieure).
    
- Raison : Requis pour l'utilisation d'Xcode et la signature des paquets .ipa destinés à l'App Store.
    

# Dépendances de déploiement (stores)

Le déploiement de l'application s'effectue sur les deux plateformes majeures de distribution mobile.

  

- iOS : Apple App Store via la console App Store Connect. Nécessite un compte Apple Developer Program.
    
- Android : Google Play Store via la Google Play Console. Nécessite un compte développeur Google Play.
    
- Outils de distribution bêta : TestFlight (iOS) et Google Play Console Testing Tracks (Android).
    

**