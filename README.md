# ScholarScout
An AI agent for academic professionals to find the next destination for their higher studies.
(Work in progress)

# Data files
Download necessary files from this link: https://drive.google.com/drive/folders/1T2d_gP8iNjqLKnmNGXXqBeOxkRrZ4GT9?usp=sharing

# Setup
```
python3 -m pip install -r requirements.txt
```
1) To setup db, install postgresql and configure its setting.

2) Then use the `scripts/scholarscout_schema.sql` to setup db.
3) Add your db credentials in `scripts/insert_sql_data.py` and run the script to add university data in db. Make sure you have downloaded the files Data files and placed in respective directory.
4) Then setup your .env file for API_KEYS
    ```
    OPENAI_KEY
    OLLAMA_API_KEY # if using OLLAMA otherwise not needed
    ```

Then you can run the agent.py to start the conversation agent.