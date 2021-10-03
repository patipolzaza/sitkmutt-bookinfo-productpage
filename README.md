# How to run product page

## Prerequisite

* Python 3.8

```bash
pip install -r requirements.txt
python productpage.py 9080
```

## How to run docker
```bash

# Build Docker Image for rating service
docker build -t productpage .

# Run Python port=8083
docker run -d --name productpage -p 8083:8083 productpage
```