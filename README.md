# NextJS Website Template
#### NextJS      
#### Authjs.dev
#### MongoDB
#### bycrypt
#### TailwindCSS
#### TypeScript
#### Mongoose




## Required Environment Variables
API_SERVER_BASE_URL="http://localhost:3000"

AUTH_SECRET="anything"

GITHUB_CLIENT_ID=

GITHUB_CLIENT_SECRET=


Sign to Google Cloud Console and create a new project
https://console.cloud.google.com/apis/credentials

GOOGLE_CLIENT_ID=

GOOGLE_CLIENT_SECRET=

# For MONGO_DB_CONNECTION_STRING, make sure to create different project in MONGO_DB to avoid confusions
https://cloud.mongodb.com/

MONGO_DB_CONNECTION_STRING=

In MONGODB, after creation of new Project,
Update the Network Access and 
add IP Address and allow anywhere
Build a Cluster
Choose M0 FREE
Name your Cluster like "ClusterPortfolio"
Generate cluster credentials and copy
Initiate connection method
Choose "Drivers"

Name your database related to your project in path 
## src/mongo.ts dbName

## To start a website with 3rd Part Login,
## Clone ME!



Before deployment, make sure to change the OAuth settings for the providers
such us, 
- Callbacks



This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
