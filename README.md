# ai-diff-summary

[![npm version](https://img.shields.io/npm/v/ai-diff-summary.svg)](https://www.npmjs.com/package/ai-diff-summary)
[![npm downloads](https://img.shields.io/npm/dm/ai-diff-summary.svg)](https://www.npmjs.com/package/ai-diff-summary)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-diff-summary)](https://github.com/lxgic-studios/ai-diff-summary/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Get a human-readable summary of your git changes. No more squinting at raw diffs.

## Install

```bash
npm install -g ai-diff-summary
```

## Usage

```bash
npx ai-diff-summary           # summarize uncommitted changes
npx ai-diff-summary HEAD~3    # summarize last 3 commits
npx ai-diff-summary main      # summarize changes vs main
```

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## License

MIT
