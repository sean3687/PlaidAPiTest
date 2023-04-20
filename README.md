1. Import Sandbox API Keys
- run following on terminal

```jsx
cp .env.example .env
```

1. Import following keys at: **/quickstart/.env.example** 

```jsx
PLAID_CLIENT_ID=642e5535ef73aa0013d50f67
PLAID_SECRET=05d6681fd6a12f357002734ec3d1b0

PLAID_ENV=sandbox

PLAID_PRODUCTS=auth,transactions,identity

PLAID_REDIRECT_URI=
```

1. Open node directory and install dependencies

```jsx
cd node
npm i
```

1. run node server
- server will running on 8000

```jsx
npm start
```

1. Open front end directory and npm install

```jsx
cd frontend
npm install
```

1. Run frontend

```jsx
npm start
```
