## Description of the packages used

1. `django`: our backend python framework, handles routing, db management, authentication, manages server side logic
2. `djangorestframework`: used to build web api's to communicate with the frontend, enables easy data transmission between python objects and json
3. `web3`: used to interact with etherium blockchain, allows block creation, enables wallet connections and smart contract verification
4. `pymongo`: enables db connection
5. `python-dotenv`: store sensitive information like api keys, database credentials
6. `djangorestframework-simplejwt`: provides json web token(jwt) authentication(login, token generation), stateless auth
7. `djongo`: mongodb connector to django
8. `django-cors-headers`: allows frontend to interact with django backend, manages security for cross-origin requests, configures which domain can access our api

## Database migration
track and handle the changes in the schema of database

## Superuser
- Administrative user of the django project's admin interface
- Allows us to log into django admin panel(gives complete control of the backend)
- To access django admin
```
http://localhost:8000/admin
```

