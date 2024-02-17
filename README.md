# Art_app

■サービス概要
どんなサービスなのかを３行で説明してください。

イラスト初心者が自分の作品を時系列で投稿し、その成長を視覚化できる投稿アプリです。
閲覧者はユーザーの「成長」や「努力」に対して、「いいね」を付けることができます。
また、イラストと同時に参考資料を共有することが可能で、他のユーザーはこれらの情報を参考にして、同じレベルに到達するための学習の道筋を立てることができます。

■ このサービスへの思い・作りたい理由
このサービスの題材となるものに関してのエピソードがあれば詳しく教えてください。
このサービスを思いつくにあたって元となる思いがあれば詳しく教えてください。

趣味でイラストを描き始め、少し技術が向上を感じ始めた頃、自分の作品をSNS上のイラストと比較するようになりました。
多くの投稿は非常に高いレベルで、どんなに拘ってイラストを描いたとしても、”イラストの上手さ”という観点から見ると劣ってしまい、モチベーションが低下や、自分のイラストのレベルがこれから成長できるのかという心配をするようになってしまいました。
しかし、友人に自分のイラストを見てもらった際、「成長」や「努力」を高く評価してもらい、絵を描く理由は上手さを追求することだけではないと再認識させられました。

そこで、すべての人がイラストを純粋に楽しめる環境を提供したいと思い、以下のコンセプトを掲げてアプリを思案しました。
①, 個々の「成長」や「努力」にフォーカスし、イラストを描くこと自体や描く人自身に価値を持たせることができる。
②, ユーザーに明確な成長の道筋を示すことができる。
③, イラスト初心者の参入難易度を下げる。

■ ユーザー層について
決めたユーザー層についてどうしてその層を対象にしたのかそれぞれ理由を教えてください。
イラスト初心者が純粋にイラストを描くことができる環境を作りたいから。

■サービスの利用イメージ
ユーザーがこのサービスをどのように利用できて、それによってどんな価値を得られるかを簡単に説明してください。
・ユーザーは自分のイラストを時系列に投稿し、各イラストに関してこだわった点や参考にしたYouTube動画、書籍を共有することができる。
・他のユーザーは公表されたイラストの「成長」や「努力」に対して「いいね」や、コメントをすることができる。また、関連する参考動画や書籍を同時に閲覧することができる。
・参考にした書籍や動画は「みんなの書籍」、「みんなの動画」として一覧で見ることができる。
・投稿したイラストをハイライト動画にすることができ、Twitter（X）に投稿することができる。

■ ユーザーの獲得について
想定したユーザー層に対してそれぞれどのようにサービスを届けるのか現状考えていることがあれば教えてください。
SNSでの宣伝

■ サービスの差別化ポイント・推しポイント
似たようなサービスが存在する場合、そのサービスとの明確な差別化ポイントとその差別化ポイントのどこが優れているのか教えてください。
独自性の強いサービスの場合、このサービスの推しとなるポイントを教えてください。

・イラストの「上手さ」ではなく、「成長」や「努力」にフォーカスしており、イラストを描くこと自体や描く人自身に価値を持たせることができる所。
・成長の可視化と参考資料の紹介により、ユーザーに成長の道筋を示すことができる。

■ 機能候補
現状作ろうと思っている機能、案段階の機能をしっかりと固まっていなくても構わないのでMVPリリース時に作っていたいもの、本リリースまでに作っていたいものをそれぞれ分けて教えてください。

MVPリリース
・ユーザー登録機能
・ユーザー情報の変更
・ログイン/ログアウト
・プロフィール機能
・イラスト投稿
・お勧め動画、書籍紹介
・マイページ
・みんなの投稿一覧
・いいね機能
・みんなの動画一覧
・みんなの書籍一覧
・ハイライト動画作成機能
・Twitter（X）投稿機能
・パスワードリセット機能

本リリース
・公開、非公開機能
・アドバイスを要求on,off機能
・問い合わせ
・利用規約・プライバシーポリシー

■ 機能の実装方針予定
一般的なCRUD以外の実装予定の機能についてそれぞれどのようなイメージ(使用するAPIや)で実装する予定なのか現状考えているもので良いので教えて下さい。
・ハイライト動画作成機能→streamio-ffmpegジェムを使用
・Twitter（X）投稿機能→Twitter APIを使用
