# 安全性を重視した生成AI導入の提案

```mermaid
```

<br/><br/>
<br/><br/>



# 目次
- [自己紹介](#自己紹介)
- [実現したいこと](#実現したいこと)
- [導入のメリット](#導入のメリット)
- [提案例](#提案例)
- [ローカルLLMとクラウド型LLMの活用方法](#ローカルllmとクラウド型llmの活用方法)
- [導入の流れ](#導入の流れ)
- [注目する技術](#注目する技術)

```mermaid
```

<br/><br/>
<br/><br/>



## 自己紹介

### 来歴と興味
- 設備業界で勤務経験があり、点検や修理の見積もり作成に表計算ソフトを利用。
- 点検や修理の見積もりは既に費用が決定されており、その費用を関数化することで効率化を図った経験。
- 作業効率化に繋がるシンプルな仕組み化に関心があり、手間を省くための自動化を模索。

### 最近の関心
- 生成AI、特にLLM (Large Language Model) (大規模言語モデル) の業務利用に注目しており、特に業務利用に必要なローカルLLM環境の整備が課題。

### 過去の関心事
- BPMN（Business Process Model and Notation）の利用に関心を持ち、業務フローの可視化や自動化を検討していた。
- 専用のシステム導入が必要、利用者全員が記法を理解する必要があり、従来通り図形による表現でとどまる。


```mermaid
```

<br/><br/>
<br/><br/>



## 実現したいこと

### 最も効果的なアプローチ
- 生成AIの業務利用を、すぐにでも始める。検証を通じて、実用性を高めていくことが重要。
- 生成AIは急速に進化しているため、最新のノウハウを蓄積しながら検証を進める。
- ツールとしての役割を重視し、利用したい人が利用できる環境を準備。
- 導入に伴う費用対効果は定量的に示すことが難しいため、定性的な評価を通して、実用性を高めていく。
- 検証を重ねる上で、生成AIを高速に処理する専用の機構が必要のため、従来型のサーバでは利用が難しい。検証には専用のサーバが必要となる。
- Mac Mシリーズ 導入により、従来型のサーバと比較し約8倍のスピード差という機能の性質を活かして、生成AIを高速に処理する環境を構築することが望ましい。
- 最終的な理想の環境としては、github の オンプレミス版を導入し、生成AIを介してメンテナンス可能とする、マークダウン化（マーメイド化）したドキュメントとともに ソースコードを管理する環境を提案。



```mermaid
```

<br/><br/>
<br/><br/>



## 導入のメリット

**1. 業務効率化**
* 情報のインプットとアウトプットの速度が向上し、業務効率化に繋がる可能性がある。
* 専門的なスキルを有するメンバーが増えれば、より高度な業務に対応できるようになる。

**2. シャドーAIの防止**
* クラウド型LLMは、情報漏洩のリスクが伴う可能性がある。
* ローカルLLMを利用するルールを設けることで、シャドーAIの発生を防止できる。

**3. 組織の柔軟性・先進性の表明**
* 新しい技術を導入し、それを活用する組織であることを示すことで、組織の柔軟性と先進性を示す。
* 若い世代に対しては、最新技術に関心を持つきっかけとなる。

**4. 他組織との関係構築**
* 生成AIに関心を持つ他の組織と協力できる可能性がある。
* これにより、新たなビジネスチャンスや技術連携の機会を得られる可能性がある。

**5. シャドーAIの発生を防ぐためにローカルLLMを利用する**

* シャドーAIとは、組織で管理されていないサービスを利用することで発生する、意図しない情報漏洩や不正使用など、意図しないAIの利用を指す。
* ローカルLLMを利用することで、シャドーAIのリスクを最小限に抑えられる。

**ポイント**
* 業務効率化、シャドーAIの防止、組織の柔軟性と先進性の表明、他組織との関係構築の4点が主なメリットである。
* 生成AIへの関心の高まりを活かし、組織の魅力を高める手段として、生成AI導入を検討する。

```mermaid
```

<br/><br/>
<br/><br/>



## 提案例

2025年2月の初期導入提案例（生成AI分野の進化を反映）

### 1. 目的

生成AIの分野は急速に進化しており、半年前にできなかったことが今だとできるようになっています。 
この提案例では、安全性を重視したローカルLLMの活用を方針としています。
具体的には、Mac Mシリーズ を導入し、llama.cpp のサーバ機能を活用することで、1.5bの日本語対応モデルを用いたWeb UI利用を目的としています。

### 2. 導入の課題

* 業務に対する生成AIの有効活用がイメージできない。
* クラウド型LLMの利用に関する機密情報の取り扱いに制限がある。
* 従来型のサーバでの検証が難しい。

### 3. 提案内容

* 1.5b日本語対応モデルによる検証
* llama.cpp Web UIの利用
* チーム共通の利用
* Mac Mシリーズ 1台 をレンタルまたは購入

### 4. 期待効果

* メイン業務に対する生成AIの活用を実務に合わせて検証
* 機密情報の取り扱いに関するリスク回避（リスク０）
* 専用サーバによる検証のスピードアップ
* クラウド型LLMとの併用について対応可

### 5. 費用対効果

* 定量的な算出は困難ですが、Mac Mシリーズ 1台 の利用による業務効率の向上を想定し、定性的に評価することが可能です。

### 6. 注意点

* 既存のサーバでの検証は、処理速度やメモリの制約等で実施が難しい可能性があるため、サーバ導入しチーム内での共有利用を希望します。 

### 7. 今後の展望

* Mac Mシリーズ 1台だけでも、利用したい人の間で利用可能になる可能性があります。

```mermaid
```

<br/><br/>
<br/><br/>



## ローカルLLMとクラウド型LLMの活用方法

### 1. 用途別に分ける

#### 1.1 クラウド型LLM

- **機密情報なしのタスク**：
    - 複雑な調査や概要把握
    - 機密情報が含まれない文章の解析や清書
    - 機密情報が含まれないコーディング

#### 1.2 ローカルLLM

- **機密情報の含むタスク**：
    - 個人の情報や機密性の高い情報を含む文章の解析と清書
    - 機密情報が含まれるコーディング

#### 1.3 ハイブリッドアプローチ

- **クラウド型LLMの出力**をローカルLLMにフィードする
- ローカルLLMで機密情報を除去し、クラウド型LLMで更なる深掘りを行う

### 2. ユーザー規模

#### 2.1 クラウド型LLM
- 大規模なユーザー群での利用を想定
- 機密情報を含まないタスクへの対応

#### 2.2 ローカルLLM
- 1台のサーバで共有利用を想定
- 機密情報が含まれるタスクへの対応
- 少数のユーザー群での利用

### まとめ
ローカルLLMは、クラウド型LLMと併用することで、機密情報の取り扱いに関する安全性を確保しながら、多様なニーズに対応することができます。また、クラウド型LLMとローカルLLMのそれぞれの強みを活かしたハイブリッドアプローチにより、より柔軟で効率的な利用を実現することが可能です。




```mermaid
```

<br/><br/>
<br/><br/>



## 導入の流れ

### 1. 論点
* **段階的なアプローチ:** 少量で運用を開始し、評価結果に基づいて段階的な導入を判断するというアプローチが現実的で効率的。

### 2. 実施のメリット
* **リスク軽減:** 大規模な導入による失敗リスクを最小限に抑えられる。
* **ニーズの確認:** 実際の業務環境での効果を検証することで、導入の必要性や規模を判断できる。

### 3. 実施計画案
* **1台導入・評価:** 初期段階では、1台の生成AIサーバを導入し、運用開始後、1か月または数週間で評価を実施。
  * **評価内容:** 定性的な効果（ユーザー満足度、使いやすさ、課題など）
  * **評価方法:** アンケート調査、インタビューなど
* **評価結果に基づく判断:** 評価結果が一定の基準を満たさない場合、または予想した効果が得られない場合は、導入を中断し、他の方法を検討。
* **継続的なモニタリング:** 導入後も定期的に評価を行い、効果を継続的に確認し、必要に応じて調整。

### 4. 継続的な学習
* **最新技術動向の把握:** 生成AI分野は急速に発展しているため、最新の技術動向を継続的に調査し、導入検討の材料とする。
* **パートナー企業との連携:** 専門家やベンダーと連携し、効果的な導入方法や最適なプラットフォームを選定する。

```mermaid
```

<br/><br/>
<br/><br/>



## 注目する技術

### 1. ファインチューニング (Fine-Tuning) (追加学習)

- **概要**: 事前学習済みのモデルを新たなデータセットでさらに学習させることで、特定のタスクに特化した性能を向上させる技術。
- **必要なもの**: 
    - **事前学習済みモデル**: 研究機関や企業が公開している大規模言語モデル（例: BERT, GPT）。
    - **新たなデータセット**: 特定のタスクや業界に特化したテキストデータ。
    - **計算資源**: 大規模なデータセットを学習するために、GPUやTPUなどの高性能計算機が必要。

```mermaid
```

<br/><br/>
<br/><br/>



### 2. RAG (Retrieval-Augmented Generation) (検索拡張生成)

- **概要**: モデルがまだ知り得ない情報や知識を、外部の情報源（例えば、インターネット上の記事や書籍）から取得し、それらを基に生成を補完する技術。
- **必要なもの**: 
    - **専用システムやデータベース**: 外部ソースから取得した情報を格納・検索できる仕組み。
    - **LLM**: 外部データから情報を取得し、適切な形式に変換してモデルに提供できる能力を持つモデル。

```mermaid
```

<br/><br/>
<br/><br/>



### 3. Long-Context LLMs (長文読解)

- **概要**: 長い文脈を直接モデルに入力してそのまま処理・応答するテクノロジ。
- **必要なもの**: 
    - **LC用のトレーニング済みモデル**: 長い文脈を正確に理解し、適切な応答を生成できるようにトレーニングされたモデル。
    - **テキストデータ**: 長文のテキストデータセット。

```mermaid
```

<br/><br/>
<br/><br/>



### 4. Vision-Language Model (VLM, 画像言語モデル)

- **概要**: 画像とテキストを複合して扱うモデル。
- **必要なもの**:
    - **VLM用のトレーニングデータ**: 画像と対応するテキストデータのセット。
    - **画像とテキストを相互に変換できるシステム**: 画像をテキストに変換し、テキストを画像に変換できる仕組みが必要。

```mermaid
```

<br/><br/>
<br/><br/>



### 5. Agentic Workflow (ワークフロー)

- **概要**: テキスト処理の各タスクを細分化し、それぞれのタスクを専用のLLMやアプリケーションの実装を組み合わせて行う技術。
- **必要なもの**:
    - **タスクの細分化**: テキスト処理の各ステップを明確に定義。
    - **各ステップの適切なLLMやアプリケーションの選択**: 各タスクに最適なモデルやシステムの選択。
    - **ワークフローの実装と管理**: 各ステップの実行手順、結果の取り扱い、問題発生時の対応などを規定。

```mermaid
```

<br/><br/>
<br/><br/>



### 6. AI agent (エージェント)

- **概要**: 環境を認識し、行動を起こすことができる自動化されたシステム。
- **必要なもの**:
    - **環境認識能力**: システムが周囲の環境を理解できる能力。
    - **行動の実行**: AIエージェントが行動を実行できる能力（例えば、タスクの実行、データの取得）。
    - **隔離環境**: AIエージェントが環境に悪影響を及ぼさないように隔離された環境が必要。

```mermaid
```

<br/><br/>
<br/><br/>


