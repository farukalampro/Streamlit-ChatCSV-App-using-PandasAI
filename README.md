# ChatCSV-Streamlit-App
An LLM powered ChatCSV Streamlit app so you can chat with your CSV files.
![chat_with_csv](https://github.com/farukalampro/Streamlit-ChatCSV-App-using-PandasAI/assets/92469073/453683be-f66a-492f-954d-646067e50778)

<h1> How to run the app?</h1>
<p> OpenAI instantly revokes the API key once it detects that the key has been exposed publicly. So, that's the only thing to take care of.</p>
 
 Generate your OpenAI API key here: <a href="https://platform.openai.com/account/api-keys"> Click Here </a>
<br>
<h2> Run locally </h2>
<p> If you are running the app locally, then you can freely use the API key.
  
  ```
  
  openai_api_key = 's#-#####################jz'
  
  #can set the API key directly, if running locally.
  
  ```
 
 Else if you want to keep the key private, store it in an environment variable named 'API_KEY' in your OS and then refer the key in app.py by:
 
  ```
  from dotenv import load_dotenv
  load_dotenv()
  openai_api_key = os.getenv("OPENAI_API_KEY")
 
  ```
  
 
  Henceforth make sure to have Streamlit installed in your system. Run the app by:
  
  ```
  git clone https://github.com/farukalampro/Streamlit-ChatCSV-App-using-PandasAI.git
  cd Streamlit-ChatCSV-App-using-PandasAI
  pip install -r requirements.txt
  streamlit run app.py
  
  ```
 <h2> Run on Cloud </h2>
 
 <p> You can also run this app locally on Streamlit Cloud, which is a free Cloud Hosting Service. 
 <br>
 Make a .env  file and store the key as 
 
 ```
 OPENAI_API_KEY='##-###############'
 
 ```
 There's already a .gitignore file with .env mentioned in it. If not, make one. <br>
 Remaining code remains the same.
