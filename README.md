# DevLinker

> Social network for developers

This is a MERN stack application. It is a small social network app that includes authentication, profiles and forum posts.

Deployed : [here](https://stark-sierra-08936.herokuapp.com/) 

### Functionality
- Sign up and sign in
- Publicly available:
  - List of all registered developers
  - Profiles of each developer
- Privately available:
  - Personal dashboard (experiences and education)
  - Edit profile view
  - Adding and Deleting experience
  - Adding and Deleting education
  - Deleting an account
  - Posts
    - Add and Delete the post
    - Like and Lislike the post
    - Add and Delete Comment on the post

### Add a default.json file in config folder with the following

```
{
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubToken": "<yoursecrectaccesstoken>"
}
```

### Install server dependencies

```bash
npm install
```

### Install client dependencies

```bash
cd client
npm install
```

### Run both Express & React from root

```bash
npm run dev
```

### Build for production

```bash
cd client
npm run build
```
