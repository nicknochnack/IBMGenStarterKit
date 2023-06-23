# Building  Apps with watsonx.ai and Streamlit
So I'm guessing you've been hearing a bit about watsonx. Well...now you can build your very own app with it🙌 (I know...crazy right?!). In this tutorial you'll learn how to build your own LLM powered Streamlit with the IBMGen library.  

## See it live and in action 📺
[![Tutorial](https://i.imgur.com/qBoUX8m.jpg)](https://youtu.be/u8vQyTzNGVY 'Tutorial')

# Startup 🚀
1. Create a virtual environment `python -m venv watxonx`
2. Activate it: 
   - Windows:`.\watxonx\Scripts\activate`
   - Mac: `source watxonx/bin/activate`
3. Clone this repo by running `git clone <this repo name>` 
4. Install the dependencies by running `pip install -r requirements.txt`
5. Update your watsonx.ai API key on Line 11 of `app.py` 
      <i>e.g. APIKEY = 'pak-2SuHPQ8y9eDznqXa-7ml-ecMAUJGLseuC3j8Cc41ZVQ'</i>
6. Run the app by running the command `streamlit run app.py`

# Other References 🔗
<p>-<a href="https://workbench.res.ibm.com/docs/ibm-generative-ai">IBMGen Documentation</a>:documentation for the IBMGen library available through the tech preview UI.</p>
<p>-<a href="https://github.com/IBM/ibm-generative-ai#langchain-extension">IBMGen Langchain Extension</a>:Langchain is a highly popular LLM library, it's used to structure prompt chains and llm workflows. In this tutorial we use the IBMGen langchain extension to generate responses.</p>

# Who, When, Why?
👨🏾‍💻 Author: Nick Renotte <br />
📅 Version: 1.x<br />
📜 License: This project is licensed under the MIT License </br>

