# AIPostGenerator
Create a content and image for post on social media with useage of AI.

# Scenario description
Project was made for learning purposes.

The scenario steps are as follows:
1. Read the details from excel file
2. For each row in input excel
   - Generate the contnet of a post with GPT.
   - Generate the image with GPT and save it localy.
   - Store all this data in excel file for coresponding row
3. Save the excel

# Folder sctructure
- main.py - Python file which cotnains whole script
- input_posts.xlsx - input excel file template with given names of collumns and some examples data. WARNING!: Changing the data scturcutre in input file might affect directly on working of a whole project. Two example inputs has been added to help in understanding the way of working and can be freally removed.
- envExample.txt - file which contains all enviromental variables. To use it simply store .env file in a same location as a script. WARNING!: This is a place where You need to provide Your API key to OpenAI. You can create it direclty from here: https://platform.openai.com/settings/organization/api-keys
