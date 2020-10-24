# ワークサンプル

## 概要

教育メンター（Webエンジニアコース担当）のワークサンプルでは、業務内容と同じ以下の内容を体験していただきます。  

1. 受講生からの質問への回答

重要なことは、本当に自分がメンバーになったかのように体験することです。これは、ただの筆記テストではありません。  
あなたと私たちの双方にとって、とても大切なことです。  

### 必要な前提知識

現時点の知識があれば理想的ですが、完全にゼロでもチャレンジする機会を設けています。  
知識がゼロの方は、この機会にご自分がどこまで知識をつけられそうかを確かめましょう。  

- Git
- Github
- Markdown
- Linuxコマンド基礎
- エディタの操作
- HTML/CSSの基礎
- Rubyの知識

現時点で知識が身についていない方を対象に、推薦学習教材をお伝えします。

[推薦学習教材]
Ruby入門をすべて取り組んでみてください。そうすれば回答ができる基礎知識が手に入ります。
https://diver.diveintocode.jp/pre_curriculums/ruby-introduction


## 取り組み方の基本原則

ワークサンプルへの取り組む方の基本原則をお伝えします。  

- 優しく丁寧に対応すること
- ただ答えを教えるのではなく、その人のためになるようにサポートすること
- オンラインでのコミュニケーションは語弊が生じやすいので、表現などに気をつけること
- 事前に説明していない言葉やユーザーのレベルを考えて、サポートや教材開発を行うこと

## ワークサンプル 受講生からの質問への回答

実務では、オンラインプログラミング学習サービス「DIVER」上や通学された受講生からの質問に直接回答することになります。  

### 質問回答例

`質問例`

```
f.text_fieldとf.hidden_fieldの違いについて、念のための確認です。
以下の認識であってますでしょうか？

f.text_field　→　テキストを編集可能な状態で表示させる
f.hidden_field　→　テキストを編集不可の状態で表示させる
```

`回答例`

```
ほぼ合っていますが、多少補足します！

f.text_field　→　テキストを編集可能な状態で表示させる（テキストを打ち込むためのボックス部分を表示させる。そのボックスに最初からテキストが入っているかどうかは、form_for文に渡した引数によって異なる）

f.hidden_field　→　コントローラなどの命令で運んできたテキストなどのデータを、現在のページに含める。(見えないし編集もできない）
```

### 実際に回答してみよう

`今回のワークサンプルで回答して欲しい質問`

```
カリキュラム中の、『4.ifの条件式について』内のコードについて曖昧な点があったので質問します。

if true # trueという値そのもの
  puts "あなたは未成年です(2)" # 処理が実行される
end

if trueで始まる式を、自分は「もしtrueであれば、以下の処理を実行する」という意味だと考えてます。
しかし、なんの式に対して、何がtrueなのか？
上のif age < 20は分かりやすいです。「もしageが20より小さいならば〜」という条件の式がある。
しかしこのif trueは、何がtrueの時に実行されるのかがよくわかりません。
教えてください。
```

### Push方法

`question_answer.md` ファイルを作成して、この質問への回答を記述し、あなたのアカウントのGithubリポジトリに保存してください。  
保存方法は、Webブラウザ上で操作をしても、ローカル環境でGitでコミットしてからプッシュをしてもどちらでも構いません。    
なお、提出前に下記の内容を守ることができているかどうかご自分でチェックしてください。  

- [ ] マークダウンの引用記号「>」を使い装飾する
- [ ] 回答文にコードを記述する場合マークダウンの「```」を使い装飾する
- [ ] 誤字脱字やマークダウンの適用漏れ、改行崩れなどないかチェックする

## 提出方法

上記の内容に取り組んだものを反映した、あなたのGithubリポジトリのURLをご提出ください。  
なお、ご提出前に以下の項目をすべて満たしているかを確認しましょう。  

- [ ] `question_answer.md`に回答を記述した

### 提出期限

提出期限は、採用面接時にお話ができていればその期限までに。そうではない場合は、ご自分で決めてください。  
私たちは、自ら業務にコミットして達成していく姿勢を重視しています。  

以上でワークサンプルは終了です。  
お疲れ様でした。