Coldx is a cold email generator which students can use to generate cold emails for a specific job application 
You have just to input the url of the job the application and it will simply generate the cold mail

Technologies Used : Langchain , Llama3.1 LLM , Chromadb , Streamlit

Project Architecture : 

<img width="1144" height="391" alt="image" src="https://github.com/user-attachments/assets/9d83b478-3839-4a40-986f-b16abe03e337" />

Working Flow :

Firstly when the user will provide the job link to the app the langchain will extract the whole Job description and further 
the llama model will extract the role , experience , skills and description in the Json format then the action will go onto
chromadb where the skills asked in job description is matched with the one in chromadb to extract the portfolio links of the
user to add in cold mail next based upon that the LLM will generate the Cold email for the user with all necessary description and skills

Here is the Screenshot of the Project 

<img width="1820" height="895" alt="image" src="https://github.com/user-attachments/assets/8d273321-d003-4f04-b979-ebb5eb4e2e4f" />


