# Android Suitmedia Mobile Test

<img src="https://i.postimg.cc/Jh5VFtqy/Screen-Shot-2023-01-16-at-01-22-21.png" />

## ABOUT
This project was done as a test as a mobile developer at Suitmedia on the Merdeka Campus Batch 4. The project was ordered to be completed within 24 hours after redeeming the access code and working according to the instructions. Project implements the concepts of Activity, Intent, etc. There are commands that require the use of the Retrofit library as well to consume the API

## START PROJECT

To get the *completed code*, clone the repo or download the repo

## DESIGN

The design was provided by Suitmedia in the context of selection as a mobile developer.

## API CONSUME

This application consumed the API from <a href="https://reqres.in">Reqres In Fake User</a>

### Get Users

Request :

- Method : GET
- Endpoint : `/api/users`
- Header :
  - Accept: application/json
  - Autohorization: Bearer token
- Query Param:
  - page: integer

Response :

```json
{
  "page": "integer",
  "per_page": "integer",
  "total": "integer",
  "total_pages": "integer",
  "data": [
    {
      "id": "integer",
      "email": "string, email",
      "first_name": "string",
      "last_name": "string",
      "avatar": "string",
    },
    ...
  ],
  "support": {
    "url": "string",
    "text": "string",
  }
}
```

## RESULT

- First Screen Layout<br/>
<img src="https://i.postimg.cc/VsDmGRqP/Screenshot-20230114-010640.png" width="260px" />

- First Screen Layout When User Click Next Button Without Fill Name Input<br/>
<img src="https://i.postimg.cc/R0Xg5NXh/Screenshot-20230114-010709.png" width="260px" />

- When Palindrom Input Value is Palindrom Word<br/>
<img src="https://i.postimg.cc/Pf80ZQSM/Screenshot-20230114-010752.png" width="260px" />

- When Palindrom Input Value is not Palindrom Word<br/>
<img src="https://i.postimg.cc/9frL2cSB/Screenshot-20230114-010813.png" width="260px" />

- Second Screen Layout<br/>
<img src="https://i.postimg.cc/jjp4rPys/Screenshot-20230114-010829.png" width="260px" />

- Loading Third Screen Layout<br/>
<img src="https://i.postimg.cc/pTkrBtWg/Screenshot-20230114-010845.png" width="260px" />

- Third Screen Layout Just Half of Data is Showed<br/>
<img src="https://i.postimg.cc/J0fLNTkf/Screenshot-20230114-010858.png" width="260px" />

- Third Screen Layout When All of Data is Showed<br/>
<img src="https://i.postimg.cc/7YS6B7Z3/Screenshot-20230114-010915.png" width="260px" />

- Second Screen Layout When User Select The User in Third Screen Layout<br/>
<img src="https://i.postimg.cc/3xn36Z5v/Screenshot-20230114-010931.png" width="260px" />




