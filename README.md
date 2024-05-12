# realtime AI Fortune Teller

## Additions

```python
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
# if you get error from the pip install, install each import that does not 
# load, pip install <module to load>
```

## Make sure you secret.toml is created in your user .streamlit folder (using Mac OS M2)

- you may have a creditals.toml copy it and add your keys
- api_key = (for assemblyAI key)
- open_api_key = (openai key)

- reference this link for other information
- <https://docs.streamlit.io/deploy/streamlit-community-cloud/deploy-your-app/secrets-management>

### 1. Obtain the AssemblyAI API key & OpenAI API & Store API Keys

Create a folder called `.streamlit` in the project folder. In this folder create a file called `secrets.toml` and paste the below keys in the .toml file:

```python
api_key = 'AssemblyAI-API-KEY'
openai_api_key = 'OpenAI-API-KEY'
```

### 2. Pip install libraries

```bash
pip install -r requirements.txt
```

### 3. Launch the app

```bash
streamlit run streamlit_app.py
```
