# markdown linter

![python](https://img.shields.io/github/pipenv/locked/python-version/yuto51942/markdown-linter)
![reposize](https://img.shields.io/github/repo-size/yuto51942/markdown-linter)
![lastcommit](https://img.shields.io/github/last-commit/yuto51942/markdown-linter)
![github](https://img.shields.io/github/followers/yuto51942?label=FollowMe&style=social)
![twitter](https://img.shields.io/twitter/follow/cateiru?style=social)

language: [🇯🇵](README.md)   [🇺🇸](docs/README_en.md)

Markdownを静的解析し、自動的に整形をします。

## 使い方

### そのまま使用

```shell
# インストール
pip install git+https://github.com/yuto51942/markdown-lint

# 起動
# - ディレクトリを指定→そのディレクトリ内の`.md`ファイルを全て変換
# - `.md`ファイルのパスを指定→そのファイルを変換
md-lint
```

### Pythonライブラリとして使用

```shell
# インストール
pip install git+https://github.com/yuto51942/markdown-lint
```

[詳しい使い方(日本語)](docs/library_doc.md)
