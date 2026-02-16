#Laboratory-Work-2-A-Plant-Species-Image-Classification

##[Link for Google Drive] https://drive.google.com/drive/folders/1a_Z3dbVImU38eqXBfiGQDC6wTQiuwxrp?usp=sharing

##1. How did the number of images per class affect your model’s accuracy?
# - The number of images per class significantly affects model accuracy. More images provide diverse examples, helping the model learn better patterns and generalize effectively. Fewer images limit learning and may cause overfitting. If classes are imbalanced, the model becomes biased toward majority classes, reducing overall performance and prediction reliability.

##2. Which plant species were most commonly misclassified and why?
# - The plant species most commonly misclassified were those with similar leaf shapes, colors, or textures, making them visually difficult to distinguish. Species with overlapping features—such as similar vein patterns or leaf sizes—confused the model. Limited training images and varying lighting conditions also contributed to misclassification by reducing feature clarity.

##3. How did changing the epochs, batch size, or learning rate affect the training results?
# - Changing the epochs, batch size, and learning rate directly affected training performance. Increasing epochs improved accuracy at first but caused overfitting when too high. Smaller batch sizes made learning more stable but slower. A high learning rate caused unstable training, while a very low rate slowed convergence and learning progress.

##4. What challenges did you encounter during dataset collection and labeling?
# - Challenges during dataset collection and labeling included limited images for some plant species, inconsistent lighting and background conditions, and difficulty ensuring balanced classes. Labeling was time-consuming and required careful verification to avoid errors. Similar-looking species also made accurate labeling difficult, increasing the risk of misclassification during training.

##5. If you were to improve your model, what specific changes would you make and why?
# - To improve the model, I would collect more balanced images per class to reduce bias and improve generalization. I would apply data augmentation to increase diversity and prevent overfitting. Fine-tuning hyperparameters, using transfer learning, and adding regularization techniques would also enhance accuracy and overall performance.
