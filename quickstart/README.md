<!-- /* cspell:locale en */ -->
<!-- LTeX: language=en-US-->
# API test

# Description

API testing guidelines recommended by ChatGPT, with corrections from the OpenAI documentation.

## Install requirements

```bash
npm init -y
npm install openai
```

## Create files

**Note:** `.env` contains the API private key, keep it secret!

```bash
touch prompt_openai.mjs
touch .env
```

## Run

```bash
node --env-file .env prompt_openai.mjs
```