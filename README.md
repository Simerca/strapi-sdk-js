[![strapi-sdk-js](https://strapi-sdk-js.netlify.app/preview-light.png)](https://strapi-sdk-js.netlify.app)

# Rewrite of Strapi SDK

![Actions](https://github.com/Stun3R/strapi-sdk/actions/workflows/main.yml/badge.svg)
[![Codecov][codecov-src]][codecov-href]
[![License][license-src]][license-href]

### Why ?

The first version does not suit me anymore in relation to the skills I had and the time I had to develop it. The project lacks readability, the code is not very clean (everything in one file). This project needs to be made more professional, the doc is not clear either and some features are missing.

### Main goal of this SDK

- A Typescript project that supports httpOnly, GraphQL & does not have a greedy & heavy HTTP client
- It must handle basic methods as well as CRUD, authentication & file upload
- If possible a CLI that allows to generate GraphQL types/mutations found on the user's Strapi project

### Todo ?

- [x]  Start from scratch
- [x]  Add project management package: Siroc, Commitlint, Jest, Eslint/Prettier, Release-it, Commitizen,
- [ ]  Add better **Typescript support** → Templates methods, Responses types, Interfaces
- [ ]  Remove **verbose mode** → Now we can use the Treeshaking for the HttpClient's response
- [ ]  **httpOnly support** → Set boolean in config to enable/disable token methods
- **Methods**
    - [ ]  CRUD → find, findOne, create, update, delete
    - [ ]  Auth → login, register, forgot, reset, sendEmailConfirmation, getProviderAuthUrl,  AuthenticateProvider, logout
    - [ ]  User Object
    - [ ]  Token
    - [ ]  Upload

## License

[MIT License](./LICENSE)

<!-- Badges -->
[codecov-src]: https://img.shields.io/codecov/c/github/Stun3R/strapi-sdk.svg?style=flat-square
[codecov-href]: https://codecov.io/gh/Stun3R/strapi-sdk

