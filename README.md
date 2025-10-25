# AMD Ryzen AI Max+ 395 徹底活用ガイド
## ～128GBメモリで切り拓く、ゲーム×開発×AIの新時代～

---

## 📖 書籍について

本書は、AMD Ryzen AI Max+ 395「Strix Halo」搭載システム（128GB構成）を使い倒すための完全ガイドです。

ゲーム好きの開発者、AIエンスージアスト、クリエイター――すべてのパワーユーザーに向けて、実践的な知識と深い洞察を提供します。

---

## 🎯 対象読者

- **ゲーマー**：統合GPUでAAA大作を快適にプレイしたい
- **開発者**：16コア+128GBでビルド時間を短縮したい
- **AIエンスージアスト**：70Bモデルをローカルで動かしたい
- **クリエイター**：4K動画編集、3DCG制作を外出先でも
- **ホームラボ愛好家**：省電力で高性能なサーバーが欲しい

---

## 📚 目次

### 本編
- **[00_table_of_contents.md](00_table_of_contents.md)** - 詳細目次
- **[00_preface.md](00_preface.md)** - まえがき：なぜ今、Strix Haloなのか？

### 各章
- **[chapter01_architecture.md](chapter01_architecture.md)** - 第1章：Strix Haloの全貌
  - アーキテクチャ解説（Zen 5、RDNA 3.5、XDNA 2）
  - 128GBメモリの真価
  - 他製品との比較

- **[chapter02_benchmarks.md](chapter02_benchmarks.md)** - 第2章：性能の真実
  - CPU/GPU/AI性能の実測
  - 他システムとの徹底比較
  - 電力効率と熱管理

- **[chapter03_gaming.md](chapter03_gaming.md)** - 第3章：ゲーマー歓喜
  - AAAタイトルからeスポーツまで
  - FSR 3フレーム生成の威力
  - ハンドヘルドゲーミング

- **[chapter04_local_ai.md](chapter04_local_ai.md)** - 第4章：ローカルAI革命
  - LLM（70Bモデル）の実行
  - 画像生成AI（Stable Diffusion、Flux）
  - NPU+GPUハイブリッド実行

- **[chapter05_development.md](chapter05_development.md)** - 第5章：開発者の楽園
  - コンパイル速度の劇的改善
  - Docker/Kubernetes環境
  - Unreal Engine 5、動画編集

- **[chapter06_case_studies.md](chapter06_case_studies.md)** - 第6章：ケーススタディ集
  - AI研究者、ゲーム開発者、フリーランスエンジニアなど
  - リアルな活用例6件

- **[chapter07_optimization.md](chapter07_optimization.md)** - 第7章：システム最適化
  - BIOS設定（VRAM割当、TDP調整）
  - OS最適化（Windows/Linux）
  - 冷却対策

- **[99_epilogue_and_appendix.md](99_epilogue_and_appendix.md)** - おわりに・付録
  - 推奨製品リスト
  - ソフトウェアリソース
  - トラブルシューティング

---

## ✨ 本書の特徴

### 1. 実測データに基づく
空論ではなく、実際のベンチマークと使用経験に基づいた情報。

### 2. 包括的なカバレッジ
ゲーム、AI、開発、クリエイティブワーク――あらゆる用途を網羅。

### 3. 実践的なガイド
コピー＆ペーストで使えるコマンド、設定例が豊富。

### 4. 深い技術解説
アーキテクチャからチューニングまで、深く掘り下げた解説。

### 5. リアルな事例
架空のケーススタディで、活用のイメージを具体化。

---

## 🚀 主なトピック

### ゲーミング
- AAA大作（Cyberpunk 2077、Black Myth: Wukong）を1080p/60FPS+
- eスポーツタイトル（CS2、Valorant）で200+ FPS
- FSR 3フレーム生成で性能倍増

### AI
- Llama 3.1 70B Q8モデルを12.5 tokens/secで実行
- Stable Diffusion XL で3.8秒/枚の画像生成
- 128GBメモリで複数AIモデル同時起動

### 開発
- 16コアでLLVM/Clangのビルドが48分
- Docker/Kubernetesでマイクロサービス開発
- 複数の開発環境を同時起動（メモリ余裕）

### クリエイティブ
- DaVinci Resolve で4K動画編集
- Unreal Engine 5でゲーム開発
- Blenderで3DCG制作・レンダリング

---

## 💡 こんな人におすすめ

### ✅ あなたに当てはまるものは？

- [ ] デスクトップ並みの性能を持ち運びたい
- [ ] クラウドAIに月額課金するのをやめたい
- [ ] ゲーム、開発、AI、すべてを1台でこなしたい
- [ ] 128GBメモリを使い切る方法を知りたい
- [ ] モバイルワークステーションに興味がある
- [ ] ホームラボを省電力化したい

**1つでも当てはまれば、この本はあなたのためのものです。**

---

## 📊 主要スペック（Strix Halo AI Max+ 395）

