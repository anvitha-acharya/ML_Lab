# ML_Lab

```
import requests

url = "https://raw.githubusercontent.com/anvitha-acharya/ML_Lab/refs/heads/main/filename.ipynb"
response = requests.get(url)

# Save locally
with open("filename.ipynb", "wb") as f:
    f.write(response.content)
```

```
!pip install nbimporter
```

```
import nbimporter
import filename
```
