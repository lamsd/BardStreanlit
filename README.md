# Introduction to BardAPI

You need to check the keyAPI of google bard by webbrowser.

Link: https://bard.google.com/?hl=en 


The steps is found out API key: 
1. Click right mouse and chose inspect
2. Choose  "Application".
3. Choose "Cookies: https://bard.google.com"
4. Find and copy "__Secure-1PSID" value.
5. Paste the value in config.py file.


### Setting up:
```python
    pip3 install -r Requirment.txt
    streamlist run main.py --server.port 8501
```

