# 広告ゲーム（ピン抜き）

## 実行環境の必要条件
* python >= 3.10
* pygame >= 2.1

## ゲームの概要
主人公に向けて宝物のみが落ちてくるようにピンを正しく抜いてクリアするゲーム

## ゲームの実装
### 共通基本機能
* 背景画像と主人公キャラクター、ステージとなる場所の描画

### 担当追加機能
* スタート画面　（担当：小室）
* ピンとステージの当たり判定（抜く行為） （担当：熊倉）
* 物体の落下　（担当：小林）
* リセット機能（マグマとの接触）　（担当：齋藤）
* クリア画面　（担当：大竹）

### ToDo
- [ ] ほげほげ機能
- [ ] ふがふが関数内の変数名の統一

### メモ
* クラス内の変数は，すべて，「get_変数名」という名前のメソッドを介してアクセスするように設計してある
* すべてのクラスに関係する関数は，クラスの外で定義してある