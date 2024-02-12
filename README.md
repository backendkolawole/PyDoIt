# PyDoIt
`PyDoIt` is built using `Python` and `Django`.
`PyDoIt` is an intuitive and easy-to-use task manager that can greatly simplify your project management and improve your development efficiency. 

Defining tasks in `PyDoIt` is simple and intuitive. You can specify task names and status using a user-friendly syntax. This makes it easy to organize and manage complex projects.

## ⚙️ Installation

- Open CMD
  
- Change directory to desktop

  `cd desktop`
   
- Clone this repository

  `git clone git@github.com:backendkolawole/PyDoIt.git`

- Change the current directory

  `cd PyDoIt`

- Create a virtual environment

  `python -m venv myvirtualenv`
  
- Activate virtual environment

  `myvirtualenv\Scripts\activate`

- Install all the packages listed in your requirements.txt file

  `pip install -r requirements.txt`

- In the same directory as settings.py, create a file called `.env`

  - Set up the `SECRET_KEY` variable

> [!WARNING]
> `SECRET_KEY` is the key to securing signed data – it is vital you keep this secure, or attackers could use it to generate their own signed values.

  
- Make migrations

  `python manage.py makemigrations`

- Apply migrations

  ` python manage.py migrate`
  
- Run server

  `python manage.py runserver`
