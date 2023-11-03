# Minimal Torch Reimplementation of the DeepSurv Paper
DeepSurv: Personalized Treatment Recommender System Using A Cox Proportional Hazards Deep Neural Network
## Results
| Experiement                 | Reproduced C-idx | Paper's C-idx |
|-----------------------------|------------------|---------------|
| Linear data, Linear CPH     | 77.66% | 77.37% |
| Linear data, DeepSurv       | 77.11% | 77.40% |
| Non-linear data, Linear CPH | 48.70% | 50.70% |
| Non-linear data, Deepsurv   | 59.58% | 64.90% |