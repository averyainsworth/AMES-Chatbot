# AMES-Chatbot

# This project contains code for a model and for the chatbot that utilizes the model. 
# The final model that ended up being used for the chatbot was the last one, which included a bidirectional-LSTM layer
# After the model was completed we wrote code that then saves the model and loads it to use it on the user responses
# The chatbot selects three questions at random from a txt file
# The chatbot then asks the user the first question and their response is saved
# Then the model.predict() function is ran on the response and the highest percentage from the output list is chosen using the numpy.array.argmax() function
# After the highest percentage is chosen it is converted into the matching sentiment
# The chatbot then responds with an appropriate response depending on what the sentiment is
# If the user types "bye" at any time the conversation ends but if they respond with anything else the chatbot asks the next question
# This process repeats for three questions and all of the user's responses are saved
