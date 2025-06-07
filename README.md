# 🔥 FIRE計算機 - 早期リタイア達成シミュレーター

## 概要

FIRE（Financial Independence, Retire Early）達成年齢を計算する高機能なWebアプリケーションです。インフレ率を考慮した実質資産の推移、モンテカルロシミュレーションによる成功確率の算出など、本格的な資産形成シミュレーションが可能です。

## 🌟 主な機能

### 基本機能
- **FIRE達成年齢の計算**: 4%ルールに基づく必要資産額の算出
- **資産推移グラフ**: 実質/名目資産の推移を可視化
- **インフレ対応**: インフレ率を考慮した実質的な資産価値を計算
- **モンテカルロシミュレーション**: 成功確率を統計的に算出

### ユーザー体験
- **ステップバイステップ入力**: 直感的な3ステップの入力フォーム
- **ダークモード対応**: 目に優しい表示切り替え
- **計算履歴保存**: 最大10件の計算履歴を自動保存
- **SNSシェア機能**: X（Twitter）、Facebook、LINEでの結果共有
- **友達と比較機能**: シェアした結果を友達と比較

### デザイン
- **モダンなUI**: グラデーション、アニメーション効果
- **レスポンシブ対応**: スマートフォン、タブレット、PCに最適化
- **アクセシビリティ**: WCAG準拠の設計

## 🚀 技術スタック

- **フロントエンド**: React 18
- **スタイリング**: Tailwind CSS
- **グラフ**: Recharts
- **アイコン**: Lucide React
- **ビルドツール**: Vite
- **デプロイ**: GitHub Pages

## 📦 セットアップ

### 開発環境の構築

```bash
# リポジトリをクローン
git clone https://github.com/appadaycreator/fire-calculator.git
cd fire-calculator

# 依存関係をインストール
npm install

# 開発サーバーを起動
npm run dev
```

### ビルド & デプロイ

```bash
# プロダクションビルド
npm run build

# GitHub Pagesへデプロイ
npm run deploy
```

## 📁 プロジェクト構造

```
fire-calculator/
├── src/
│   ├── App.jsx          # メインコンポーネント
│   ├── main.jsx         # エントリーポイント
│   └── index.css        # グローバルスタイル
├── public/
│   ├── index.html       # HTMLテンプレート
│   └── ogp.png         # OGP画像
├── package.json         # プロジェクト設定
├── vite.config.js       # Vite設定
├── tailwind.config.js   # Tailwind設定
├── robots.txt          # クローラー設定
└── sitemap.xml         # サイトマップ
```

## 🔧 カスタマイズ

### 計算パラメータの変更

`src/App.jsx`内の`fieldDefinitions`オブジェクトで、入力フィールドの範囲や初期値を変更できます：

```javascript
const fieldDefinitions = {
  currentAge: {
    label: "現在の年齢",
    min: 20,
    max: 70,
    // ...
  }
  // ...
}
```

### デザインテーマの変更

Tailwind CSSのクラスを編集することで、簡単にデザインをカスタマイズできます。

## 📊 アフィリエイト設定

アフィリエイトリンクは`src/App.jsx`内のアフィリエイトセクションで管理されています。実際のアフィリエイトリンクに置き換えてください。

## 🔍 SEO対策

- 適切なメタタグ設定
- 構造化データ（JSON-LD）
- サイトマップ（sitemap.xml）
- robots.txt

## 📱 ブラウザ対応

- Chrome (最新版)
- Firefox (最新版)
- Safari (最新版)
- Edge (最新版)
- モバイルブラウザ

## 🤝 貢献

プルリクエストや機能提案を歓迎します！

1. このリポジトリをフォーク
2. 機能ブランチを作成 (`git checkout -b feature/amazing-feature`)
3. 変更をコミット (`git commit -m 'Add amazing feature'`)
4. ブランチにプッシュ (`git push origin feature/amazing-feature`)
5. プルリクエストを作成

## 📄 ライセンス

MIT License

## 👤 作者

**appadaycreator**
- X (Twitter): [@appadaycreator](https://x.com/appadaycreator)
- GitHub: [@appadaycreator](https://github.com/appadaycreator)

## 🙏 謝辞

このプロジェクトは30日連続開発チャレンジの一環として作成されました。
#継続は力なり