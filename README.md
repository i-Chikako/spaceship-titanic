# Spaceship Titanic - Kaggleコンペティション

このリポジトリは、Kaggleの「Spaceship Titanic」分類コンペティションに取り組んだ内容をまとめたものです。
(https://www.kaggle.com/competitions/spaceship-titanic)

## 🏆 結果
- 最終順位：2,050チーム中 156位　上位8％（リーダーボード、2025年5月24日時点）
- 使用モデル：スタッキング（ベースモデル：LGBMClassifier + XGBoost + CatBoost　メタモデル：LogisticRegression）
- 評価指標：Accuracy（正解率）
- 最終スコア：0.80710

## 📄 概要
宇宙船の事故により別次元に転送された乗客を年齢・出身惑星・支出データなどの特徴量から、別次元に転送されたかどうかを予測する分類問題に取り組みました。

## 💻 開発環境
- Python 3.12.3
- Jupyter Notebook
- scikit-learn 1.6.1
- XGBoost 3.0.0
- LightGBM 4.6.0
- CatBoost 1.2.8
- pandas 2.2.2
- numpy  1.26.4

## 🔍 アプローチ
- 特徴量エンジニアリング（欠損値の処理、特徴量の組み合わせなど）
- クロスバリデーションを用いたモデル学習
- スタッキングによる性能向上

## 📁 ファイル構成
- `SpaceshipTitanic.ipynb`: 整理された最終モデル

## 📝 補足
このコンペティションでは、分類問題の実践・特徴量エンジニアリング・スタッキングの練習として非常に有意義でした。
今回、スタッキングすることにより予測精度が上がることを学びました。
今後ほかのモデルや特徴量エンジニアリングの方法についての知識を増やしていきたいと思います。
