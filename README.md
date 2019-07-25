# Practice Testing for Python

テストとは？
- APIの品質を定義付けるもの
- 要件を満たすための根拠

テストのフェーズ
- APIを構成する個々のメソッド/モジュールに対するテスト（単体テスト/UT）
- APIのテスト（結合テスト/IT）
- 運用のテスト（統合テスト/総合テスト/システムテスト/EtoE/ST）
- 機能テスト
- 受入のテスト（RT）
- リリース後の継続的なテスト

テストエンジニアとQAエンジニア
- 各テストフェーズでの実行部隊
- テストエンジニアのカバレッジはUT/IT/ST/RT
    - APIが動くことを担保とするテストの実装
- QAエンジニアのカバレッジはリリース後の継続的テスト
    - 成果ログの確認
    - KPI/KGI/OKRを満たす品質か否かの確認
    - 計測ツールの開発
    - API更改のためのプランニングと実行

当プロジェクトの立ち位置
- テストエンジニアが実施するべくUT/ITの技法を習得
- pytestのベストプラクティスの追求

Pytestモジュールについて
- Pythonのソフトウェアフレームワーク
- テストの自動検出
- テストの結果報告
- CIやWebオートメーションとの統合
- unittestまたはnoseで書かれたテストも実行可能

テスト戦略
- UT
- IT
- システムテスト（EndToEnd）
- 機能テスト

Pytestの一般的な挙動
```
# 引数なしの場合はすべてのディレクトリのテストが走る
$ pytest

# 単純なテスト実行
$ pytest ch1/test_one.py

# 詳細なテスト実行
$ pytest -v ch1/test_one.py
```

Pytestのベストプラクティス
- pass

Pytestの利用頻度高のコマンドラインオプション
- pass

Pytestのテスト関数
- pass

セットアップコード
- フィクスチャ
    - セットアップセクション
    - ティアダウンセクション
    - スーパーチャージ

参考文献
- [テスト駆動Python](https://www.shoeisha.co.jp/book/detail/9784798157603)




 

