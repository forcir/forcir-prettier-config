<p align="center"></p>
<div align="center">
    <picture>
        <source media="(prefers-color-scheme: dark)" srcset="https://cdn.forcir.com/oss/forcir-prettier-config/assets/images/logos/dark.png?0">
        <img alt="Forcir Prettier Config" src="https://cdn.forcir.com/oss/forcir-prettier-config/assets/images/logos/light.png?0">
    </picture>
</div>
<p align="center"><strong>Shared configuration for a consistent experience using Prettier.</strong></p>
<p align="center"></p>

## Install

```bash
pnpm add -DE prettier @forcir/prettier-config
```

```bash
yarn add -DE prettier @forcir/prettier-config
```

```bash
npm install -DE prettier @forcir/prettier-config
```

## Basic Usage

### package.json (recommended)

```jsonc
{
  // ...
  "prettier": "@forcir/prettier-config",
  // ...
  "scripts": {
    // ...
    "format": "prettier --write \"**/*.{js,json,md,ts,tsx}\""
    // ...
  }
}
```
