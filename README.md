<<<<<<< HEAD
# ChatGPT Lite

English | [简体中文](./README.zh-CN.md)

ChatGPT Lite is a fast ChatGPT UI application developed using Next.js. It supports both OpenAI and Azure OpenAI accounts.

Example use cases for GPT Lite include:

- A cost-effective alternative to ChatGPT's free version or Plus subscription ($20/month) by deploying a custom webchat UI with API integration.
- Deploying a custom ChatGPT web app to explore OpenAI's ChatGPT completion API and prompting capabilities.
- Creating a private web-based ChatGPT for exclusive use among friends without sharing an API key.
- A high-quality code base that serves as an excellent starting point for your next AI Next.js project.

Visit [ChatGPT Minimal](https://github.com/blrchen/chatgpt-minimal) for a beginner-friendly version of the ChatGPT UI code base.

[Live Demo](https://gptlite.vercel.app)
![demo](./docs/images/demo.jpg)

## Prerequisites

You'll need either an OpenAI account or an Azure OpenAI account.

## Running Locally

1. Install NodeJS 18.
2. Clone the repository.
3. Install dependencies with `npm install`.
4. Copy `.env.example` file to `.env.local` and update environment variables.
5. Start the application using `npm run dev`.
6. Visit `http://localhost:3000` in your browser.

## Run with Docker

1. Clone the repository and navigate to the root directory.
2. Update the `OPENAI_API_KEY` environment variable in the `docker-compose.yml` file.
3. Build the application using `docker-compose build .`.
4. Start it by running `docker-compose up -d`.

## One-click Deploy on Vercel

Click the button below to deploy to Vercel:
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fblrchen%2Fchatgpt-lite&project-name=chatgpt-lite&framework=nextjs&repository-name=chatgpt-lite)

## Environment Variables

You will need to use the environment variables defined in [`.env.example`](.env.example) to run the application. Below is an explanation of each environment variable:

For OpenAI-specific environments:

| Name                | Description                                                                                            | Default Value            |
| ------------------- | ------------------------------------------------------------------------------------------------------ | ------------------------ |
| OPENAI_API_BASE_URL | Use only if you intend to use a reserved proxy for `api.openai.com`.                                   | `https://api.openai.com` |
| OPENAI_API_KEY      | Obtain secret key string from the [Open AI API website](https://platform.openai.com/account/api-keys). |

For Azure Open AI-specific environments:

| Name                      | Description                                    |
| ------------------------- | ---------------------------------------------- |
| AZURE_OPENAI_API_BASE_URL | Endpoint (e.g., https://xxx.openai.azure.com). |
| AZURE_OPENAI_API_KEY      | Key                                            |
| AZURE_OPENAI_DEPLOYMENT   | Model deployment name                          |

## Contribution

We welcome PRs of any size.

## Disclaimers

This code is intended solely for demonstration and testing purposes.
=======
# mastergpt-ui
>>>>>>> be5e8d8d9a29a6ec3a6a4cf8aad9f46846296d31
