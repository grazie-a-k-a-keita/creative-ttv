## CreAtiveTTV

![deploy workflow](https://github.com/grazie-a-k-a-keita/creative-ttv/actions/workflows/deploy.yml/badge.svg)

入力されたテキストを音声として出力するサービス

※ TTVとは、 `Text to Voice` の略

### Web Speech API

- [Web_Speech_API](https://developer.mozilla.org/ja/docs/Web/API/Web_Speech_API)
- [SpeechSynthesisUtterance](https://developer.mozilla.org/ja/docs/Web/API/)

### commit message

| TH       | TH                                     |
| -------- | -------------------------------------- |
| feat     | 新しい機能                             |
| fix      | バグの修正                             |
| docs     | ドキュメントのみの変更                 |
| style    | 空白、フォーマット、セミコロン追加など |
| refactor | 仕様に影響がないコード改善(リファクタ) |
| perf     | パフォーマンス向上関連                 |
| test     | テスト関連                             |
| chore    | ビルド、補助ツール、ライブラリ関連     |

### Domain

- [grazie-a-k-a-keita.github.io/creative-ttv/](https://grazie-a-k-a-keita.github.io/creative-ttv/)

### Other

- コミット時に husky でエラーが出る場合

```bash
# fatal: cannot exec '.husky/pre-commit': Permission denied

chmod +x .husky/pre-commit
```
