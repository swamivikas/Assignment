# Convin-Assignment
Assignment: Daily Expenses Sharing Application

 # Prerequisites
 ## Python 3.x
 ## Django

# Setup Django:
  ## Make sure MongoDB is installed and running. Adjust the database settings in settings.py as needed:
   ```
  DATABASES = {
    'default': {
        'ENGINE': 'djongo',
        'NAME': 'expenses_db',
    }
    }
  ```


# Apply the migrations:

```
python manage.py makemigrations
python manage.py migrate
```

# Run the server:

```
python manage.py runserver
```

# API Endpoints

## Create User: POST /api/users/
### you can see the testing of api on postman in below image
![Screenshot 2024-07-27 172916](https://github.com/user-attachments/assets/503acce6-0df0-4a26-8a0f-c1e540a588dc)



## Retrieve User Details: GET /api/users/{id}/
### you can see the testing of api on postman in below image
![Screenshot 2024-07-27 173040](https://github.com/user-attachments/assets/af5e58b4-602d-4e15-bd63-876108cd6034)

## Add Expense: POST /api/expenses/
### you can see the testing of api on postman in below image -> it is a post request so user have to provide data 
![Screenshot 2024-07-27 173143](https://github.com/user-attachments/assets/97c1c5c7-fbe9-4190-9cbc-bedf81fd8eb5)

## Retrieve Individual User Expenses : /api/expenses/{enter user id}/user_expenses/
### you can see the testing of api on postman in below image
![Screenshot 2024-07-27 173342](https://github.com/user-attachments/assets/2f2e202f-203c-43ed-a0ef-378122692f16)

## Retrieve Overall Expenses : /api/expenses/all_expenses/
### you can see the testing of api on postman in below image
![Screenshot 2024-07-27 173440](https://github.com/user-attachments/assets/6ba09b6d-2bd4-4bbd-8c10-2ce87c28085c)
