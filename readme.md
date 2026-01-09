## Run Locally

Clone the project

```bash
  git clone https://github.com/CoderHritik0/Joyjunction-django.git
```
Go to the project directory

```bash
  cd Joyjunction-django
```

Create and activate a virtual environment

```bash
  python -m venv .venv
  .venv/Scripts/activate   # Windows  
  source .venv/bin/activate  # macOS/Linux

```

Install dependencies

```bash
  pip install -r requirements.txt
```

Run migrations

```bash
  python manage.py migrate
```

Create `.env` file in the root directory and add the following environment variables

```env
  SECRET_KEY=your_secret_key
```

Start the development server

```bash
  python manage.py runserver
```

Start another terminal and activate the virtual environment

```bash
  .venv/Scripts/activate   # Windows  
  source .venv/bin/activate  # macOS/Linux
```

Install Tailwind CSS dependencies

```bash
  cd theme/static_src/src
  npm install
```

again go to the root directory

```bash
  cd ../../../
```

Start Tailwind CSS in watch mode

```bash
  python manage.py tailwind start
```

Now visit:
👉 http://127.0.0.1:8000/