## Changes in activation function

**Hidden Layers:** 28*28 - 64 - 128 - 254 - 10  
**Batch Size:** 64  
**Loss Function:** crossentropy  
**Optimizer:** Adam

| Activation Function         | Epoch | Training Accuracy | Testing Accuracy | Training Loss | Testing Loss |
|----------------------------|-------|-------------------|------------------|--------------|--------------|
| Sigmoid                    | 1     | 0.75              | 0.91             | 0.78         | 0.33         |
| Sigmoid                    | 2     | 0.93              | 0.94             | 0.26         | 0.21         |
| Sigmoid                    | 3     | 0.95              | 0.95             | 0.18         | 0.17         |
| Sigmoid                    | 4     | 0.96              | 0.96             | 0.14         | 0.14         |
| Sigmoid                    | 5     | 0.97              | 0.96             | 0.12         | 0.14         |
| Sigmoid                    | 6     | 0.97              | 0.96             | 0.10         | 0.13         |
| Sigmoid                    | 7     | 0.97              | 0.97             | 0.09         | 0.12         |
| Sigmoid                    | 8     | 0.98              | 0.97             | 0.08         | 0.11         |
| Sigmoid                    | 9     | 0.98              | 0.97             | 0.07         | 0.12         |
| Sigmoid                    | 10    | 0.98              | 0.97             | 0.06         | 0.11         |
| ReLU                       | 1     | 0.90              | 0.95             | 0.33         | 0.17         |
| ReLU                       | 2     | 0.96              | 0.96             | 0.13         | 0.12         |
| ReLU                       | 3     | 0.97              | 0.97             | 0.10         | 0.10         |
| ReLU                       | 4     | 0.98              | 0.96             | 0.08         | 0.12         |
| ReLU                       | 5     | 0.98              | 0.97             | 0.07         | 0.10         |
| ReLU                       | 6     | 0.98              | 0.97             | 0.05         | 0.09         |
| ReLU                       | 7     | 0.98              | 0.97             | 0.05         | 0.09         |
| ReLU                       | 8     | 0.99              | 0.98             | 0.04         | 0.09         |
| ReLU                       | 9     | 0.99              | 0.98             | 0.04         | 0.09         |
| ReLU                       | 10    | 0.99              | 0.97             | 0.03         | 0.10         |
| Tanh                       | 1     | 0.91              | 0.94             | 0.32         | 0.19         |
| Tanh                       | 2     | 0.95              | 0.96             | 0.15         | 0.13         |
| Tanh                       | 3     | 0.97              | 0.97             | 0.11         | 0.10         |
| Tanh                       | 4     | 0.97              | 0.97             | 0.08         | 0.10         |
| Tanh                       | 5     | 0.98              | 0.97             | 0.07         | 0.10         |
| Tanh                       | 6     | 0.98              | 0.97             | 0.06         | 0.10         |
| Tanh                       | 7     | 0.99              | 0.97             | 0.05         | 0.10         |
| Tanh                       | 8     | 0.99              | 0.97             | 0.04         | 0.10         |
| Tanh                       | 9     | 0.99              | 0.97             | 0.03         | 0.11         |
| Tanh                       | 10    | 0.99              | 0.97             | 0.03         | 0.10         |
| Leaky ReLU                 | 1     | 0.90              | 0.95             | 0.33         | 0.18         |
| Leaky ReLU                 | 2     | 0.96              | 0.96             | 0.14         | 0.12         |
| Leaky ReLU                 | 3     | 0.97              | 0.97             | 0.10         | 0.10         |
| Leaky ReLU                 | 4     | 0.98              | 0.97             | 0.08         | 0.10         |
| Leaky ReLU                 | 5     | 0.98              | 0.97             | 0.06         | 0.10         |
| Leaky ReLU                 | 6     | 0.98              | 0.97             | 0.05         | 0.09         |
| Leaky ReLU                 | 7     | 0.99              | 0.98             | 0.05         | 0.08         |
| Leaky ReLU                 | 8     | 0.99              | 0.98             | 0.04         | 0.09         |
| Leaky ReLU                 | 9     | 0.99              | 0.97             | 0.03         | 0.09         |
| Leaky ReLU                 | 10    | 0.99              | 0.97             | 0.03         | 0.11         |
| Exponential Linear Unit    | 1     | 0.23              | 0.33             | 2.28         | 2.25         |
| Exponential Linear Unit    | 2     | 0.43              | 0.56             | 2.22         | 2.17         |
| Exponential Linear Unit    | 3     | 0.58              | 0.61             | 2.10         | 2.01         |
| Exponential Linear Unit    | 4     | 0.59              | 0.60             | 1.88         | 1.71         |
| Exponential Linear Unit    | 5     | 0.62              | 0.67             | 1.55         | 1.37         |
| Exponential Linear Unit    | 6     | 0.69              | 0.73             | 1.24         | 1.09         |
| Exponential Linear Unit    | 7     | 0.75              | 0.78             | 1.01         | 0.90         |
| Exponential Linear Unit    | 8     | 0.79              | 0.81             | 0.84         | 0.76         |
| Exponential Linear Unit    | 9     | 0.81              | 0.83             | 0.73         | 0.67         |
| Exponential Linear Unit    | 10    | 0.83              | 0.84             | 0.65         | 0.60         |


## Training vs Testing Loss

For sigmoid activation function:

![image](https://github.com/user-attachments/assets/3765922f-81bf-4924-b7e2-950eee749a0d)

For ReLu activation function:

<img width="570" alt="image" src="https://github.com/user-attachments/assets/97895576-1caf-495b-b532-f24e169da9af" />


For Tanh activation function

![image](https://github.com/user-attachments/assets/64920ed0-c8cd-44fa-85a6-fa5d90e00b7c)

For Leaky ReLu activation function:

![image](https://github.com/user-attachments/assets/582117cf-2436-42ff-9bfc-e7ba0d4bd0c0)

For Exponential Linear Unit (ELU)

![image](https://github.com/user-attachments/assets/92193c41-97d8-4040-95bc-d30c4dad3499)






