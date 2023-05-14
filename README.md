# Faithful Benchmark for Information Seeking Dialogue
#### CSE635: Natural Language Processing and Text Mining (Prof. Rohini Srihari & Souvik Das)

This repository consists of Final project implementation. 
The final implementation are in the Milestone3/Codes directory and the files are as listed below:
1. BEGIN_BERT.ipynb
2. VRM_Bert.ipynb
3. Text_generation.ipynb

## Instructions for Execution
#### Steps to check ouputs of all the files:
1. Download the file.
2. Run the entire ipynb file in either Colab or Kaggle environment by importing the file in either of the environments.
3. Execute the ipynb files as different notebooks and incase of Kaggle select GPU T100 and for Google colab select the GPU from run-time. 

#### Specific instructions for Text_generation.ipynb:
1. The file has a function called 'generate_response' which requires manual input from the user.
2. When the cell is executed, input a query for example: "Do you like pizza?". 
3. Next you will be prompted to enter the associated knowledge. Enter the associated knowledge with respect to the query asked in setp 2 for example: "Pizza is a dish of Italian origin consisting of a usually round, flat base of leavened wheat-based dough topped with tomatoes, cheese, and often various other ingredients, which is then baked at a high temperature, traditionally in a wood-fired oven.".
4. The response will then be generated using the model trained which will be printed as a model output response.
5. Copy the response generated and provide it as a input to the Begin classifier to understand what kind of response it is.

## Things to take care of: 
1. The files already have pre-saved outputs from the previous run.
2. As the size of the data is above 18,000 it would take atleast 45-60mins to train so please make sure you have adequate resources to execute the code.
