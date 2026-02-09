# Neural Network Classification with PyTorch

Este repositorio forma parte del proyecto del curso de Deep Learning que cursé en la SIAFI, desarrollado dentro del Curso Propedéutico.

Este proyecto tiene como objetivo diseñar, entrenar y evaluar un modelo de red neuronal utilizando PyTorch
para una tarea de clasificación supervisada.

Se sigue un flujo de trabajo típico de Ciencia de Datos que incluye:
- Exploración del dataset
- Preprocesamiento de los datos
- Construcción del modelo
- Entrenamiento y validación
- Evaluación del desempeño
- Ajuste de hiperparámetros

El proyecto prioriza no solo la precisión del modelo, sino también la comprensión del comportamiento de los datos
y de la red neuronal.

## **Proyecto — Clasificación con Redes Neuronales (PyTorch)**
[`PROYECTO.ipynb`](PROYECTO.ipynb)  
Desarrollo completo de un modelo de clasificación supervisada utilizando PyTorch y una red neuronal multicapa (MLP).

> **Project description**  
> It's time to show off your skills! Build, train, and evaluate a neural network model using PyTorch on a dataset of your choice.  
> You can use any dataset available online or one from your previous assignments.  
>  
> Make sure to preprocess the data appropriately, define a suitable architecture, and implement training and evaluation loops.  
> Remember to document your code and explain your choices.  
>  
> You ought to follow a Data Science workflow, check the suggested workflow in the *Introduction to Data Science* course or develop your own.  
> Recommended minimal steps include data exploration, preprocessing, model building, training, evaluation, and fine-tuning.  
>  
> Submit your code along with a brief report summarizing your approach and findings (the format is free).  
> Remember that a good Data Science project is not just about getting high accuracy, but also about understanding the data and the model's behavior.  
>  
> Make sure to highlight any challenges you faced and how you overcame them.  
> Pinpoint areas for future improvement or exploration.  
> Use clear visualizations to support your analysis where appropriate.  
> And remember to make communications clear and concise.  
>  
> If you need inspiration, you can use the following idea:  
>  
> Build and train a classification MLP on the CoverType dataset:  
>  
> 1. Load the dataset using `sklearn.datasets.fetch_covtype()` and create a custom PyTorch `Dataset` for this data.  
> 2. Create data loaders for training, validation, and testing.  
> 3. Build a custom MLP module to tackle this classification task.  
> 4. Train this model on the GPU, and try to reach 93% accuracy on the test set.  
>    For this, you will likely have to perform hyperparameter search to find the right number of layers and neurons per layer,  
>    a good learning rate and batch size, and so on. You can optionally use Optuna for this.
