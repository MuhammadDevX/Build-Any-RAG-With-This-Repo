This repo contains the required code for creating a pinecone database and utilizing it for your RAG applications. 

Follow the following steps:
1. First clone the project
2. Create your python virtual environment
3. On the terminal run 'pip install -r requirements.txt' 
4. Create your database in pinecone on https://www.pinecone.io (The number dimensions is based on the embedding model used. The one that I have used has 1536 as the dimenstion for vectors)
5. Copy the Url for your database and add it to your .env file by the name PINECONE_API_KEY
6. Create an api key for openai and save it in your .env file by the name OPENAI_API_KEY
7. Add the index name to your .env file as well by the name PINECONE_INDEX_NAME (based on what you named from pinecone)
8. Run the commands one by one for getting your database. (Make sure to change the directory of the folder used in this code. Currently it is using  'test/'. Either change the directory or add all your pdfs to a folder named as test and then run the notebook)

Well done you have just created your own pinecone database and used a frontier model over it to respond according to the asked question. PLEASE STAR THIS REPO 
