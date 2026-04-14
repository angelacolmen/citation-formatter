# Citation Formatter

An AI-powered citation formatter built with Claude. Paste any messy, incomplete, or incorrectly formatted citation and get it back clean in your preferred style.

## Features

- Supports **APA 7th**, **MLA 9th**, **Chicago 17th**, **Harvard**, and **Vancouver** styles
- Handles partial, malformed, or informal citations
- Surfaces notes when assumptions were made (e.g. missing publisher, unknown year)
- One-click copy of the formatted result
- API key stored locally in your browser — never hardcoded, safe to use publicly

## Demo

🤗 [Live on HuggingFace Spaces](https://huggingface.co/spaces/AngelaColmen/citation-formatter)

## How to Use

1. Open `index.html` in your browser (or visit the live demo)
2. Click the 🔑 API key section and paste your [Anthropic API key](https://console.anthropic.com)
3. Paste any citation into the text box — as messy as you like
4. Select a citation style
5. Click **Format citation**

Your API key is saved to `localStorage` in your browser only and is never stored in the code or transmitted anywhere other than Anthropic's API.

## Example Inputs

The formatter handles a wide range of messy inputs:

```
smith j 2019 attachment theory new york basic books
```
```
Harari, Y, Sapiens, a brief history, vintage, 2014
```
```
https://doi.org/10.1038/s41586-021-03819-2
```

## Tech Stack

- Vanilla HTML, CSS, JavaScript — no frameworks, no build step
- [Claude](https://anthropic.com) (claude-sonnet-4) via the Anthropic API

## Setup for Local Development

No installation needed. Just open `index.html` in any modern browser.

To run via a local server (optional):

```bash
npx serve .
```

## Related Projects

- [Semantic Library Search](https://github.com/angelacolmen/semantic-library-search)
- [Subject Heading Generator](https://github.com/angelacolmen/subject-heading-generator)

## License

MIT
