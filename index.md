Implemented a deep learning version of a chatbot in Python which is accurate. We can customize the data according to business requirements and train the chatbot with great accuracy. Chatbots are used everywhere and all businesses is looking forward to implementing bot in their workflow.
# Dataset
The dataset we will be using is ‘intents.json’. This is a JSON file that contains the patterns we need to find and the responses we want to return to the user.

The chatbot will be trained on the dataset which contains categories (intents), pattern and responses. The project uses a special recurrent neural network (LSTM) to classify which category the user’s message belongs to and then we will give a random response from the list of responses.
