Note : Students to please use Gmail ID for creation of Github account. Procedure for making a github account is mentioned **[[Here]](https://www.youtube.com/watch?v=Gn3w1UvTx0A)**
# 🤖 My Personal AI Object Detector

## 🌟 Project Overview

I used **Teachable Machine** to train a custom image classification model. The goal of this project was to teach a computer to distinguish between me and common desk objects like pens and bottles.

### 🚀 Try It Live!

You can test this model yourself using your own webcam. No setup required:
👉 **[[Here]]https://teachablemachine.withgoogle.com/models/HVA9zYsz7/**



## 📸 Proof of Concept

Here are screenshot of the AI identifying me with high confidence:

<img width="370" height="717" alt="image" src="https://github.com/user-attachments/assets/4be3b316-276f-4dde-8c8b-11f8af9f185f" />
<img width="369" height="710" alt="image" src="https://github.com/user-attachments/assets/4e76ed6a-6135-4ac0-b042-3d796be2287c" />
<img width="376" height="707" alt="image" src="https://github.com/user-attachments/assets/53935838-6677-4574-9262-8b25847d4080" />
<img width="373" height="708" alt="image" src="https://github.com/user-attachments/assets/c4dee500-f8a4-4a33-9121-410c6fa97360" />





## 🧠 How it Works

I trained the AI using four distinct classes:

1. **Usama:** Recognizes my face/presence in the frame.
2. **Bottle:** Identifies when a water bottle is held up.
3. **Pen:** Identifies when a pen is shown to the camera.
4. **Nothing:** A "background" class for when no objects are present.


## 🛠️ Tools Used

* **[Teachable Machine](https://teachablemachine.withgoogle.com/)** - Used for gathering data and training the neural network.
* **GitHub** - Used to host this documentation and share the project with the world.


## 📝 Reflection

Supervised Learning 
* This project uses Supervised Learning because I provided "labeled data" (the names for each category) to the model. The AI learned by associating the visual patterns from the webcam with the specific labels I created

*Want to play with Unsupervised learning? 
* Check here :  **[Unsupervised Learning](http://alekseynp.com/viz/k-means.html)** 

## Your Task 
 **"Mini-AI Portfolio Challenge."** 

## 📝 Assignment: The "Object Detective" Lab

### **Objective**

Create your own custom Image Classifier using **Teachable Machine** and publish it as a "digital poster" on **GitHub**.

### **Part 1: The Training (30 mins)**

1. **Pick a Theme:** Choose 3-4 objects or hand signals to teach the computer. (e.g., "Phone vs. Calculator," "Mask On vs. Mask Off," or "Rock, Paper, Scissors").
2. **Train the Model:** Use the Teachable Machine website to record your data and train your model.
3. **Test It:** Ensure your model is at least 90% confident when you show it the objects!

### **Part 2: The Logic (Critical Thinking)**

In your project notes, answer the following:

* **Why is this "Supervised Learning"?** (Hint: Did you provide the names for the objects?)

* **Edge Cases:** What happens if you hold two objects at once? How does the computer react?

### **Part 3: The Showcase (GitHub)**

1. **Create a Repository:** Name it `AI-Object-Detector`.
2. **The README:** Copy the template provided in class and fill in your details.
3. **Visuals:** Upload a screenshot of your "Preview" window showing the AI correctly identifying an object.
4. **Live Link:** Export your model and paste the shareable link in your README so the teacher (and your friends) can try it!


### **Grading Criteria (Keep it simple!)**

| Task | Points |
| --- | --- |
| **Functionality:** Does the share link work? | 40% |
| **Documentation:** Is the README filled out correctly? | 30% |
| **Understanding:** Did they correctly identify it as Supervised Learning? | 20% |
| **Presentation:** Is there a screenshot included? | 10% |



### Importatnt: 

If AI gets "confused" (e.g., it thinks a pen is a bottle), you need to **add more data.** This is a great way to explain that AI is only as good as the information we give it.



