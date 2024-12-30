# Conclusie

## Basis opzet CNN:
### 53% accuracy

## Augmentatie + Geaugmenteerde data toegevoegd aan trainset: 
### 57% - Overfitting vanaf Epoch 3

## Augmentatie uitgebreid met Random brightness, contrast adjustments, Gaussian blur en Random cropping:
### 54% - Overfitting vanaf Epoch 5 (Model begon met 47.95% accuracy)
Epoch 5/15
Training Loss: 1.1549
Validation Loss: 1.2398
Validation Accuracy: 54.64%

## Regularisatie (Dropout + L2) + Extra layer:
### 59% - Overfitting vanaf Epoch 8 (Model begon met 39.37% accuracy)
Epoch 8/15
Training Loss: 1.1773
Validation Loss: 1.1023
Validation Accuracy: 58.87%

## SGD optimizer ipv. Adam:
### 56% - Overfitting vanaf Epoch 12 (Model begon met 36.32% accuracy)

## Extra layer + 2x augmented dataset bijgevoegd:
### 58-60% - Overfitting vanaf Epoch 7 (Model begon met 30% accuracy)

## 10x augmented dataset bijgevoegd om overfitting op te lossen "315799 rows":
### 59% - Overfitting vanaf Epoch 4 (Model begon met 46.06% accuracy) 
Epoch 4/15
Training Loss: 1.0932
Validation Loss: 1.0969
Validation Accuracy: 59.39%

