🩺 Predicting Medical Insurance Costs with AI 🤖
Ever wonder how insurance companies figure out what you'll pay? This project is all about using a special kind of AI called an Artificial Neural Network (ANN) to predict medical insurance charges. It's a great way to see how deep learning can be used to solve real-world problems!

🚀 What's Inside?
Mini_Project_DL_Regression.ipynb: This is the main Jupyter Notebook with all the code. It takes you on a journey from exploring the data to building and testing the AI model.

README.md: You're reading it right now! It gives you a quick rundown of the project.

📊 The Data
We're working with a dataset that has some neat info about people, like:

age: How old they are.

sex: Whether they're male or female.

bmi: Their Body Mass Index.

children: How many kids are on their plan.

smoker: Do they smoke? (Spoiler alert: this one's a big deal!)

region: Which part of the US they live in.

charges: The medical costs we're trying to predict!

🕵️‍♂️ Finding Insights (EDA)
Before we built our AI, we played detective with the data. Here's what we found:

We had a duplicate row in the data, so we got rid of it.

Turns out, smokers have much, much higher medical charges. 🚬

People with a higher BMI and older age also tend to have higher costs.

Interestingly, folks in the Southeast region have the highest average charges.

🛠️ Tools and Technologies
This project was built using the following Python libraries:

Pandas & NumPy: For all the heavy lifting with data cleaning and manipulation.

Scikit-learn: To get the data ready for our AI model.

Matplotlib: For creating all the cool plots and visualizations that helped us understand the data better.

TensorFlow & Keras: The brains behind the operation! These are the powerful deep learning frameworks we used to build our neural networks.

🧠 Building Our AI Brain
We tried out a couple of different AI models:

The "Starter" Model: This one was pretty simple, but it didn't do so well. In fact, its performance was so bad it got a negative R2 score! 🙈

The "Smarter" Model: We beefed up this model with some cool features like EarlyStopping, Dropout layers (to prevent it from getting too confident in its training data) and a powerful Adam optimizer. This one was a huge success!

This smarter model was able to predict medical costs with an R2 score of about 0.78 on data it had never seen before. That means it's pretty accurate and isn't just memorizing the training data!

While it did a great job overall, we noticed that predicting super high charges is still a bit tricky. But hey, that just gives us something to work on for the next version!
