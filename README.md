# ParalegalAssistant 🏛️
Paralegal Assistant created using Langflow and Ollama Model

## Prerequisites
install python 🐍 :
https://www.python.org/downloads/

install Langflow :
`pip install langflow`

install ollama :
https://ollama.com/download/mac

install qwen 2.5 ( default setup is fine ) :
`ollama run qwen2.5`
https://ollama.com/library/qwen2.5

# Setting up Assistant to run Local 🚌

Download the Assistant flow JSON file from this repo

Run the following in your command line : 

`ollama run llama3.2` 

In another command line window run the following :

`langflow run`

Copy and paste the local host address into your browser. You should see a screen similar to the following :

![Screenshot 2025-03-31 at 2 15 37 PM](https://github.com/user-attachments/assets/0ab90e94-8adf-4938-8cc7-2ed72d2ab6f7)

Select `new flow`, you can create a blank flow since you will be importing the model from JSON file. 

Select import from the dropdown menu located near the center of your new blank flow page as shown below :

![Screenshot 2025-03-31 at 2 19 10 PM](https://github.com/user-attachments/assets/74ca62ea-275b-4c6e-a489-8d3d1bea4b0b)

Select the `Paralegal Assistant.json` file

You then should be able to test the assistant by entering playground mode and interacting :

![Screenshot 2025-03-31 at 2 23 23 PM](https://github.com/user-attachments/assets/eb426cf5-a280-45bc-8599-07f5282ce51b)


# Congratulations, You have setup the Paralegal Assistant to run Locally on your Machine! 🎉
