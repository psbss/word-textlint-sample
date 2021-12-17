# Word textlint sample
MS WordをMarkdown形式に変換してGitで管理しつつ、プルリクエスト（PR）作成時にTextlintを実行するサンプルリポジトリです。

## Git Clone

```bash
git clone git@github.com:psbss/word-textlint-sample.git
```

## Usage
Wordファイルをマークダウンに変換する(GitHub markdown style)

```bash
sh ./docx2md.sh
```

Wordファイルをマークダウンに変換してGit RemoteにPushする

```bash
sh ./docx2md.sh push
```

## License
This repo licensed under MIT.

自由に利用してください（但し .docx / .md ファイルを除く）
