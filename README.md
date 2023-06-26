# Optical-Character-Recognition-
The project title is "Optical Character Recognition." The entire project was segmented into three main sections: Data Pre-processing, CNN Architecture, and Real-Time Implementation. The model achieved an impressive accuracy rate of 99.01%.

In the Data Pre-processing phase, various techniques were employed to prepare the input data for the OCR model. This involved steps such as image resizing, noise removal, and contrast enhancement to enhance the quality of the input images. These preprocessing techniques played a crucial role in improving the model's accuracy by ensuring that the input data was clean and well-suited for training.

The CNN Architecture section focused on designing the Convolutional Neural Network (CNN) model for character recognition. CNNs are well-suited for image classification tasks due to their ability to learn spatial hierarchies from input data. The architecture of the CNN model was carefully designed, considering factors such as the number of convolutional layers, pooling layers, and fully connected layers. The model was trained using a large dataset of labeled characters to learn the patterns and features necessary for accurate character recognition.

The Real-Time Implementation phase involved deploying the trained model to recognize characters in real-time scenarios. This could involve capturing images through a camera or processing scanned documents. The model was integrated with appropriate libraries and frameworks to enable real-time character recognition. The implementation was optimized to ensure efficient performance, enabling fast and accurate recognition of characters in real-world settings.

Overall, the project achieved remarkable success, attaining a high accuracy rate of 99.01%. This demonstrates the effectiveness of the applied techniques in accurately recognizing characters from various sources, paving the way for applications such as automated document processing, text extraction, and more.

I am attaching the link of the dataset used
https://www.kaggle.com/datasets/sachinpatel21/az-handwritten-alphabets-in-csv-format?resource=download

Steps to run the project:
1. Install dependencies: Install Python and run the command pip install keras numpy matplotlib opencv-python to install required packages.
2. Ensure file setup: Make sure data_preprocessing.py, CNN-Architecture.py, and implementation.py are in the same directory.
3. Preprocess data: Open data_preprocessing.py, modify the code to load and preprocess your dataset, and save the changes.
4. Define CNN architecture: Open CNN-Architecture.py, implement your CNN model's architecture, configure layers and activation functions, and save the changes.
5. Implement OCR: Open implementation.py, import necessary modules and code for data preprocessing and CNN architecture, implement training and evaluation code, and save the changes.
6. Open terminal: Open your terminal or command prompt.
7. Navigate to project directory: Use the cd command to navigate to the directory containing your project files.
8. Run the project: Execute python implementation.py in the terminal to run the project. Monitor the terminal for progress and output.

GUI Interface

<img width="1062" alt="Screenshot 2023-06-26 at 7 43 18 PM" src="https://github.com/ManalisJadhav/Optical-Character-Recognition-/assets/108777498/e486eccd-e315-4818-80b1-1273c76b87a1">

Character recognition

<img width="1062" alt="Screenshot 2023-06-25 at 11 24 56 PM" src="https://github.com/ManalisJadhav/Optical-Character-Recognition-/assets/108777498/d957105d-59d1-4d6e-be7a-a689cc26ab43">

Digit recognition

<img width="1062" alt="Screenshot 2023-06-25 at 11 27 26 PM" src="https://github.com/ManalisJadhav/Optical-Character-Recognition-/assets/108777498/9079c0eb-1d37-4c28-83cb-2248465775ae">






