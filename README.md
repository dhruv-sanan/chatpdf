# ChatPDF

Chat with your PDFs — built with Next.js, Pinecone (vector search), OpenAI, Prisma, Kinde auth, and Stripe billing.

## Stack

Next.js, tRPC, Prisma, Kinde Auth, Pinecone, OpenAI, Stripe.

## Getting Started

```bash
git clone https://github.com/dhruv-sanan/chatpdf.git
cd chatpdf
npm install
```

Create a `.env` file in the project root:

```
DATABASE_URL=
OPENAI_API_KEY=
PINECONE_API_KEY=
PINECONE_ENVIRONMENT=
STRIPE_SECRET_KEY=
STRIPE_WEBHOOK_SECRET=
KINDE_CLIENT_ID=
KINDE_CLIENT_SECRET=
KINDE_ISSUER_URL=
KINDE_SITE_URL=http://localhost:3000
KINDE_POST_LOGOUT_REDIRECT_URL=http://localhost:3000
KINDE_POST_LOGIN_REDIRECT_URL=http://localhost:3000
```

Then:

```bash
npx prisma generate
npx prisma db push
npm run dev
```

Open [http://localhost:3000](http://localhost:3000).

## Scripts

- `npm run dev` — start dev server
- `npm run build` — production build
- `npm run start` — run production build
