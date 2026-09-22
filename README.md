# 📻 SinoSphère : "Le futur de la radio, aujourd'hui." — Analyse de Données & Stratégie Médias

> **Projet académique (L3 Économie-Gestion / Analyse de Données)** — Conception d'une stratégie de lancement pour une nouvelle radio généraliste nationale, appuyée sur une étude quantitative rigoureuse (ACP et Classification Ascendante Hiérarchique) sous **Stata** à partir d'une base de 1 660 observations.

---

## 🚀 Contexte et Objectifs du Projet
Dans le cadre du lancement de **SinoSphère** — une radio généraliste se positionnant comme la référence sur l'actualité internationale avec un focus stratégique sur la Chine —, ce projet d'analyse de données vise à convaincre des investisseurs institutionnels (banque et Arcom). 

L'approche repose sur l'exploitation statistique des préférences des auditeurs français afin de définir :
1. **La Ligne Éditoriale (Le Fond et la Forme) :** Regroupement des genres d'émissions et des thématiques d'actualité par Analyse en Composantes Principales (ACP).
2. **La Segmentation d'Audience (Le Ciblage) :** Identification des profils d'auditeurs types par Classification Ascendante Hiérarchique (CAH / Dendrogramme) pour isoler le cœur de cible prioritaire.

---

## 🛠️ Stack Technique & Méthodologie
* **Logiciel statistique :** IBM SPSS Statistics / **Stata**
* **Méthodes d'analyse multidimensionnelle :**
  * **Analyse en Composantes Principales (ACP) :** Réduction de dimension sur 16 variables d'émissions (`V12`) et 13 variables de thématiques (`V13`), rotation orthogonale *Varimax* et règle du coude pour la sélection des axes.
  * **Classification Ascendante Hiérarchique (CAH) :** Segmentation de l'échantillon d'auditeurs et visualisation par dendrogramme.
  * **Statistiques descriptives univariées et bivariées :** Analyse des moyennes, écarts-types, tris croisés et profils socio-démographiques (sexe, âge, CSP).

---

## 📂 Structure et Principaux Résultats

### 1. Le "Moodboard" de la Radio : ACP sur les Émissions (`V12`)
* **Réduction de dimension :** Sélection de 3 axes principaux expliquant **62,76%** de la variance totale des goûts en matière d'émissions.
* **Typologies de formats identifiées :**
  * *Confort et Amélioration du quotidien* (conseil aux auditeurs, jeux, cuisine, santé, musique).
  * *Reportages et Découvertes* (sciences, philosophie, grands reportages).
  * *Divertissement et Humour* (imitations, satires politiques, chroniques d'humoristes).
  * *Communication et Débat* (entretiens avec des personnalités, débats d'actualité).

### 2. Le Fond : ACP sur les Thématiques (`V13`)
* **Réduction de dimension :** Rétention de 2 axes principaux après rotation *Varimax* expliquant **68,24%** de la variance.
* **Enseignements stratégiques :** 
  * L'**actualité internationale** s'impose comme la thématique la plus porteuse de l'échantillon (note moyenne de **6,36/10**, avec l'écart-type le plus faible de 2,61), confirmant la pertinence du positionnement géostratégique de SinoSphère.

### 3. Ciblage et Personas : La Typologie d'Audience (CAH)
* **Segmentation :** Découpage de l'audience en groupes distincts.
* **Le Cœur de Cible (Persona Prioritaire - Groupe 2) :** 
  * Qualifié sous l'appellation *"Personnes qui aiment bien toutes les émissions"*.
  * Caractérisé par un profil mature (majoritairement âgé de 50 à 70 ans) disposant du temps nécessaire pour une écoute approfondie, et surreprésentant les **CSP+ (47,3%)**, un public particulièrement friand de décryptages géopolitiques et économiques approfondis.

---

## 👤 Auteur
* **Eric Lin** — Étudiant en Master 1 Data Sciences for Social Sciences (Université Paris Nanterre) & Licence en Économie-Gestion (Université Paris-Panthéon-Assas)
