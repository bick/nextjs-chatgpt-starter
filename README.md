# Next.js ChatGPT Starter

The all-in-one starter kit for high-performance ChatGPT applications.

## Features

- **ChatGPT** - ChatGPT is a state-of-the-art conversational AI model.

## Demo

- https://nextjs-chatgpt-starter.vercel.app/

[![Screenshot of demo](./public/demo.png)](https://subscription-payments.vercel.app/)

## Architecture

![Architecture diagram](./public/architecture_diagram.svg)

## Step-by-step setup

When deploying this template, the sequence of steps is important. Follow the steps below in order to get up and running.

### Initiate Deployment

#### Vercel Deploy Button

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fvercel%2Fnextjs-subscription-payments&env=NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY,STRIPE_SECRET_KEY&envDescription=Enter%20your%20Stripe%20API%20keys.&envLink=https%3A%2F%2Fdashboard.stripe.com%2Fapikeys&project-name=nextjs-subscription-payments&repository-name=nextjs-subscription-payments&integration-ids=oac_VqOgBHqhEoFTPzGkPd7L0iH6&external-id=https%3A%2F%2Fgithub.com%2Fvercel%2Fnextjs-subscription-payments%2Ftree%2Fmain)

### Configure OpenAI ChatGPT

In your `.env.local` file, add your OpenAI API key as `OPENAI_API_KEY`.

#### [Optional] - Set up redirect wildcards for deploy previews (not needed if you installed via the Deploy Button)

If you've deployed this template via the "Deploy to Vercel" button above, you can skip this step. The Supabase Vercel Integration will have set redirect wildcards for you. You can check this by going to your Supabase [auth settings](https://app.supabase.com/project/_/auth/url-configuration) and you should see a list of redirects under "Redirect URLs".
