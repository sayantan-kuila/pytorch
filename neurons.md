## Changes in the number of neurons in a hidden layer

**Activation Function:** ReLu  
**Loss Function:** crossentropy  
**Optimizer:** Adam  
**Batch size:** 64

| No. of neurons in Hidden Layer | Epoch | Training Accuracy | Testing Accuracy | Training Loss | Testing Loss |
|--------------------------------|-------|-------------------|------------------|--------------|--------------|
| 28*28-8-16-32-10              | 1     | 0.75              | 0.87             | 0.76         | 0.43         |
| 28*28-8-16-32-10              | 2     | 0.88              | 0.90             | 0.39         | 0.34         |
| 28*28-8-16-32-10              | 3     | 0.90              | 0.91             | 0.33         | 0.31         |
| 28*28-8-16-32-10              | 4     | 0.91              | 0.92             | 0.30         | 0.29         |
| 28*28-8-16-32-10              | 5     | 0.92              | 0.92             | 0.28         | 0.28         |
| 28*28-8-16-32-10              | 6     | 0.92              | 0.92             | 0.27         | 0.27         |
| 28*28-8-16-32-10              | 7     | 0.92              | 0.92             | 0.27         | 0.27         |
| 28*28-8-16-32-10              | 8     | 0.92              | 0.92             | 0.26         | 0.27         |
| 28*28-8-16-32-10              | 9     | 0.92              | 0.92             | 0.26         | 0.27         |
| 28*28-8-16-32-10              | 10    | 0.92              | 0.92             | 0.25         | 0.26         |
| 28*28-64-128-256-10           | 1     | 0.82              | 0.90             | 0.72         | 0.33         |
| 28*28-64-128-256-10           | 2     | 0.91              | 0.92             | 0.31         | 0.27         |
| 28*28-64-128-256-10           | 3     | 0.93              | 0.93             | 0.26         | 0.24         |
| 28*28-64-128-256-10           | 4     | 0.93              | 0.94             | 0.23         | 0.22         |
| 28*28-64-128-256-10           | 5     | 0.94              | 0.94             | 0.21         | 0.20         |
| 28*28-64-128-256-10           | 6     | 0.95              | 0.94             | 0.19         | 0.18         |
| 28*28-64-128-256-10           | 7     | 0.95              | 0.95             | 0.17         | 0.17         |
| 28*28-64-128-256-10           | 8     | 0.95              | 0.95             | 0.16         | 0.16         |
| 28*28-64-128-256-10           | 9     | 0.96              | 0.96             | 0.14         | 0.15         |
| 28*28-64-128-256-10           | 10    | 0.96              | 0.96             | 0.13         | 0.14         |
| 28*28-256-512-1024-10         | 1     | 0.86              | 0.93             | 0.50         | 0.24         |
| 28*28-256-512-1024-10         | 2     | 0.94              | 0.95             | 0.21         | 0.18         |
| 28*28-256-512-1024-10         | 3     | 0.95              | 0.96             | 0.15         | 0.13         |
| 28*28-256-512-1024-10         | 4     | 0.96              | 0.96             | 0.12         | 0.12         |
| 28*28-256-512-1024-10         | 5     | 0.97              | 0.97             | 0.09         | 0.11         |
| 28*28-256-512-1024-10         | 6     | 0.98              | 0.97             | 0.08         | 0.09         |
| 28*28-256-512-1024-10         | 7     | 0.98              | 0.97             | 0.06         | 0.08         |
| 28*28-256-512-1024-10         | 8     | 0.98              | 0.97             | 0.05         | 0.08         |
| 28*28-256-512-1024-10         | 9     | 0.99              | 0.98             | 0.05         | 0.07         |
| 28*28-256-512-1024-10         | 10    | 0.99              | 0.98             | 0.04         | 0.08         |
| 28*28-2560-3480-5120-10       | 1     | 0.93              | 0.96             | 0.23         | 0.12         |
| 28*28-2560-3480-5120-10       | 2     | 0.97              | 0.97             | 0.11         | 0.11         |
| 28*28-2560-3480-5120-10       | 3     | 0.98              | 0.97             | 0.07         | 0.09         |
| 28*28-2560-3480-5120-10       | 4     | 0.98              | 0.98             | 0.05         | 0.07         |
| 28*28-2560-3480-5120-10       | 5     | 0.99              | 0.98             | 0.05         | 0.09         |
| 28*28-2560-3480-5120-10       | 6     | 0.99              | 0.97             | 0.04         | 0.10         |
| 28*28-2560-3480-5120-10       | 7     | 0.99              | 0.98             | 0.04         | 0.08         |
| 28*28-2560-3480-5120-10       | 8     | 0.99              | 0.98             | 0.03         | 0.08         |
| 28*28-2560-3480-5120-10       | 9     | 0.99              | 0.98             | 0.03         | 0.09         |
| 28*28-2560-3480-5120-10       | 10    | 0.99              | 0.98             | 0.03         | 0.10         |


## Training vs Testing Loss

No. of neurons in Hidden Layer = 28*28-8-16-32-10

![image](https://github.com/user-attachments/assets/74825692-1a41-4acc-9813-2280977b9391)

No. of neurons in Hidden Layer = 28*28-64-128-256-10

![image](https://github.com/user-attachments/assets/a226805d-9c71-49d2-ad3f-dd6127d05308)

No. of neurons in Hidden Layer = 28*28-256-512-1024-10

![image](https://github.com/user-attachments/assets/4fceb597-4bf2-42b6-92a8-1310ab4d11ba)

No. of neurons in Hidden Layer = 28*28-2560-3480-5120-10

![image](https://github.com/user-attachments/assets/6e7c7714-ac01-43c6-9229-709261eddd5f)


