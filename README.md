# Roadmap

---

## Légende

✅ = complété

☑️ = en cours

🆘 = besoin d'aide

❌ = prévu

---

## Modèle de reconnaissance des insectes :

### Dataset

- [✅] Téléchargement depuis le repo iNaturalist 2021
- [✅] Préparation (gestion des performances avec `ijson`)
- [✅] Filtrage pour ne conserver que les insectes
- [✅] Upload sur Kaggle, solution gratuite similaire à Google Colab

### Modèle

- [✅] Vérification des données sur Kaggle
- [✅] Suppression des quelques fichiers corrompus par les interruptions pendant le transfert
- [✅] Préparation des datasets (train/train-mini/val/public-test)
- [✅] Extraction de la hiérarchie par ordre > famille > genre > espèce depuis les noms de dossiers
- [✅] Application de transformation pour augmenter artificiellement la taille du dataset train
- [✅] Construction d'un dictionnaire représentant la hiérarchie, avec les infos de localisation
- [✅] Apprentissage de la théorie sur le finetune du modèle MobileNet v3
- [☑️] Entrainement sur le dataset train-mini 
