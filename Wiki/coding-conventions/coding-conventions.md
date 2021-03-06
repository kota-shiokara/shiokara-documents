# 変数について
- 使用される状況に合わせて具体的な名前にしてください。
  - 例: `result` -> 関数などでreturnする時に返す値。
  - 例2: `exampleTextView` -> AndroidとかでUIの一種であるTextViewを示す時などに使う。View bindingという機能を使用する場合は変数名はあまり気にしなくていい。
- 長くても構いません。エディタは優秀なので長くても補完が効いてくれるので、「書くのが面倒」なんて言い訳はしないようにしましょう。
- 自然な英語になるようにしましょう。テックリーダーは英語が苦手ですが何とか文をひねりだしてるので皆さんも頑張ってください。
- 配列を表す変数は複数系にしましょう。

# 関数について
- 返す値、もしくは機能が明確にわかるような名前にしてください。`動詞+名詞`などが多いと思います。
  - 例: `fetchTextData()` -> インターネットからTextDataを取得する。
  - 例2: `getTextData()` -> ローカルからTextDataを取得する。
- 関数にする大きな利点は3つあると考えています。
  - 同じような処理を二回以上書かなくて良い。
  - 処理を細かくすることで、修正箇所が少なくて済む。
  - テストをしやすくなる。

# 特記事項
尚、各プラットフォームで変数名の命名規則が若干変わったりなどがあります。  
基本的な考え方は上記ですが、それぞれのプラットフォームに合う形でコーディングしてください。
- Androidは[こちら](./coding-conventions-android.md)
- iOSは[こちら](./coding-conventions-ios.md)

# コメント
コメントは強制ではありませんが、後々の修正や、自分がこの関数でどんな処理を書くのかなどを言語化することで未来の開発者(チームメンバーや自分)に優しさを見せることができます。
- 関数の前にその関数がどのような処理を行うかをコメントで書いておく

これだけでも次に開発する人、未来の我々は助かることでしょう。