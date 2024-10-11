# Neural-Network-Assignment-ICP_6

NAME: RAMA KRISHNA GANTA ID#: 700759560

VIDEO: https://drive.google.com/file/d/1ifAZQ1_aJd82PPU5eUFq6KGi5ZMfwkQg/view?usp=sharing

1. Add one more hidden layer to autoencoder

Solution: This autoencoder model extends the previous one by introducing a hidden layer of 64 dimensions between the encoded and decoded representations. The additional hidden layer allows the network to capture more complex features from the input data. Like the previous example, the Fashion MNIST dataset is used, normalized, and reshaped. The training process runs for five epochs, showing improvement in the reconstruction loss through each epoch, reflecting more effective learning due to the added complexity.

![image](https://github.com/user-attachments/assets/7041f8d9-df6d-49bc-9bfa-e397bdd6dcb6)

Output:

![image](https://github.com/user-attachments/assets/9ea1305f-ff1b-4b96-9d20-2adaca7912b2)

2. Do the prediction on the test data and then visualize one of the reconstructed version of that test data. Also, visualize the same test data before reconstruction using Matplotlib

Solution: After training an autoencoder with an additional hidden layer, the model's effectiveness is evaluated by reconstructing test images. The input data is reshaped, and predictions on test data produce reconstructed images. These results are visualized using Matplotlib, where both the original and reconstructed images are displayed side by side for comparison. This step helps in assessing how well the autoencoder captures and recreates the input data.

![image](https://github.com/user-attachments/assets/7964c4ca-e8f5-4c2e-bb45-fc838229cc2c)

Output:

![image](https://github.com/user-attachments/assets/459f394c-1fc6-40c1-8719-aa2e6d14b1fa)

3. Repeat the question 2 on the denoisening autoencoder

Solution: This denoising autoencoder is trained to remove noise from input images. After adding Gaussian noise to the Fashion MNIST dataset, the autoencoder learns to reconstruct clean images. The model uses a 32-dimensional encoding layer and is trained for 20 epochs. Predictions are made on noisy test images, and the results are visualized by comparing noisy inputs with their reconstructed outputs. This showcases the model's ability to denoise and improve image quality.

![image](https://github.com/user-attachments/assets/6f8b95d8-6a0a-421c-9cfe-e9d164c295ca)


Output:

![image](https://github.com/user-attachments/assets/18c4e4ea-8ada-404c-b8c4-617a9f4d581a)

4. plot loss and accuracy using the history object

Solution: The final model is a simple classification network trained on Fashion MNIST data to classify images into 10 categories. It uses a dense layer for encoding and a softmax layer for classification. The Adam optimizer and categorical cross-entropy loss function are employed. After training for 10 epochs, both the training/validation loss and accuracy are plotted using the history object. This provides a clear visualization of the model's performance improvement over epochs.

![image](https://github.com/user-attachments/assets/c488f1e5-28e7-4c4f-a479-90d9595b8a10)

Output:

![image](https://github.com/user-attachments/assets/4bd8cb00-c6de-4ef1-863e-52cdd9ed1466)




