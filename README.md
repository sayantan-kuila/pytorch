# Pytorch

This repository involves training an Artificial Neural Network (ANN) model on the MNIST dataset. The model’s performance is evaluated under different conditions, and the results are presented in five tables showing training accuracy, testing accuracy, training loss, and testing loss across multiple epochs.

## MNIST Dataset
Dataset download [Link](https://drive.google.com/file/d/1eEKzfmEu6WKdRlohBQiqi3PhW_uIVJVP/view).

### Dataset Statistics 
Color: Grey-scale
Sample Size: 28x28

### The Number of Samples per Category for MNIST

| CATEGORY          | 0     | 1     | 2     | 3     | 4     | 5     | 6     | 7     | 8     | 9     | TOTAL  |
|------------------|------|------|------|------|------|------|------|------|------|------|--------|
| Training Samples | 5,923 | 6,742 | 5,958 | 6,131 | 5,842 | 5,421 | 5,918 | 6,265 | 5,851 | 5,949 | 60,000 |
| Testing Samples  | 980   | 1,135 | 1,032 | 1,010 | 982   | 892   | 958   | 1,028 | 974   | 1,009 | 10,000  |

### Samples

![image](https://github.com/user-attachments/assets/c51ebd68-f889-4de5-a3b4-dc055e242eeb)

## Observation

### Change in batch size

Hidden Layers: 28*28 - 64 - 128 - 254 - 10
Activation Function: ReLu
Loss Function: crossentropy
Optimizer: Adam

| Batch Size | Epoch | Training Accuracy | Testing Accuracy | Training Loss | Testing Loss |
|------------|-------|-------------------|------------------|---------------|--------------|
| 2          | 1     | 0.92              | 0.95             | 0.27          | 0.17         |
| 2          | 2     | 0.96              | 0.96             | 0.16          | 0.16         |
| 2          | 3     | 0.96              | 0.94             | 0.15          | 0.24         |
| 2          | 4     | 0.97              | 0.97             | 0.13          | 0.16         |
| 2          | 5     | 0.97              | 0.97             | 0.12          | 0.15         |
| 2          | 6     | 0.97              | 0.96             | 0.12          | 0.21         |
| 2          | 7     | 0.97              | 0.96             | 0.11          | 0.24         |
| 2          | 8     | 0.97              | 0.96             | 0.11          | 0.20         |
| 2          | 9     | 0.98              | 0.97             | 0.10          | 0.15         |
| 2          | 10    | 0.98              | 0.97             | 0.09          | 0.17         |
| 8          | 1     | 0.93              | 0.96             | 0.24          | 0.12         |
| 8          | 2     | 0.96              | 0.97             | 0.12          | 0.11         |
| 8          | 3     | 0.97              | 0.97             | 0.09          | 0.11         |
| 8          | 4     | 0.98              | 0.97             | 0.08          | 0.10         |
| 8          | 5     | 0.98              | 0.97             | 0.07          | 0.12         |
| 8          | 6     | 0.98              | 0.97             | 0.06          | 0.11         |
| 8          | 7     | 0.98              | 0.97             | 0.06          | 0.13         |
| 8          | 8     | 0.98              | 0.98             | 0.05          | 0.13         |
| 8          | 9     | 0.99              | 0.97             | 0.05          | 0.14         |
| 8          | 10    | 0.99              | 0.97             | 0.05          | 0.13         |
| 16         | 1     | 0.92              | 0.96             | 0.25          | 0.14         |
| 16         | 2     | 0.96              | 0.96             | 0.12          | 0.12         |
| 16         | 3     | 0.97              | 0.97             | 0.09          | 0.10         |
| 16         | 4     | 0.98              | 0.97             | 0.07          | 0.10         |
| 16         | 5     | 0.98              | 0.97             | 0.06          | 0.09         |
| 16         | 6     | 0.98              | 0.98             | 0.05          | 0.09         |
| 16         | 7     | 0.99              | 0.97             | 0.05          | 0.09         |
| 16         | 8     | 0.99              | 0.98             | 0.04          | 0.09         |
| 16         | 9     | 0.99              | 0.97             | 0.04          | 0.12         |
| 16         | 10    | 0.99              | 0.98             | 0.03          | 0.10         |
| 64         | 1     | 0.90              | 0.95             | 0.34          | 0.17         |
| 64         | 2     | 0.96              | 0.96             | 0.14          | 0.13         |
| 64         | 3     | 0.97              | 0.96             | 0.10          | 0.11         |
| 64         | 4     | 0.97              | 0.97             | 0.08          | 0.10         |
| 64         | 5     | 0.98              | 0.97             | 0.07          | 0.09         |
| 64         | 6     | 0.98              | 0.97             | 0.06          | 0.09         |
| 64         | 7     | 0.98              | 0.97             | 0.05          | 0.09         |
| 64         | 8     | 0.99              | 0.97             | 0.04          | 0.09         |
| 64         | 9     | 0.99              | 0.98             | 0.04          | 0.08         |
| 64         | 10    | 0.99              | 0.97             | 0.03          | 0.10         |



