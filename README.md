# CAP6415 F25 – Measuring Effects of Training Set Compression on Task Performance

## 📘 Abstract
This project investigates how compressing the size of a training dataset affects the performance of a Convolutional Neural Network (CNN) on an image classification task. The main goal is to measure how reducing training samples impacts accuracy, loss behavior, generalization, and learned feature representations. A series of controlled experiments were conducted where the dataset was systematically compressed, and the resulting model performance metrics were evaluated and compared. The full implementation—including preprocessing, training, evaluation, and visualizations—is contained in the notebook: **computer vision final project.ipynb**.

---

## 🧠 Problem Description
Deep learning models, especially CNNs, typically rely on large, labeled datasets to achieve good performance. However, in real-world scenarios, storage, memory, bandwidth, and labeling constraints may force practitioners to train on compressed or reduced datasets.

This project focuses on answering:
- How much does dataset compression degrade model performance?
- What is the relationship between dataset size and accuracy/generalization?
- How do internal feature maps differ when training on fewer samples?
- Is there a compression threshold where performance drops sharply?

The experiments provide insights into the trade-off between dataset size and task performance in computer vision workflows.

---

## 🛠 Frameworks & Tools Used
The implementation relies on the following frameworks:

- **TensorFlow / Keras** – CNN model construction, training, and evaluation  
- **NumPy & Pandas** – Data handling and preprocessing  
- **Matplotlib** – Visualization of accuracy/loss curves and feature maps  
- **Scikit-Learn** – Train/validation/test splitting and performance metrics  
- **OpenCV (optional)** – Additional image preprocessing  

All experiments were executed in:computer vision final project.ipynb


---

## 🧩 Method Summary
1. Loaded and preprocessed the dataset.  
2. Created compressed versions of the dataset (e.g., 100%, 50%, 25%, 10%).  
3. Trained identical CNN architectures on each compressed dataset split.  
4. Evaluated models using accuracy, loss, confusion matrices, and sample predictions.  
5. Visualized early-layer activation maps to analyze how compression affects learned features.  
6. Compared performance degradation across compression levels.

---

## 📊 Results Summary
- Compression consistently reduces test accuracy and increases loss.  
- Smaller datasets produce noisier gradients and slower convergence.  
- Feature maps become less distinct and activate more randomly at higher compression levels.  
- There is a noticeable “performance cliff” once compression becomes too aggressive (e.g., <10%).  

Full plots and numerical results are available in the notebook.

---

## 📝 Weekly Logs
Progress documentation is provided through:

-wee1.txt (Week 1)

-Week2.txt (Week 2)

-Week3.txt (Week 3)

-week4.txt (Week 4)

-week5.txt (Week 5)


---

## 📚 Attribution & References
This project uses publicly available libraries and is inspired by standard CNN classification workflows.

**Framework Documentation:**
- TensorFlow/Keras: https://www.tensorflow.org/
- Scikit-Learn: https://scikit-learn.org/
- OpenCV: https://opencv.org/

**Conceptual References:**
- LeCun, Y., Bengio, Y., & Hinton, G. *Deep Learning*. Nature, 2015.  
- Krizhevsky, A., Sutskever, I., & Hinton, G. E. *ImageNet Classification with Deep Convolutional Neural Networks*, 2012.

**Code Attribution:**
- CNN architecture and training loops adapted from official TensorFlow/Keras examples.  
- Feature visualization techniques based on Keras “Visualizing intermediate activations” guide.

All external code has been properly cited and modified as needed.

---







