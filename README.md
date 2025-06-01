Project Highlight: Breast Cancer Color Dataset Classification Using Deep Learning

I recently worked on a breast cancer classification project leveraging a colorized medical imaging dataset. The goal was to build an accurate model to classify breast tumor images into (0) and (1) categories, using deep learning techniques. 

🔍 Dataset
2,000 color images labeled into two categories: benign (0) and malignant (1), balanced equally.
Images preprocessed and loaded into a Pandas DataFrame for efficient management and analysis.

📊 Exploratory Data Analysis (EDA)
Visualized class distribution using countplots and pie charts to understand dataset balance.
Displayed sample images from each class to get a visual sense of the data.

⚙️ Modeling
Designed a custom convolutional neural network (CNN) with a novel Continuous Convolution Layer to better capture spatial patterns and features in images.
Implemented a Variational Loss function combining binary cross-entropy with smoothness regularization to improve generalization and stability of learned kernels.
Trained the model with TensorFlow’s Keras API, using image data generators for efficient batch processing and augmentation.

📈 Training and Validation
Used an 80-10-10 train-validation-test split with stratification to preserve class balance.
Achieved promising classification accuracy, demonstrating the potential of combining continuous kernel learning with variational regularization for medical image analysis.

I’m excited about how AI can support early and accurate cancer diagnosis, and I look forward to applying these skills to more healthcare challenges!
