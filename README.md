# doc_genai_Proposal_for_introducing_generative_AI_with_emphasis_on_safety
安全性を重視した生成AI導入の提案

# 安全性を重視した生成AI導入の提案
Proposal for introducing generative AI with emphasis on safety

doc_genai_Proposal_for_introducing_generative_AI_with_emphasis_on_safety

# 目次
## 自己紹介
## 実現したいこと
## 導入のメリット
## 前回までの経緯
## 今回の提案
## ローカルLLMでできそうなこと
## 導入の提案
## 注目する技術

## 自己紹介

### 来歴と興味
- 設備業界で勤務経験があり、点検や修理の見積もり作成に表計算ソフトを利用。
- 点検や修理の見積もりは既に費用が決定されており、その費用を関数化することで効率化を図った経験あり。
- 作業効率化に繋がるシンプルな仕組み化に興味があり、手間を省くための自動化を心掛けてきた。
- 情報のインプットとアウトプットを高速化するためのシステム構築にも関心が高い。

### 最近の関心
- 生成AI、特にLLM (Large Language Model) (大規模言語モデル) の業務利用に注目しており、特に業務利用に必要なローカルLLM環境の整備が課題。

### 過去の関心事
- BPMN（Business Process Model and Notation）の利用に関心を持ち、業務フローの可視化や自動化を検討していた。専用のシステム導入が必要、利用者全員が記法を理解する必要があり、従来通り図形による表現でとどまる。




## 実現したいこと

### 最も効果的なアプローチ
- 生成AIの業務利用を、すぐにでも始める。検証を通じて、実用性を高めていくことが重要。
- 生成AIは急速に進化しているため、最新のノウハウを蓄積していきたいと考えている。
- ツールとしての役割を重視し、利用したい人が利用できる環境を準備したい。自分が最も利用したいから提案している。
- 導入に伴う費用対効果を定量的に示すことが難しいため、定性的な評価を重視して、実用性を高めていく。
- 検証を重ねる上で、既存のマシンでは利用が難しい。常時起動はできないため、検証には専用のマシンが必要となる。
- Mac Mシリーズ 導入により、一般的なマシンと比較し約8倍のスピード差という機能の性質を活かして、検証用の会話ラリーを素早く実行できる環境を構築することが望ましい。
- 最終的には github の オンプレミス版を導入し、生成AIを介してメンテナンス可能とする、マークダウン化（マーメイド化）したドキュメントとともに ソースコードを管理する環境を提案。





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



## 2025年2月の提案（生成AI分野の進化を反映）

### 1. 目的

生成AIの分野は急速に進化しており、半年前にできなかったことが今だとできるようになっています。 

今回の提案では、既存のMac M2 Miniを活用し、llama.cpp のサーバ機能を活用することで、1.5bの日本語対応モデルを用いたWeb UI検証を目的としています。

### 2. 現状の問題点

* メイン業務に対する生成AIの有効活用が見込めない。
* 機密情報の取り扱いに関する制限がある。
* クラウド型LLMの利用に関するルールが明確ではない。
* 現在の開発環境での検証が難しい。

### 3. 提案内容

* 1.5b日本語対応モデルによる検証
* llama.cpp Web UIの利用
* チーム共通の利用
* レンタルMac M2 Mini 1台

### 4. 期待効果

* メイン業務に対する生成AIの活用を実務に合わせて検証
* 機密情報の取り扱いに関するリスク軽減
* マシンによる検証のスピードアップ
* クラウド型LLMへの移行に伴うリスク軽減

### 5. 費用対効果

* 定量的な算出は困難ですが、レンタルMac M2 Mini 1台の利用による業務効率の向上を想定し、定性的に評価することが可能です。

### 6. 注意点

* 既存のマシンでの検証は、処理速度やメモリの制約等で実施が難しい可能性があるため、マシン導入しチーム内での共有利用を希望します。 

### 7. 今後の展望

* 2025年1月末にリリースの1.5Bモデル「tinyswallow」を利用することで、Mac Mini 1台でも前回提案の検証が少人数ではなく利用したい人の間で可能になる可能性があります。



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
- 1台のマシンで共有利用を想定
- 機密情報が含まれるタスクへの対応
- 少数のユーザー群での利用

