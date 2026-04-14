# Citation Formatter

An AI-powered citation formatter built with Claude. Paste any messy, incomplete, or incorrectly formatted citation and get it back clean in your preferred style.

## Features

- Supports **APA 7th**, **MLA 9th**, **Chicago 17th**, **Harvard**, and **Vancouver** styles
- Handles partial, malformed, or informal citations
- Surfaces notes when assumptions were made (e.g. missing publisher, unknown year)
- One-click copy of the formatted result
- API key stored locally in your browser — never hardcoded, safe to use publicly

## Demo

🤗 [Live on HuggingFace Spaces](https://huggingface.co/spaces/angelacolmen/citation-formatter) 

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
