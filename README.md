# Hiding Node.js Environment Varaibles

Using the4 `dotenv` Nopde.js package to load variables from an .env file.

1. Create a file called `.env` and place it in your project folder.

2. Put your actual database credentials and API keys in your `.env``file:
    
    ```php
    DB_HOST=<DB_HOST>
    DB_DATABASE=<DB_DATABASE>
    DB_USERNAME=<DB_USERNAME>
    DB_PASSWORD=<DB_PASSWORD>
    
    API_SECRET=real_api_key
    ```

3. Create a second copy of your `.env` file and name it `.env.sample`. Use this file to provide instructions to the next programmer using your project code:
    
    ```php
    DB_HOST=localhost
    DB_DATABASE=database
    DB_USERNAME=username
    DB_PASSWORD=password
    
    API_SECRET=api_key
    ```

4. Make sure your GitHub repo does not include the file named `.env`. In your `.gitignore` file add:
    
    ```
    .env
    ```

> [!Note]
> I have excluded this step in this repo so you can view both the `.env` and `.env.sample` files. 

5. Add `dotenv` to your project:

    ```
    npm add dotenv
    npm i
    ```

6. Start the Node.js app:

    ```
    node app.js
    ```

---

## Project Stack

This project uses [Node.js](https://nodejs.org/).

<img src="https://console.codeadam.ca/api/image/nodejs" width="60"> 

---

## Repo Resources

- [Node.js](https://nodejs.org/)
- [dotenv](https://www.npmjs.com/package/dotenv)

<a href="https://codeadam.ca">
<img src="https://codeadam.ca/images/code-block.png" width="100">
</a>