## まとめ
ローカルLLMは、クラウド型LLMと併用することで、機密情報の取り扱いに関する安全性を確保しながら、多様なニーズに対応することができます。また、クラウド型LLMとローカルLLMのそれぞれの強みを活かしたハイブリッドアプローチにより、より柔軟で効率的な利用を実現することが可能です。




## 導入の提案

### 1. 論点
* **段階的なアプローチ:** 少量で運用を開始し、評価結果に基づいて段階的な導入を判断するというアプローチが現実的で効率的。

### 2. 実施のメリット
* **リスク軽減:** 大規模な導入による失敗リスクを最小限に抑えられる。
* **ニーズの確認:** 実際の業務環境での効果を検証することで、導入の必要性や規模を判断できる。

### 3. 実施計画案
* **1台導入・評価:** 初期段階では、1台の生成AIマシンを導入し、運用開始後、1か月または数週間で評価を実施。
  * **評価内容:** 定性的な効果（ユーザー満足度、使いやすさ、課題など）
  * **評価方法:** アンケート調査、インタビューなど
* **評価結果に基づく判断:** 評価結果が一定の基準を満たさない場合、または予想した効果が得られない場合は、導入を中断し、他の方法を検討。
* **継続的なモニタリング:** 導入後も定期的に評価を行い、効果を継続的に確認し、必要に応じて調整。

### 4. 継続的な学習
* **最新技術動向の把握:** 生成AI分野は急速に発展しているため、最新の技術動向を継続的に調査し、導入検討の材料とする。
* **パートナー企業との連携:** 専門家やベンダーと連携し、効果的な導入方法や最適なプラットフォームを選定する。





## 注目する技術

### 1. ファインチューニング (Fine-Tuning) (追加学習)

- **概要**: 事前学習済みのモデルを新たなデータセットでさらに学習させることで、特定のタスクに特化した性能を向上させる技術。
- **必要なもの**: 
    - **事前学習済みモデル**: 研究機関や企業が公開している大規模言語モデル（例: BERT, GPT）。
    - **新たなデータセット**: 特定のタスクや業界に特化したテキストデータ。
    - **計算資源**: 大規模なデータセットを学習するために、GPUやTPUなどの高性能計算機が必要。

### 2. RAG (Retrieval-Augmented Generation) (検索拡張生成)

- **概要**: モデルがまだ知り得ない情報や知識を、外部の情報源（例えば、インターネット上の記事や書籍）から取得し、それらを基に生成を補完する技術。
- **必要なもの**: 
    - **専用システムやデータベース**: 外部ソースから取得した情報を格納・検索できる仕組み。
    - **LLM**: 外部データから情報を取得し、適切な形式に変換してモデルに提供できる能力を持つモデル。

### 3. Long-Context LLMs (長文読解)

- **概要**: 長い文脈を直接モデルに入力してそのまま処理・応答するテクノロジ。
- **必要なもの**: 
    - **LC用のトレーニング済みモデル**: 長い文脈を正確に理解し、適切な応答を生成できるようにトレーニングされたモデル。
    - **テキストデータ**: 長文のテキストデータセット。

### 4. Vision-Language Model (VLM, 画像言語モデル)

- **概要**: 画像とテキストを複合して扱うモデル。
- **必要なもの**:
    - **VLM用のトレーニングデータ**: 画像と対応するテキストデータのセット。
    - **画像とテキストを相互に変換できるシステム**: 画像をテキストに変換し、テキストを画像に変換できる仕組みが必要。

### 5. Agentic Workflow (ワークフロー)

- **概要**: テキスト処理の各タスクを細分化し、それぞれのタスクを専用のLLMやアプリケーションの実装を組み合わせて行う技術。
- **必要なもの**:
    - **タスクの細分化**: テキスト処理の各ステップを明確に定義。
    - **各ステップの適切なLLMやアプリケーションの選択**: 各タスクに最適なモデルやシステムの選択。
    - **ワークフローの実装と管理**: 各ステップの実行手順、結果の取り扱い、問題発生時の対応などを規定。

### 6. AI agent (エージェント)

- **概要**: 環境を認識し、行動を起こすことができる自動化されたシステム。
- **必要なもの**:
    - **環境認識能力**: システムが周囲の環境を理解できる能力。
    - **行動の実行**: AIエージェントが行動を実行できる能力（例えば、タスクの実行、データの取得）。
    - **隔離環境**: AIエージェントが環境に悪影響を及ぼさないように隔離された環境が必要。
