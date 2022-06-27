Assignment-3-2

Ronen Aranovich- 314983438

Ohad Shriki- 203665401

API link- https://app.swaggerhub.com/apis-docs/Ronen96/Register/1.0.0

# Soccer League Managament - Backend

## Danish Superliga Server


This project is a backend server to manage the Danish Soccer Superliga. It uses [Sportmonks API](https://docs.sportmonks.com/football/) to import the real Superliga data to the server. We used [Azure Database](https://portal.azure.com/#home) to create and store our own data - such as Users, Permissions and Soccer Games.



## How To Install
 
1. Install [Node JS](https://nodejs.org/en/download/) 
2. Install [npm](https://docs.npmjs.com/cli/v7/commands/npm-install)
   ```
   npm install
   ```
3. Install Dependent Packages
    ```
   npm i
   ```
4. Run
   ```
   node project/main.js
   ```
5. Your server will be available on http://localhost:3000/ 
6. If everything is installed correctly, your server will respond to [alive test call](http://localhost:3000/alive)

   ![image](https://user-images.githubusercontent.com/73793617/120918876-6de96e80-c6bf-11eb-9a14-577bd6d9541f.png)

## API

To create our API we used [SWAGGER UI Editor](https://editor.swagger.io/). You can find our API documented here:

https://app.swaggerhub.com/apis-docs/Ronen96/Register/1.0.0

Alternativly, you can access it locally after cloning this repository, install all dependencies and setting up the Server at http://localhost:3000/api

## FIFA Representative 


To access Manager's Functionalities you will have to be logged in as FIFA Representative


```yaml
{
 "username": "Admin"
 "password": "Admin"
}
```
</br>
</br>


