Stage 1. Collect LinkedIn posts and extract Topic, Language, Length  from it.
Stage 2. Now use topic, language and length to generate a new post. Some of the past posts related to that specific topic, language and length will be used for few shot learning to guide the LLM about the writing style etc.




Set-up
To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside .env update the value of GROQ_API_KEY with the API_KEY you created.
use latest llama model                                                                                                                                                 
To get started, first install the dependencies using:                                                                                                              
 pip install -r requirements.txt                                                                                                                                    
Run the streamlit app:                                                                                                                                                 
streamlit run main.py
