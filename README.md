# Roadmap

---

## Légende

✅ = complété

☑️ = en cours

🆘 = besoin d'aide

❌ = prévu

---

## Modèle :

### Dataset @YoannDev90

- [✅] Téléchargement depuis le repo iNaturalist 2021
- [✅] Préparation (gestion des performances avec `ijson`)
- [✅] Filtrage pour ne conserver que les insectes
- [✅] Upload sur Kaggle, solution gratuite similaire à Google Colab

### Modèle @YoannDev90

- [✅] Vérification des données sur Kaggle
- [✅] Suppression des quelques fichiers corrompus par les interruptions pendant le transfert
- [✅] Préparation des datasets (train/train-mini/val/public-test)
- [✅] Extraction de la hiérarchie par ordre > famille > genre > espèce depuis les noms de dossiers
- [✅] Application de transformation pour augmenter artificiellement la taille du dataset train
- [✅] Construction d'un dictionnaire représentant la hiérarchie, avec les infos de localisation
- [✅] Apprentissage de la théorie sur le finetune du modèle MobileNet v3
- [☑️] Entrainement sur le dataset train-mini

## Base de données : @Elnix90 Lucky Nath

- [❌] Création d'une base de données basée sur le dataset
- [❌] Stocker des informations sur les espèces
- [❌] Enrichir la base de données avec des données externes, par exemple Wikipédia
- [❌] Stocker les données de localisation de chaque image du dataset

## Application Android : @Elnix90 Lucky

- [🆘] Création d'une appli avec Kivy
- [☑️] Création d'une appli de test en kotlin (plus facile) qui servira de solution de secours si nous n'arrivons pas à créer d'application android avec Kivy ou d'application pour ordinateur
- [❌] Gestion de la caméra
- [❌] Gestion de la galerie
- [❌] Export vers un ordinateur
- [❌] Transfert

## Application Desktop : Nath

- [❌] Création d'une appli avec CustomTkinter
- [❌] Création d'une API pour permettre la communication entre l'ordinateur et le téléphone
- [❌] Gérer le modèle (téléchargement/installation/utilisation avec `onnx-runtime`)
- [❌] Interface permettant une interaction avec le modèle de reconnaissance d'insectes
- [❌] Carte du monde permettant la visualisation graphique du dataset, avec un marqueur par image
- [❌] Biographie Wikipédia de l'espèce/famille
