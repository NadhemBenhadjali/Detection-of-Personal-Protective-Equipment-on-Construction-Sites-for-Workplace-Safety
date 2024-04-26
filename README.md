# Detection-of-Personal-Protective-Equipment-on-Construction-Sites-for-Workplace-Safety
https://www.kaggle.com/c/gods30/
Goal: Your mission will be to develop an automatic detection system for PPE in construction site images, using artificial intelligence to enhance worker safety.
Here's an updated README file that reflects the specific title and details of the Kaggle competition on the detection of personal protective equipment (PPE) on construction sites for workplace safety:

---

## Project Title: Detection of PPE on Construction Sites for Workplace Safety - Kaggle Competition

### Overview
This project is an entry in the Kaggle competition "Detection of Personal Protective Equipment on Construction Sites for Workplace Safety." The challenge focuses on developing machine learning models that can effectively detect whether construction workers are wearing the required personal protective equipment (PPE) such as helmets, vests, and safety boots.

### Technical Approach
- **Data Preprocessing:** The dataset, characterized by an imbalance in the representation of different classes (PPE types), was managed using techniques like data augmentation and modifying class weights to ensure equitable learning across all classes.
- **Model Architecture:** We chose TensorFlow as our deep learning framework, implementing a transfer learning strategy with the ResNet50 architecture. This model, pre-trained on the ImageNet dataset, is fine-tuned to tailor its capabilities to PPE detection.
- **Training:** The model was trained by fine-tuning several layers of ResNet50 while keeping the initial layers unchanged to preserve the generic features learned from ImageNet. This approach was essential to adapt the neural network to the specific features of PPE in construction settings.
- **Evaluation:** The model's performance was evaluated on its accuracy and F1-score, critical metrics considering the unbalanced nature of the training data.
- **final score** :
  first approach (tf):
![image](https://github.com/NadhemBenhadjali/Detection-of-Personal-Protective-Equipment-on-Construction-Sites-for-Workplace-Safety/assets/153218589/b0ab88c8-8f94-4fdc-9f56-584289168f61)
 second approach (pytorch):
![image](https://github.com/NadhemBenhadjali/Detection-of-Personal-Protective-Equipment-on-Construction-Sites-for-Workplace-Safety-/assets/153218589/eede8d77-5b7f-427f-9b7e-0dd0035c44d2)

