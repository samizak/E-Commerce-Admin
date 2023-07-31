# Fullstack E-Commerce Admin Panel

## Description
A fullstack E-Commerce Admin panel created with NextJS, React, TailwindCSS, Clerk, shadcn and Prisma.

- [Link to Main Store](https://github.com/samizak/E-Commerce-Store/).

## Live Preview
https://e-commerce-admin-woad.vercel.app/

## Technologies
* TypeScript
* NextJS
* React
* Tailwind CSS
* MySQL
* Prisma
* Clerk
* Zustand
* shadcn
* Axios
* React Hot Toast
* Lucide React
* Stripe

## Key Features:

- Ability to create, search and control multiple `stores` through Admin CMS.
- Ability to view store `overview` of sale details and revenue graph.
- Ability to create, update and delete `Billboards`.
- Ability to create, update and delete `Categories`.
- Ability to create, update and delete `Products`.
- Ability to update `Store` name.
- Ability to upload multiple images for products and change or remove them.
- Ability to create, update and delete filters such as `Color` and `Size`.
- Ability to control `Featured` products.
- Ability to `archive` products.
- Ability to view orders and sales.
- Ability to toggle `Dark` and `Light` mode theme.
- Using `Stripe` Intergration.
- Using `MySQL` database.


# Getting Started

## 1. Cloning the repository
```shell
git clone https://github.com/samizak/E-Commerce-Admin.git
```

## 2. Install packages
```shell
npm i
```
Or if you prefer using Yarn:
```shell
yarn install
```

## 3. Setup .env file
```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

# This was inserted by `prisma init`:
# Environment variables declared in this file are automatically made available to Prisma.
# See the documentation for more detail: https://pris.ly/d/prisma-schema#accessing-environment-variables-from-the-schema

# Prisma supports the native connection string format for PostgreSQL, MySQL, SQLite, SQL Server, MongoDB and CockroachDB.
# See the documentation for all the connection string options: https://pris.ly/d/connection-strings

DATABASE_URL=
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=
STRIPE_API_KEY=
FRONTEND_STORE_URL=
STRIPE_WEBHOOK_SECRET=
```

## 4. Connect to PlanetScale and Push Prisma Database
```shell
npx prisma generate
npx prisma db push
```


## 5. Start the app
```shell
npm run dev
```
Or if you prefer using Yarn:
```shell
yarn dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |


## Preview
### Main Dashboard
![Untitled](https://github.com/samizak/E-Commerce-Admin/assets/30938455/db23d33a-e469-44a1-9813-9d2bfef9e297)

### Edit Product
![Untitled2](https://github.com/samizak/E-Commerce-Admin/assets/30938455/4f8a752b-652e-46c1-b913-1695902ed5fd)
