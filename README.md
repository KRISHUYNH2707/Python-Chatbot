# An-rule-based-Chatbot-in-Python-and-Flask

##  An rule-based Chatbot using Python and Flask REST API

### Execution

To run this Bot, First run the requirement.txt file as follows:

1. Open a terminal or command prompt
2. Navigate to the folder with your requirements.txt
  run: pip install -r requirements.txt
  You are done installing dependencies
3. Then, run the train.py file to train the model. This will generate a file named chatbot_model.h5. 
This is the model which will be used by the Flask REST API to easily give feedback. 
4. After running train.py, next run the app.py to initialize and start the bot. 

Note: To add more terms and voccabulary to the bot, modify the intents.json file and add your personalized words and retrain the model again.
