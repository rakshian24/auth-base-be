# Auth Base

## Base node project for providing authentication

Authentication is provided by storing JWT in httpOnly cookies on signIn/signUp and clearing this coookie on signOut.

### API is hosted live [here](https://rakshian-auth-base-be.vercel.app)

<hr>

### API documentation

#### 1. Sign up

<b>Endpoint - </b> `/api/v1/users/signUp`<br>
<b>HTTP method - </b> `POST`<br>
<b>Payload - </b>

```
{
    "name": "your_name",
    "email": "your_email@gmail.com",
    "password": "Your Password",
    "confirmPassword": "Your Password"
}
```

<br>
<hr>

#### 2. Sign in

<b>Endpoint - </b> `/api/v1/users/signIn`<br>
<b>HTTP method - </b> `POST`<br>
<b>Payload - </b>

```
{
    "email": "your_email@gmail.com",
    "password": "Your Password",
}
```

<br>
<hr>

#### 3. Sign out

<b>Endpoint - </b> `/api/v1/users/signOut`<br>
<b>HTTP method - </b> `POST`<br>
<br>

<hr>

#### 4. Get profile

<b>Endpoint - </b> `/api/v1/users/profile`<br>
<b>HTTP method - </b> `GET`<br>
<br>

<hr>

#### 5. Update profile

<b>Endpoint - </b> `/api/v1/users/profile`<br>
<b>HTTP method - </b> `PUT`<br>
<b>Payload - </b>

```
{
    "name": "your_updated_name",
}
```

<br>
<hr>
<hr>
