# todo-list-django

🚧 Requirements:

- Python 3.11
- Docker

## 💿 Running the app

First, create a virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate
```

Then, install the dependencies:

```bash
pip install -r requirements.txt
```

Finally, run the server:

```bash
docker build -t todo-list-django .

docker run -p 8000:8000 todo-list-django

```

🏁 Open http:localhost:8000/ in your browser.

✌🏼 By [dev-azevedo](https://linkedin.com/in/dev-azevedo)