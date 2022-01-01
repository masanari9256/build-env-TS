# TypeScriptを使用したプロジェクトの環境

## Overview
コミット時にESLintとPrettierが走るTypeScript環境  
`git commit`すると、huskyのhooksでlint-stagedを呼び出します。
lint-stagedを使用して、ESLintとPrettierを呼び出します。

## Usage
```zsh
git clone git@github.com:masanari9256/build-env-TS.git
cd build-env-TS
npm install
```

## Requirement
npm 8.1.2

## Note
必要に応じてパッケージをアップデートしてください  
