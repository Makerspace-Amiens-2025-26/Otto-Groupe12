---
layout: default
nav_order: 5
title: Conception et prototypage
---


# 🔧 Conception & Prototypage

## Modification apportée au robot

### Ajout d'un étage entre la tête et le corps

**Objectif :** Personnaliser notre robot Otto-MKS pour le distinguer du modèle original, lui donner une apparence plus imposante et augmenter sa hauteur sans compromettre ses fonctionnalités.

#### 🎯 Objectifs détaillés
- Augmenter la hauteur totale du robot
- Créer une silhouette plus haute et plus massive
- Préserver la stabilité mécanique
- Permettre le passage des câbles électroniques
- Ne pas gêner les mouvements des servomoteurs

#### 💡 Solution retenue

Conception d'une **pièce intermédiaire** s'insérant entre la tête et le corps. Cette pièce a été pensée pour s'adapter parfaitement à la structure existante tout en offrant l'espace nécessaire aux composants.

| Contrainte | Solution |
|------------|----------|
| Stabilité | Centre de gravité maintenu bas |
| Passage des câbles | Canaux intégrés dans la pièce |
| Compatibilité | Fixations identiques au modèle original |

---

## 🧩 Modélisation 3D sur Onshape

L'ensemble des pièces du robot a été modélisé ou modifié sur **Onshape**.

### Pièces originales d'Otto-MKS

- Corps principal
- Tête avec emplacement pour capteur ultrason
- Pieds et jambes


---

## 📐 Visualisation 3D

<iframe height="500" width="100%" src="https://modelembedder.net/embed?did=9c8be9d5948860dbdf8c5030&wvm=v&wvmid=5700a20b0c46ffa8c7e0796d&eid=4f1193e47d2309dbc86d44f2&elementType=ASSEMBLY" frameborder="0"></iframe>

{: .warning }
> Si le modèle 3D ne s'affiche pas, cliquez sur le bouton ci-dessous pour accéder directement à Onshape.

[🔗 Ouvrir sur Onshape](https://cad.onshape.com/documents/9c8be9d5948860dbdf8c5030/w/5700a20b0c46ffa8c7e0796d/e/4f1193e47d2309dbc86d44f2){: .btn .btn-primary }

---

## 🖨️ Prototypage et intégration

### Étapes d'impression 3D

La pièce intermédiaire a été imprimée en **PLA** avant d'être intégrée au robot.

| Paramètre | Valeur |
|-----------|--------|
| Matériau | PLA (gris) |
| Hauteur de couche | 0.2 mm |
| Remplissage | 20% |
| Supports | Non requis |

### 🔧 Assemblage

1. Démontage de la tête du robot original
2. Insertion de l'étage imprimé entre le corps et la tête
3. Passage des câbles (alimentation, capteur ultrason) à l'intérieur de l'étage
4. Remontage de la tete sur l'étage

---

## 📸 Résultat final

![Robot Otto-MKS modifié](assets/images/otto-final.jpg)

{: .note }
> *Photo du robot assemblé avec l'étage supplémentaire. Placez votre image dans `assets/images/otto-final.jpg`*

---

## 📎 Annexes techniques

| Lien | Description |
|------|-------------|
| [Onshape - Pièces originales](https://cad.onshape.com/...) | Dossier complet des pièces de base |
| [Onshape - Pièce modifiée](https://cad.onshape.com/...) | Fichier STL de l'étage intermédiaire |
| [Vidéo d'assemblage](https://youtu.be/8-qTWAUJMaU) | Tutoriel pas-à-pas |

---

## 🛠️ Matériel utilisé

| Outil | Modèle |
|-------|--------|
| Imprimante 3D | Bambu Lab |
| Filament | PLA |
| Logiciel CAO | Onshape |


---

*Conception réalisée par Rozié Archibald & Hanquer Nohem  – Projet 1ère année*
