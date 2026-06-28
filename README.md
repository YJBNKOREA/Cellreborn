# CELLREBORN Global Brand Hub

Global K-haircare brand hub for CELLREBORN by YJBN Co., Ltd.

This repository contains a GitHub-ready static implementation of the CELLREBORN global brand hub. It connects B2C shoppers to official country stores and routes B2B buyers to distributor, salon, catalog, OEM/ODM, and inquiry paths.

## Core Features

- Global homepage with B2C and B2B entry points
- Country/store routing from `config/storeLinks.json`
- Language and country selection kept independent in browser storage
- Eight product collection sections
- Authorized sales channel rendering from central store data
- B2B inquiry form that prepares a routed email to HQ
- Brand science, professional salon, OEM/ODM, and YJBN connection blocks

## Link Management

All country shopping links are managed in:

```text
config/storeLinks.json
```

Header, footer, country selector, channel cards, hero CTAs, and shopping CTAs read from this single source. To change China, USA, Japan, Korea, or future market channels, update the JSON data instead of editing UI code.

## Local Preview

Open `index.html` through a local web server so the page can fetch `config/storeLinks.json`.

```bash
python -m http.server 8080
```

Then visit:

```text
http://localhost:8080/
```

## Contact

B2B inquiry routing defaults to `9chana@cellreborn.co.kr`.
