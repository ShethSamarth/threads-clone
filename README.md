# Threads Clone

This is a repository for MERN Threads Clone which includes an extra feature of communities: Next.js 13.4, React, TailwindCSS, ShadCN UI, MongoDB.

Key Features:

- Uploading and commenting on threads
- Creating and joining communities
- Image uploads with UploadThing
- Validatation of form data with Zod
- MongoDB database
- Credential authentication with Clerk
- Google authentication with Clerk
- Github authentication with Clerk
- Client form validation and handling using react-hook-form
- Tailwind design for sleek UI
- Tailwind animations and transition effects
- Full responsiveness for all devices

# Final Version

To visit the website, [click here.](https://threads-clone-ss.vercel.app)

### Cloning the repository

```shell
git clone https://github.com/ShethSamarth/threads-clone.git
```

### Install packages

```shell
npm install
```

### Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_CLERK_WEBHOOK_SECRET=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/onboarding
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

MONGODB_URL=

UPLOADTHING_SECRET=
UPLOADTHING_APP_ID=
```

### Start the app

```shell
npm run dev
```