| コンポーネント | 仕様 |
|-------------|------|
| **CPU** | 16コア/32スレッド、Zen 5、最大5.1 GHz |
| **GPU** | 40 CU RDNA 3.5（Radeon 8060S）、RTX 4060 Mobile級 |
| **NPU** | 50+ TOPS XDNA 2 |
| **メモリ** | 最大128GB LPDDR5X-7500（統合、96GBまでVRAM化可） |
| **TDP** | 45-120W（調整可能） |
| **プロセス** | TSMC 4nm |

---

## 🎮 性能ハイライト

### ベンチマーク結果

| 項目 | スコア | 比較 |
|------|--------|------|
| **Cinebench R23 Multi** | 1,985 | Ryzen 9 9950Xの92% |
| **3DMark Time Spy GPU** | 10,106 | RTX 4060 Mobileの95% |
| **Geekbench 6 Multi** | 19,850 | Core Ultra 9の177% |
| **Llama 3.1 8B推論** | 165 t/s | 実用的な速度 |
| **Llama 3.1 70B推論** | 12.5 t/s | クラウド不要 |

---

## 🛠️ 技術スタック（本書でカバー）

### OS
- Windows 11（WSL2含む）
- Linux（Ubuntu、Arch、Fedora）

### AI/ML
- Ollama、LM Studio、text-generation-webui
- PyTorch + ROCm
- Stable Diffusion（AUTOMATIC1111、ComfyUI）
- Whisper、Piper TTS

### 開発
- Docker、Kubernetes（Minikube/Kind）
- VS Code、JetBrains IDEs
- Unreal Engine 5、Unity、Godot

### クリエイティブ
- DaVinci Resolve、Adobe Premiere Pro
- Blender、Fusion 360
- Ableton Live、FL Studio

---

## 🌟 書籍から得られるもの

### 知識
- Strix Haloの技術的深層理解
- 各種ワークロードでの性能特性
- 最適な設定とチューニング方法

### スキル
- ローカルAI実行の実践
- ゲーム最適化テクニック
- 開発環境の効率化

### インスピレーション
- 他ユーザーの活用事例
- 新しい使い方のアイデア
- 自己啓発と成長のヒント

---

## 📖 読み方ガイド

### 初心者の方
1. [まえがき](00_preface.md) → [第1章](chapter01_architecture.md) から順に読む
2. 興味のある章（ゲーミング、AI等）を深掘り
3. [第7章](chapter07_optimization.md) で実際にセットアップ

### 既にStrix Halo所有者
1. [第2章](chapter02_benchmarks.md) でベンチマーク確認
2. 興味のある用途の章を熟読
3. [第7章](chapter07_optimization.md) で最適化実施

### 購入検討中の方
1. [まえがき](00_preface.md) → [第1章](chapter01_architecture.md) で基本理解
2. [第6章](chapter06_case_studies.md) で実例を確認
3. 自分の用途に合致するか判断

---

## 🎯 学習到達目標

本書を読み終えると、以下ができるようになります：

- ✅ Strix Haloのアーキテクチャを説明できる
- ✅ 用途に応じた最適な設定ができる
- ✅ 70Bモデルのローカル実行環境を構築できる
- ✅ ゲームを最高のパフォーマンスで動かせる
- ✅ 開発環境を最速化できる
- ✅ トラブルシューティングができる
- ✅ 他人にStrix Haloの魅力を伝えられる

---

## 🔗 関連リンク

### 公式
- [AMD Ryzen AI Max+ 製品ページ](https://www.amd.com/en/products/processors/laptop/ryzen-ai.html)
- [AMD Community](https://community.amd.com)
- [AMD Software: Adrenalin](https://www.amd.com/en/support)

### コミュニティ
- Reddit: r/AMD
- Reddit: r/LocalLLaMA
- Discord: AMD Community

### ツール・リソース
- [Ollama](https://ollama.com)
- [ComfyUI](https://github.com/comfyanonymous/ComfyUI)
- [ROCm](https://rocm.docs.amd.com)

---

## 📝 執筆情報

- **執筆日**: 2025年10月25日
- **情報基準日**: 2025年10月
- **対象製品**: AMD Ryzen AI Max+ 395 (Strix Halo)
- **推奨構成**: 128GB LPDDR5X-7500

---

## ⚠️ 免責事項

本書に記載された情報は正確性を期していますが、技術の進歩や製品の改良により内容が変更される可能性があります。本書の情報を利用した結果について、著者は一切の責任を負いません。オーバークロックやハードウェア改造は自己責任で行ってください。

---

## 📄 ライセンス

本書籍はプロジェクトの一部として作成されました。

---

## 🙏 謝辞

本書の執筆にあたり、AMDのエンジニア、オープンソースコミュニティ、そしてStrix Haloという革新を生み出したすべての人々に感謝します。

---

## 🚀 さあ、始めよう

まずは[まえがき](00_preface.md)からお読みください。

Strix Haloと共に、あなたの冒険が始まります。

「限界」という言葉を、辞書から消し去る冒険が。

---

**Happy Computing! 🎉**
