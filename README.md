# Chatbase

Realtime chat using GraphQL Live Queries, Next.js and NextAuth.js 
## Tools used

- NextAuth.js
- Next.js
- Apollo Client
- Grafbase
- Server-Sent Events
- GraphQL Live Queries
- GraphQL
- Tailwind CSS

## Local Development

1. `npm install`
2. Create a [GitHub OAuth App] with your app details for development purposes. Make sure to set `Authorization callback URL` to `http://localhost:3000/api/auth/callback/github`
3. `cp .env.example .env` and add values for `GITHUB_CLIENT_ID` and `GITHUB_CLIENT_SECRET` from step 2.
4. [Generate a secret value] for `NEXTAUTH_SECRET` and add it to `.env`
5. `cp grafbase/.env.example grafbase/.env`
6. Add the same `NEXTAUTH_SECRET` to `grafbase/.env`
7. `npx grafbase dev`
8. `npm run dev`


