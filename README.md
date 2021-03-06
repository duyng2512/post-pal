# Post Pal A Scanning Solution for VN Post Vinh Long



## App Introduction


<p align="center">

  <img src="/read-me/app-logo.png">
  
</p>



## Features

- Basic Authentication (Register/Login with hashed password)
- Account confirmation with 4 (Changeable) digit OTP.
- Email helper ready just import and use.
- JWT Tokens, make requests with a token after login with `Authorization` header with value `Bearer yourToken` where `yourToken` will be returned in Login response.
- Pre-defined response structures with proper status codes.
- Included CORS.
- **CRUD** operations.
- Validations added.
- Included API collection for Postman.
- Light-weight project.




## How to install

### Using Git (recommended)

1.  Clone the project from github. Change "myproject" to your project name.

```bash
git clone https://github.com/duyng2512/post-pal.git ./myproject
```

### Using manual download ZIP

1.  Download repository
2.  Uncompress to your desired directory

### Install npm dependencies after installing (Git or manual download)

```bash
cd myproject
npm install
```



## How to run

### Running API server locally

```bash
npm run dev
```

You will know server is running by checking the output of the command `npm run dev`

```bash
Connected to mongodb:YOUR_DB_CONNECTION_STRING
App is running ...

Press CTRL + C to stop the process.
```

**Note:** `YOUR_DB_CONNECTION_STRING` will be your MongoDB connection string.



## License

This project is open-sourced software licensed under the MIT License. See the LICENSE file for more information.
