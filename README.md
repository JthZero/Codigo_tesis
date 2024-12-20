# Pendulum Control with Quantum Deep Reinforcement Learning

Este repositorio implementa un modelo de Deep Reinforcement Learning (DRL) con redes neuronales cuánticas para controlar un péndulo invertido. Este proyecto forma parte de mi tesis de maestría, donde exploro cómo las redes neuronales cuánticas pueden aplicarse a problemas de control óptimo.
Codigo de tesis QRL

---

## Descripción

El péndulo invertido es un problema clásico en aprendizaje por refuerzo y control. En este proyecto:
- Se utiliza **Deep Q-Learning** para entrenar un modelo que aprenda a estabilizar el péndulo invertido.
- Se integran **redes neuronales cuánticas** como aproximadores de funciones de valor Q, demostrando su potencial en entornos simulados.

El entrenamiento se realiza en el entorno **CartPole-v1** de Gym, con un simulador cuántico proporcionado por **PennyLane**.

---

## Cómo usar

1. Asegúrate de tener instaladas las dependencias principales:
   - **Python 3.8+**
   - **Gym** (OpenAI Gym)
   - **PyTorch**
   - **PennyLane**
