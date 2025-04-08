# ダイヤモンド価格の予測 - 回帰モデルによる分析プロジェクト

本プロジェクトでは、Seabornの`diamonds`データセットを用いて、データの前処理と回帰モデルでの価格予測を行いました。

---

## プロジェクト概要

- 使用データ：Seabornの`diamonds`データセット
- 使用言語：Python
- モデル手法：
   - 線形回帰（Linear Regression）
   - ラッソ回帰（Lasso）
   - リッジ回帰（Ridge）
   - ElasticNet
   - XGBoost
   - LightGBM
   - ランダムフォレスト（Random Forest）

---

## 分析の流れ

1. **データの理解と可視化**  
   - 統計データの確認
   - 目的変数（price）と説明変数の関係を可視化
   - 説明変数の分布確認

2. **前処理**
   - 異常値の特定と除外
   - 特徴量エンジニアリング（カテゴリカルデータのエンコーディング、新たな特徴量の検討、不要な特徴量の削除）

3. **モデル構築と評価**
   - 線形回帰モデルの作成と精度評価
   - 非線形回帰モデルの作成と精度評価
   - 線型回帰モデルと非線形回帰モデルの精度比較

---

## ファイル構成

```
📂 seaborn-diamonds-analysis
├── seaborn-diamonds-analysis.ipynb
├── README.md
└── requirements.txt
```

---

## 工夫ポイント

- 過学習を防ぐために、外れ値/異常値の確認や特徴量の選択を行った
- 相関関係や特徴量の分布の確認で可視化を多数取り入れ、視覚的にわかりやすいEDAを行った

---

## 実行環境

- Python 3.11.11（Google Colaboratoryにて実行）
- pandas / seaborn / matplotlib / scikit-learn など

必要パッケージは`requirements.txt`に記載しています。

```bash
pip install -r requirements.txt
```

---

## 関連リンク
以下の記事で分析プロセスの詳細を説明しています。

- [note記事](https://note.com/nagi8851/n/n5ffc47f66441)

