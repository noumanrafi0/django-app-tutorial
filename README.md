# django-app-tutorial

Implementation of django app (project) following the tutorial officially available at (https://docs.djangoproject.com/en/4.2/intro/tutorial01/)

## Installation (For macOS and Linux)

To install and run the project locally, follow the steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/noumanrafi0/django-app-tutorial.git
   ```

2. Navigate to the project directory:

   ```bash
   cd django-app-tutorial
   ```

3. Create a virtual environment:

   ```bash
   python3 -m venv env
   ```

4. Activate the virtual environment:

   ```bash
   source env/bin/activate
   ```

5. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

6. Apply database migrations:

   ```bash
   python manage.py makemigrations
   ```

   ```bash
   python manage.py migrate
   ```

## Usage

1. Access the app at `http://127.0.0.1:8000/polls/` to participate in the polls.

## Credits

- [Django Framework](https://www.djangoproject.com/)
