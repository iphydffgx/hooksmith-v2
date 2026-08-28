# hooksmith-v2

A handful of React hooks I keep copy-pasting between projects

Built for my own use; public in case it helps someone.

## Usage

```bash
import { useDebounce, useLocalStorage } from './src';

const debounced = useDebounce(value, 300);
```

## Features

- Tiny: no dependencies besides React
- useMediaQuery SSR-safe
- useDebounce with leading/trailing options
- useLocalStorage with JSON serialization

## Install

```bash
npm install
npm test
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── faq.md
│   └── usage.md
├── scripts/
│   └── dev.sh
├── src/
│   ├── config.js
│   ├── index.js
│   ├── useDebounce.js
│   └── useLocalStorage.js
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
└── package.json
```

## License

MIT. Do whatever you want.
