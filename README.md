# Chat-Groq an Chatbot using LangChain and Groq
- Created a conversational chatbot using langchain and groq
- Utilised the UI capabilities of streamlit
- Used [Groq](https://groq.com/) Inference API to utilise the `Llama3-8b-8192` model
---
## To run locally
1. Modify the `GROQ_API_KEY` from `st.secrets` to `os.gentenv` or just pass the api key which you can get at [keys](https://console.groq.com/keys).
2. Run command
```
pip install -r requirements.txt
```
3. then after installing all the packages run
```
streamlit run app.py
```
---
## To modify the theme and styling of the streamlit UI
- Refer to [link](https://docs.streamlit.io/develop/concepts/configuration/theming)
