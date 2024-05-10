# Projeto_Alura_2024
!pip install -q -U google-generativeai
     

from google.colab import userdata
gemini_key = userdata.get('gemini_key')
     

import google.generativeai as genai
genai.configure(api_key=gemini_key)
