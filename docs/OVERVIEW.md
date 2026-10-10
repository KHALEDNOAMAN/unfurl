# Unfurl - Overview

## What It Does
A JavaScript utility for URL unfurling and metadata extraction.

## Features
| Feature | Description |
|---------|-------------|
| URL Preview | Extract title, description, image |
| OpenGraph | Parse OG meta tags |
| Twitter Cards | Parse Twitter card metadata |
| Favicon | Extract site favicon |

## Usage
```javascript
const { unfurl } = require("unfurl");

const metadata = await unfurl("https://github.com");
console.log(metadata.title);
console.log(metadata.description);
console.log(metadata.image);
```

## Use Cases
- Link previews in chat applications
- Social media sharing cards
- SEO analysis tools
- Content aggregation