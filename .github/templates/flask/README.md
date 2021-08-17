# flask_test_1 Flask Application

This is a Flask application.

## Installation

From source:

```bash
git clone https://github.com/huogerac/flask-test-1 flask_test_1
cd flask_test_1
make install
```

From pypi:

```bash
pip install flask_test_1
```

## Executing

This application has a CLI interface that extends the Flask CLI.

Just run:

```bash
$ flask_test_1
```

or

```bash
$ python -m flask_test_1
```

To see the help message and usage instructions.

## First run

```bash
flask_test_1 create-db   # run once
flask_test_1 populate-db  # run once (optional)
flask_test_1 add-user -u admin -p 1234  # ads a user
flask_test_1 run
```

Go to:

- Website: http://localhost:5000
- Admin: http://localhost:5000/admin/
  - user: admin, senha: 1234
- API GET:
  - https://localhost:5000/api/v1/product/
  - https://localhost:5000/api/v1/product/1
  - https://localhost:5000/api/v1/product/2
  - https://localhost:5000/api/v1/product/3


> **Note**: You can also use `flask run` to run the application.
