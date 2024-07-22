<a href="https://nextjs-chat-ai-general-purpose.vercel.app">
  <h1 align="center">Role Play AI Chatbot</h1>
</a>

<p align="center">
  An open-source general purpose role play AI chatbot app template built with Next.js, the Vercel AI SDK, OpenAI, and Vercel KV.
</p>

<br/>

## Tech Stack

- [Next.js](https://nextjs.org) App Router
- React Server Components (RSCs), Suspense, and Server Actions
- [Vercel AI SDK](https://sdk.vercel.ai/docs) for streaming chat UI
- Support for OpenAI (default), Anthropic, Cohere, Hugging Face, or custom AI chat models and/or LangChain
- [shadcn/ui](https://ui.shadcn.com)
  - Styling with [Tailwind CSS](https://tailwindcss.com)
  - [Radix UI](https://radix-ui.com) for headless component primitives
  - Icons from [Phosphor Icons](https://phosphoricons.com)
- Chat History, rate limiting, and session storage with [Vercel KV](https://vercel.com/storage/kv)
- [NextAuth.js](https://github.com/nextauthjs/next-auth) for authentication

## Model Providers

This template ships with OpenAI `gpt-3.5-turbo` as the default.

## Running locally

You will need to use the environment variables [defined in `.env.example`](.env.example) to run the AI Chatbot.You can create a `.env` file and copy paste `.env.example` and update the necessary values.

> Note: You should not commit your `.env` file or it will expose secrets that will allow others to control access to your various OpenAI and authentication provider accounts.

```bash
pnpm install
pnpm dev
```

Your app template should now be running on [localhost:3000](http://localhost:3000/).