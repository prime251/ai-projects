#  Teachable Machine Practice Log

This project shows three AI experiments I did using **Google Teachable Machine**.  
I explored how AI can learn to classify images, sounds, and body poses using simple training examples.

---

##  1. Dog vs Cat Image Classifier

- **Tool**: Teachable Machine (Image Project)  
- **Training Data**:  
  - 30 images of dogs  
  - 30 images of cats  
- **Test Result**:  
  - The model correctly identified a new dog photo that wasn't in the training data.
- **What I learned**:  
  - AI doesn’t just memorize—it learns patterns to generalize new data.
- **Screenshot**:  
![Dog vs Cat Screenshot](./dog vs cat.png)

---

##  2. Audio Classifier – Yes vs No / Mom vs Me

- **Tool**: Teachable Machine (Audio Project)  
- **Experiment 1**:  
  - Trained with 10 samples of "Yes" and 10 samples of "No"  
  - The model performed well and responded accurately.
- **Experiment 2**:  
  - Tried to classify Mom's voice vs My voice using the same words.  
  - The result was less accurate and inconsistent.
- **What I learned**:  
  - Audio classification needs more data and clearer differences to work well.

---

##  3. Pose Classifier – Left / Right / Both Hands Up

- **Tool**: Teachable Machine (Pose Project)  
- **Classes**:
  - Class 1: Left hand up  
  - Class 2: Right hand up  
  - Class 3: Both hands up  
- **Result**:  
  - Two-class models (left vs right) worked fine.  
  - Adding a third class (both hands up) caused more confusion and lower accuracy.
- **What I learned**:  
  - Pose classification is impressive but needs distinct and consistent movements to stay accurate.

---

##  What I Found Interesting

- The image model could recognize **new images** not used during training.  
- The voice model was **harder to train** and needs more clarity and variety.  
- The pose model was **fun to test**, and even small differences in movement mattered.  
- I realized that good training data is the key to good AI predictions.

---

##  Tools Used

- [Google Teachable Machine](https://teachablemachine.withgoogle.com/)
- Laptop webcam and built-in microphone
- Sample images from Kaggle (Dog vs Cat dataset)

---

##  Folder Structure (Example)

