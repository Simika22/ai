Import the necessary libraries:
Import the ChatBot class from the ChatterBot library.
Import the ChatterBotCorpusTrainer class for training the chatbot.
Define any other required variables, like products and response prompts.
Create a chatbot instance:

Create a ChatBot instance with a name (e.g., 'EcommerceBot').
Train the chatbot:

Create a ChatterBotCorpusTrainer instance and train the chatbot on the English language corpus.
Define functions and variables:

Define functions to handle product information and user input.
Define product information and response prompts as required.
Get user's name:

Prompt the user to enter their name.
Start a conversation loop:

Display a welcome message.
Within the conversation loop:

Prompt the user for input.
If the user input is "bye," exit the loop and say goodbye.
Otherwise, call the chatbot_response function to handle the user's input.
Inside the chatbot_response function:

Convert user input to lowercase for case-insensitivity.
Check if the input contains a greeting. If it does, return a greeting response.
Check if the input is "bye." If it is, return a goodbye response and exit.
If the input contains the word "price," provide a general response about asking for product prices.
If none of the above conditions are met, iterate through the products and check if any product name is mentioned in the input. If found, call the get_product_info function and return the product details.
If none of the above conditions are met, return a generic "I didn't understand" response.
In the get_product_info function:

Check if the product name exists in the products dictionary.
If the product exists, return a formatted response with the product's name, price, and description.
If the product doesn't exist, return a "not found" response.
Display the chatbot's response to the user's input within the conversation loop.
