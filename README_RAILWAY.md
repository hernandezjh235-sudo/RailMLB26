# Railway deploy setup

Use this folder as your GitHub repo contents, or copy these files into your current repo.

Required files:
- app.py
- requirements.txt
- railway.json
- Procfile
- runtime.txt
- .streamlit/config.toml

Railway start command:
streamlit run app.py --server.port $PORT --server.address 0.0.0.0

After pushing to GitHub, connect the repo to Railway and deploy.
