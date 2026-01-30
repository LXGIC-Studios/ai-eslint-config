# ai-eslint-config

[![npm version](https://img.shields.io/npm/v/ai-eslint-config.svg)](https://www.npmjs.com/package/ai-eslint-config)
[![npm downloads](https://img.shields.io/npm/dm/ai-eslint-config.svg)](https://www.npmjs.com/package/ai-eslint-config)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-eslint-config)](https://github.com/lxgic-studios/ai-eslint-config/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Generate an ESLint config that matches your codebase's existing style. No more arguing about semicolons.

## Install

```bash
npm install -g ai-eslint-config
```

## Usage

```bash
npx ai-eslint-config
# → ESLint config written to eslint.config.js

npx ai-eslint-config --format json
# → Generates .eslintrc.json instead

npx ai-eslint-config --dir ./src
# → Only analyze files in ./src
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## License

MIT
