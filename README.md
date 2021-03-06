# AI-Chatbot
 A retrieval based chatbot using NLTK, Keras, Tensorflow, Python, etc. Chatbot project using Python
Implemented a deep learning version of a chatbot in Python which is accurate. We can customize the data according to business requirements and train the chatbot with great accuracy. Chatbots are used everywhere and all businesses is looking forward to implementing bot in their workflow.

Dataset
The dataset we will be using is ‘intents.json’. This is a JSON file that contains the patterns we need to find and the responses we want to return to the user.

The chatbot will be trained on the dataset which contains categories (intents), pattern and responses. The project uses a special recurrent neural network (LSTM) to classify which category the user’s message belongs to and then we will give a random response from the list of responses.

 Details of the file structure: 
 1. Intents.json – The data file which has predefined patterns and responses.
 2. train_chatbot.py – In this Python file, we wrote a script to build the model and train our chatbot.
 3. Words.pkl – This is a pickle file in which we store the words Python object that contains a list of our vocabulary.
 4. Classes.pkl – The classes pickle file contains the list of categories.
 5. Chatbot_model.h5 – This is the trained model that contains information about the model and has weights of the neurons.
 6. Chatgui.py – This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot.
 
-> Here are the 5 steps to create a chatbot in Python from scratch:
1. Import and load the data file
2. Preprocess data
3. Create training and testing data
4. Build the model
5. Predict the response

The program will open up a GUI window within a few seconds. With the GUI you can easily chat with the bot.
