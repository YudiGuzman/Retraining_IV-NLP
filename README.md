# Retraining_IV-NLP
It shows the retraining process of the best model using fixed seeds. The notebook is associated with the analysis and evaluation of the performance of the best model selected in the original training phase. The objective of this retraining phase is to generate the predicted data set for subsequent causal evaluation. This repository contains the notebooks used for the retraining process of the three best selected models, with the aim of evaluating their behavior from a causal inference approach.

## Contenido
- Notebook de rentrenamiento con semillas fijas
- Configuración de entorno (semillas, librerías, etc.)

## Requisitos
- Python 3.x
- TensorFlow, NumPy, pandas, scikit-learn

## Semillas utilizadas
- random.seed(42)
- np.random.seed(42)
- tf.random.set_seed(42)

