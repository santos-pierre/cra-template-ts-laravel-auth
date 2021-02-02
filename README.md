# cra-template-ts-laravel-auth

>This is the official base template for [Create React App](https://github.com/facebook/create-react-app).

Template for [LaravelReactSPA](https://laravelreactspa.santospierre.com).

## Javascript

[Javascript Version](https://www.npmjs.com/package/cra-template-laravel-auth)

## Usage

### npx

```sh
npx create-react-app my-app --template ts-auth-laravel
```

Change in `.env.development`

```php
REACT_APP_API_URL="http://localhost:80/" // Backend Domain
REACT_APP_GITHUB_REDIRECT="http://localhost/github/auth/login"
```

> You need to reload the server after a change in environment varibales file.

### Work with Laravel brand new project
Check [LaravelReactSPA](https://laravelreactspa.santospierre.com) for the backend guide and implementation.

Recommend installing [sail](https://laravel.com/docs/8.x/sail) before

## Features

- Login/Register Page
- Guarded/Public Routes
- Sign In with Github
- Styling with tailwindcss, transition animation with @headlessui/react

## Includes

- [axios](https://www.npmjs.com/package/axios)
- [craco](https://www.npmjs.com/package/@craco/craco)
- [postcss](https://www.npmjs.com/package/postcss)
- [autoprefixer](https://www.npmjs.com/package/autoprefixer)
- [tailwindcss](https://www.npmjs.com/package/tailwindcss)
- [@tailwindcss/forms](https://www.npmjs.com/package/@tailwindcss/forms)
- [@tailwindcss/postcss7-compat](https://www.npmjs.com/package/@tailwindcss/postcss7-compat)
- [@headlessui/react](https://www.npmjs.com/package/@headlessui/react)
- [redux](https://www.npmjs.com/package/reduxt)
- [react-redux](https://www.npmjs.com/package/react-redux)
- [redux-persist](https://www.npmjs.com/package/redux-persist)
- [redux-thunk](https://www.npmjs.com/package/redux-thunk)
- [react-router-dom](https://www.npmjs.com/package/react-router-dom)

## Testing Locally

```
npx create-react-app . --template file:../path/to/your/template/cra-template-[template-name]
```
