# TypeScriptを使用したプロジェクトの環境
コミット時にESLintとPrettierが走るTypeScript環境

## Overview
`git commit`すると、huskyのhooksでlint-stagedを呼び出します。  
lint-stagedを使用して、ESLintとPrettierを呼び出します。

## Usage
```zsh
git clone git@github.com:masanari9256/build-env-TS.git
cd build-env-TS
npm install
```

## Requirement
- npm 8.1.2
- TypeScript 4.5.4
- ESLint 8.5.0
- Prettier 2.5.1
- husky 7.0.4

その他パッケージについては、`package-lock.json`を確認してください

## Note
必要に応じてパッケージをアップデートしてください。    
パッケージ確認方法は、
```
npm outdated
```

## Author
- name  
Masanari Michiya
- email  
masanari92562@gmail.com
- SNS  
[Twitter](https://twitter.com/log_masa)  
[Qiita](https://qiita.com/masanari9256)  
[Instagram](https://www.instagram.com/masanari9256/)

## References
- YouTube  
https://youtu.be/R35LJL6a-p0
- 公式ドキュメント  
https://typicode.github.io/husky/#/?id=install
- Zenn  
https://zenn.dev/luvmini511/articles/a47b1aa0310d1a
https://zenn.dev/seya/articles/c908d88df0a587
