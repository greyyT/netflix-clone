# Netflix Clone

> _A fullstack app clone main functionalities of Netflix._

<p align='center'>
<img width=100 src="https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/227_Netflix_logo-512.png">
</p>

## Overview

<p align="justify">
The main goal of this project is to create a fullstack app clone main functionalities of Netflix. Using NextJS 13.4 and pages router, the app recreates the Netflix interface and functionalities. However, this app only have some movies for test purposes. The app is responsive and can be used on mobile devices.
</p>

Check out the [deployment](https://greyyt-netflix-clone.vercel.app/auth) by Vercel.

## Installation

To run this project locally, follow these steps:

1. Clone this repository

```sh
git clone git@github.com:greyyT/netflix-clone.git
cd netflix-clone
```

2. Install dependencies

```sh
npm install
```

3. Create a `.env` file in the root directory of the project and add the following environment variables:

```sh
DATABASE_URL=YOUR_DATABASE_URL # for example: postgres://postgres:postgres@localhost:5432/netflix
NEXTAUTH_JWT_SECRET=YOUR_JWT_SECRET
NEXTAUTH_SECRET=YOUR_NEXTAUTH_SECRET

# The following variables are for authentication with Google and Github. You can get them from the following links:
# https://docs.github.com/en/developers/apps/building-oauth-apps/creating-an-oauth-app
# https://developers.google.com/identity/protocols/oauth2
GITHUB_ID=YOUR_GITHUB_ID
GITHUB_SECRET=YOUR_GITHUB_SECRET

GOOGLE_CLIENT_ID=YOUR_GOOGLE_CLIENT_ID
GOOGLE_CLIENT_SECRET=YOUR_GOOGLE_CLIENT_SECRET
```

4. Build the project

```sh
npm run build
```

5. Run the project

```sh
npm run start
```

For development purposes, you can run the following command:

```sh
npm run dev
```
