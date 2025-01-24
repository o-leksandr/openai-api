<!-- markdownlint-disable MD033 MD041 -->
<!-- /* cspell:locale en */ -->
<!-- LTeX: language=en-US-->

<!-- source: https://raw.githubusercontent.com/r-lyeh-archived/AVA/refs/heads/master/README.md -->
<p align="left">
<br/>
<a href="http://unlicense.org/"><img alt="Unlicensed" src="https://img.shields.io/badge/license-Unlicense-blue.svg?style=plastic"/></a>
<br/>
</p>

# API test

API testing guidelines based on the ChatGPT recommendations and the OpenAI documentation.

## How to use

### Install requirements

```bash
npm init -y
npm install openai
```

### Create files

**Note:** `.env` contains the API private key, keep it secret!

```bash
touch prompt_openai.mjs
touch .env
```

### Run

```bash
node --env-file .env prompt_openai.mjs
```

## References

- [How to integrate OpenAI into the VS Code workspace to prompting from the command line?](../docs/guide.md)

## Contributing

If you find a bug or want to add content, please make changes. You can use the `Edit file` button in the top right corner of any article to add them in a pull request, if you don't know what that means, you can always open an [issue](https://github.com/o-leksandr/markdown-resume-template/issues/new).

## License

The project is released into the public domain (as per [this notice](LICENSE)).<br/>
Any contribution to this repository is implicitly subjected to the same release conditions.