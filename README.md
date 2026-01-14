# Deep Learning Uni Project

Dieses Repository enthält Übungen und Experimente aus dem Bereich **Deep Learning mit TensorFlow/Keras**.  
Der Fokus liegt auf Modelltraining, Evaluation (Loss/Accuracy), Normalisierung sowie Reproduzierbarkeit der Ergebnisse.

---

## 📦 Voraussetzungen

- **Python:** 3.9 – 3.12 (TensorFlow-Kompatibilität)
- **Git**
- **Conda / Miniforge (empfohlen)** https://github.com/conda-forge/miniforge



---

## 🧪 Jupyter Notebooks ohne Outputs (nbstripout)

Um Notebook-Outputs repositoryweit zu entfernen (saubere Commits):

```bash
nbstripout --install --attributes .gitattributes
git add .gitattributes
git commit -m "Add nbstripout configuration"
git push
```

## 🐍 Miniforge / Conda / Mamba – Basics

### Environment erstellen
Ein neues Conda-Environment mit einer bestimmten Python-Version:

```bash
conda create -n deeplearning-uni python=3.12
conda activate deeplearning-uni
```
Mein Env nutzen:
```bash
conda env create -f deeplearning-uni-env.yaml
conda activate deeplearning-uni
```
oder für schnelleres erstellen Mamba nutzen:
```bash
conda install mamba -n base -c conda-forge
mamba env create -f deeplearning-uni-env.yaml
```
---
## Weiterführende Grundlagen

### Introduction
https://developers.google.com/machine-learning/intro-to-ml?hl=en

### Googles Crash-Course:
https://developers.google.com/machine-learning/crash-course/linear-regression?hl=en

### Some Tensorflow Tutorials
https://www.tensorflow.org/tutorials/keras/regression
https://www.tensorflow.org/tutorials/keras/classification
https://www.tensorflow.org/tutorials/images/cnn
