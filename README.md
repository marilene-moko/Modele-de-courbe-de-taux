# Modèles de Courbe de Taux

## Objectif du projet

Ce projet vise à explorer les concepts de base des **modèles de courbe de taux**, en abordant les sujets suivants :
- Reconstituer une courbe de taux zéro-coupon
- Valoriser des instruments de taux dérivés (caplets, swaptions)
- Explorer le modèle de Hull & White pour la calibration et le pricing d’options de taux

## Contenu

### 1. **Reconstruction de la courbe des taux zéro-coupon**
- Utilisation de la méthode du **bootstrapping** et de l'**interpolation spline** pour reconstruire la courbe des taux zéro-coupon à partir des données de marché.

### 2. **Valorisation des instruments de marché**
- **Valorisation des dérivés de taux** comme les caplets et les swaptions.
- Construction des **courbes de taux forward**.

### 3. **Modèle de pricing des caplets et swaptions**
- Calcul des prix de marché à partir de la courbe zéro-coupon.
- **Comparaison des interpolations linéaire vs spline** pour déterminer la méthode la plus adaptée à la valorisation.

### 4. **Modèle de Hull & White**
- **Transition depuis le modèle HJM** (Heath-Jarrow-Morton) vers le modèle Hull & White.
- Formulation mathématique du modèle et **calibration** à partir des données de marché.
- **Simulation Monte-Carlo** pour la valorisation d’options structurées basées sur ce modèle.

