# 🩺 Predicting Medical Insurance Costs with AI 🤖  

Ever wonder how insurance companies figure out what you'll pay?  

This project is all about using a special kind of AI called an **Artificial Neural Network (ANN)** to predict medical insurance charges.  
It's a great way to see how deep learning can be used to solve real-world problems!  



## 🚀 What's Inside?  
- **Mini_Project_DL_Regression.ipynb** → Main Jupyter Notebook with all the code. It takes you on a journey from exploring the data to building and testing the AI model.  
- **README.md** → You’re reading it right now! Quick rundown of the project.  



## 📊 The Data  
We’re working with a dataset that has some neat info about people, like:  

- **age** → How old they are  
- **sex** → Male or Female  
- **bmi** → Body Mass Index  
- **children** → How many kids are on their plan  
- **smoker** → Do they smoke? (Spoiler alert: this one’s a big deal!) 🚬  
- **region** → Which part of the US they live in  
- **charges** → The medical costs we’re trying to predict  



## 🕵️‍♂️ Finding Insights (EDA)  
Before we built our AI, we played detective with the data. Here’s what we found:  

- Found and removed a **duplicate row** in the dataset.  
- **Smokers** have **much, much higher** medical charges.  
- People with **higher BMI** and **older age** also tend to have higher costs.  
- Folks in the **Southeast region** have the **highest average charges**.  



## 🛠️ Tools and Technologies  
This project was built using the following Python libraries:  

- **Pandas & NumPy** → Data cleaning and manipulation  
- **Scikit-learn** → Preprocessing and preparing the dataset  
- **Matplotlib** → Visualization and data insights  
- **TensorFlow & Keras** → Building and training the neural networks  



## 🧠 Building Our AI Brain  
We tried out a couple of different AI models:  

### 🔹 The "Starter" Model  
- A simple ANN with minimal layers.  
- **Performance:** Very poor, with a negative R² score 🙈  

### 🔹 The "Smarter" Model  
- Added **Dropout layers** to prevent overfitting.  
- Used the **Adam optimizer** for efficient learning.  
- **Performance:** Achieved an **R² score of ~0.78** on unseen data 🎉  

📌 This means the model predicts medical costs fairly accurately and isn’t just memorizing the training data.  

⚠️ Challenge: Predicting **super high charges** remains tricky, leaving room for future improvements.  



## 🛠️ How to Run  

### 2. Set Up Environment  
Make sure you have **Python 3.8+** installed. Create a virtual environment and install dependencies:  


### 3. Run the Notebook

Start Jupyter and open the notebook:



jupyter notebook Mini_Project_DL_Regression.ipynb


### 4. Explore & Experiment
Run all cells to reproduce results.

Try tweaking hyperparameters or network structure for improved performance.

# ✅ Conclusion
This project shows how deep learning (ANNs) can be applied to predict real-world outcomes like medical insurance costs.
It highlights the importance of EDA, feature understanding, and model tuning in building effective AI models.
