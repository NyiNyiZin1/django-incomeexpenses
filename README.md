Income Expenses API

## Installation steps

1. Ensure you have python3 installed

2. Clone the repository
3. create a virtual environment using `virtualenv venv`
4. Activate the virtual environment by running `source venv/bin/activate`

- On Windows use `source venv\Scripts\activate`

5. Install the dependencies using `pip install -r requirements.txt`

6. Migrate existing db tables by running `python manage.py migrate`

7. Run the django development server using `python manage.py runserver`

### Note(Not useful)
1. http://localhost:8000/api/api.json
2. python manage.py flushexpiredtokens
3. "redirect_url": "incomeexpenses://reset"
4. send mail
5. auth provider facebook, google, twitter
6. swagger UI
