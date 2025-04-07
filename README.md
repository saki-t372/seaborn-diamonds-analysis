# ダイヤモンド価格の予測 - 回帰モデルによる分析プロジェクト

本プロジェクトでは、Seabornのdiamondsデータセットを用いて、データの前処理と回帰モデルでの価格予測を行いました。

---

## プロジェクト概要

- 使用データ：Seabornの`diamonds`データセット
- 使用言語：Python
- モデル手法：LinearRegression, Lasso, Ridge, ElasticNet, XGBoost, LightGBM, RandomForest

---

## 分析の流れ

1. **データの理解と可視化**  
   - 統計データの確認
   - 目的変数（price）と説明変数の関係を可視化
   - 説明変数の分布確認

2. **前処理**
   - 異常値の検出と除外
   - 特徴量エンジニアリング（カテゴリカルデータのエンコーディング、新たな特徴量の検討、不要な特徴量の削除）

3. **モデル構築と評価**
   - 線形回帰モデルの作成と精度評価
   - 非線形回帰モデルの作成と精度評価
   - 線型回帰モデルと非線形回帰モデルの精度比較

---

## 📁 ファイル構成

```
📂 seaborn-diamonds-analysis
├── seaborn-diamonds-analysis.ipynb
└── README.md
└── requirements.txt
```

---

## 工夫ポイント

- 相関係数の分析による特徴量選択
- 過学習防止のため、変数数の調整と外れ値処理
- 視覚的にわかりやすいEDA（可視化多数）

---

## 実行環境

- Python 3.11.11
- pandas / seaborn / matplotlib / scikit-learn など

必要パッケージは`requirements.txt`に記載しています。

```bash
pip install -r requirements.txt
```

---

## 関連リンク
以下の記事で分析プロセスの詳細を説明しています。

- [note記事（詳細解説）](https://note.com/nagi8851/n/n5ffc47f66441)

