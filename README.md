# Handwritten Vietnamese Recognition
> Failure is only the opportunity to begin again. Only this time, more wisely. Good times become good memories, but bad times become good lessons. - Uncle Iroh
## Motivation
Not many people know that my name is not *Thu*, but it's actually *Thư*, and the ways these two words are pronounced are also different. Vietnamese written alphabet is a Latin-based script but it has various dialectical marks that make Vietnamese a very nuanced language. My motivation for pursuing this project is: 1) I love my mother tongue language because the nuances make it so special and beautiful, and 2) I believe in the meaningful applications of handwriting recognition in many settings, such as education, clinical settings, banking, etc.
## Pipeline 1: Classify variations of the letter A - A, Ă, Â
### Data Acquisition
The dataset consists of 300 samples of handwritten Vietnamese letters which belong to 3 classes: a, ă, â. Each class consists of 100 samples. I wrote all these letters on regular A4 papers and used my phone to scan them through CamScanner. The original pictures were cropped into squared frames.
### Data Preprocessing
1. Resizing
2. Binarization
3. Normalization
### Feature Extraction
1. Pixel Features
### Model Selection
1. K-Nearest Neighbor Classifier
2. Naive Bayes
3. Multinomial Logistic Regression
4. Decision Tree
5. Random Forest
6. Support Vector Machines
7. Neural Networks
### Model Performance
1. Confusion Matrix
2. ROC-AUC
### Discussion & Limitations

