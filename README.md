# 🐶 Chopped Pet-Store API 🐱

This API is created following from the official example API provided by swagger, splitting it into multiple files

## 📖 Table of Contents

- [🐶 Chopped Pet-Store API 🐱](#-chopped-pet-store-api-)
  - [📖 Table of Contents](#-table-of-contents)
  - [Getting Started](#getting-started)

## Getting Started

To render this api, you need `@openapitools/swagger-cli`

```bash
npm install @openapitools/swagger-cli -g
```

then bundle the api using the folowing command

```bash
swaagger-cli bundle --outfile=bundle.yaml --type=yaml openapi.yaml
```

A `bundle.yaml`  file will be compiled folowing the splitted definition
