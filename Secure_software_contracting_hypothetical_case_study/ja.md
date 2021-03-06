## 大ばか者を訴えよう -- セキュリティ、ソフトウェア、契約および弁護士

  - Jeff Williams (Aspect Security, Inc.) により
  - 2004年1月13日に投稿された

## 序文

あなたが、彼らが生産したコードがセキュリティ・ホールに満ちていると数年後にわかるために、ソフトウェア・ショップにあなたのWebアプリケーション開発を外部調達するならば、あなたは何をするでしょうか？
あなたがコードを書いた開発者であるならば、あなたは何をするでしょうか？ 聞き慣れたように聞こえます？
多くの組織において、ワンパターンの反応は契約違反または怠慢論に関して開発者を告訴することです、しかし、それはあなたができる最大の間違いです。
このコラムは、これらの論争がどのように起こるか、契約がどのように機能するか、双方におけるいくつかの議論について論じます。そして、うまくいけばあなたに微妙な状況を案内する助けになる妥協点を提案します。

`あなたが書いたソフトウェアが脆弱性を持つかもしれないとわかるとき、あなたは何をしますか？`

## 単にもう一つの外注化されたWebアプリケーション

National Widgetsのありさまを想像します。
2年前、Nationalは彼らのユーザーのためにウェブサイトを構築するために、優秀なFront
End Associatesと契約しました。 契約は、実行される仕事、スケジュール、そして、多くの機能要求を詳述しました ―
しかし、セキュリティについて完全に語られていなかった。 Front
Endはサイトを構築しました、そして、Nationalは何事もなくおよそ18か月前にそれを配備しました。
サイトはよくうまくいっていました、そして、Nationalは大きな委託をFront Endに提供しました。

近年では、一部のNational従業員はセキュリティ問題の可能性を持ち上げたので、NationalはFront
Endへ行って、アプリケーションがセキュアかどうか、彼らに尋ねました。 Front
End営業チームは、踊り始めて、彼らが彼らの契約上の義務を満たすと確信していると言って、これらの「新しい」要求事項を受けるという提案をして満足です。
Nationalは最初の契約を確信できなくて、最初の契約がセキュリティを必要としたかどうか確かめるために、彼らの弁護士のところへ行きました。

## 弁護士を送り出します

弁護士は問題に非常に興奮しているようになって、責任、権利、義務と過失推定則の標準について声明をし始めました。
Nationalは、契約がセキュリティを必要としたか、必要としなかったかどうかについて、はっきりした答えを決して得ませんでした。
それで、彼らはただFront Endに戻って、彼らに無料で問題を解決するよう頼みました。 そして、状況が崩壊させ始めた所で、それはそうです。

Front Endは、彼らがコードに少しもセキュリティ問題がないと思っていると言いました。
納品の前に、彼らはアプリケーションのセキュリティ監査をするためにセキュリティ・テストの会社を雇いました。
彼らが雇った会社は、試験をして報告を準備するために、侵入テストを専門とすると主張しました。
残念なことに、同社がしたすべては、nmapとnessusのような2、3のスキャンツールを実行することでした。
彼らはツール出力をきれいにして、レポートを出しました。 Front
Endがレポートをあげたとき、Nationalは笑って、彼らに彼らが開発したアプリケーションのためにアプリケーション・セキュリティ試験結果を生産するよう頼みました。
これに直面して、Front
Endは素早く引き下がって、彼らのコードに関するセキュリティ問題がない、そして、たとえあったとしても、彼らはセキュアなコードを構築することを要求されていない、と再び主張しました。

Nationalは、セキュアなコードを構築する要件が明らかである、そして、故意にセキュアではないコードを構築したどんなベンダーでも明らかに怠慢であると答えました。
ついで、明らかに、把握して、彼らは黙示の被保証人、厳格責任と集団訴訟のような用語をやたらと使い始めました。
彼らはOWASPトップ１０をWebアプリケーション・セキュリティのための事実上の標準とさえ呼んで、連邦取引委員会さえ標準を満たさない会社を求めていると言いました。

## みんな専門家を雇う

静かに、Front Endは彼らのコードにはセキュリティ問題があったことを心配し始めました。 それで、彼らは彼ら自身の専門家を雇いました。
彼らは、Webアプリケーション・セキュリティを専門とした会社が彼らのコードをレビューして、いくらかのアプリケーション侵入テストをするとわかりました。
これらの専門家は非常にたくさんの問題を最初の数日で発見して、彼らにそれがどのように行っていたかについて知らせるために、Front
Endを呼びました。 Front
Endの上級マネージャーは、彼らの調査結果に対する報告書を彼らが必要としないということを彼らに知らせるために、数日後に専門家に後で電話しました。
むしろ、彼らは遠隔会議の間に口ですべての結論を受けるのを好みます。

一方、Nationalは最初の業務予定が彼らのコードに関する本当に深刻なセキュリティ問題があるということを証明することになっていると決めました。
それで、彼らは彼ら自身のWebアプリケーション・セキュリティの専門家を雇って、アプリケーション・セキュリティ・チェックを手配しました。
これらの専門家は標準的なWebアプリケーション脆弱性スキャンツールから始めたが、多少の問題を見つけるだけでした。
専門家はコードレビューをしたくて、Nationalにアプリケーションのためにソースコードのコピーを送るよう頼みました。
しかし、Nationalは彼らのアプリケーションを決して請求しないで、ソースコードのコピーを持ちませんでした。 彼らがFront
Endにコピーを要求したとき、彼らは手間どって、企業秘密と著作権問題に言及して、最終的に拒否されました。
Nationalにとって幸いにも、コードはJavaで記述されて、わかりにくくされませんでした。
それで、専門家はDigital
Millennium著作権法（DMCA）をばかにして、Jadでコードを逆コンパイルして、なんとしても彼らのコードレビューを実行しました。
彼らも、彼らの結論を確認するために、コードレビューとともにいくらかの侵入テストをしました。

残念なことに（しかし、もっともなことだが）、レビューは深刻な問題をトップ１０のカテゴリーのうちの6つで発見しました。
問題のいくつかは、設計レベルの問題で、修正するためにかなり多くの人月の努力を必要とします。
それで、NationalはFront Endに戻って、彼らに結論を示して、再び彼らに無料で問題を解決するよう頼みました。 Front
End（今すっかり心配される）は、彼らの弁護士と問題に取り掛かると答えて、会議を去りました。
もっともなことだが、弁護士はNationalに決して反応しませんでした。

## 悪いからより悪いへ

そのため、NationalはFront Endを告訴する義務がありました。Front
Endが契約において必要とされる作業を実施しておらず、そして、彼らは問題を修正して、Nationalの弁護料を払うべきだと主張しました。
Front
Endは、コードが2年前にわたって開発されていたこと、彼らは支払いを受けていたこと、そして、それ故コードはNationalによって完全に受け入れられていたことという事実に基づき、棄却する反応を示しました。
彼らも、彼らが契約する時点で存在しなかった要件を満たさないことに対して責任があるとみなされることができないと択一的に主張しました。

双方は、今や弁護料、失われた生産性と風評被害に多くの数万ドルをつぎ込みました。
実際の訴訟費用に加えて、双方は質問に答えていて、書類をつくり、証言録取書のために、そして、裁判に準備している重要な時間を使いました。
環境が劇的に変わったので、Nationalアプリケーションの最初の開発者の多くはFront
Endを去りました、そして、彼らは崩壊の原因となりたくありませんでした。

## より良い方法?

この哀れな物語は、この問題を取り扱わない方法の良い例です。
この状況にある多くの会社が明らかにあります、そして、法律制度は良いありません打開策でありません。
若干の善と悪が双方の上にあるので、この混乱をきれいにするより良い方法を見ましょう、それから、私たちはこれらの問題が将来起こるのを防ぐことについての若干の考えで終わります。

最初に、双方に所属する誰でも、セキュアなWebアプリケーションを構築することがただきれいに見えるものを構築することより多くの努力をすると思う必要があります。
あなたが顧客であるならば、あなたはだまし取られる感覚を止めなければなりません。
あなたと構築者が問題を協議したならば、価格はほぼ間違いなくより高かったでしょう。
あなたは大多数の開発者にはセキュリティの大きな理解がない顧客にも取らなければならないので、それの代金を払うことなく脆弱性のないコードに期待することは合理的でありません。
結局のところ、あなたは多分、あなたが代金を払ったものを得たでしょう。
あなたがあなたのアプリケーションでセキュリティ問題を疑うならば、それらを無視しません。

しかし、あなたが開発者であるならば、ここで無実のふりをしません。
顧客がコードが脆弱性を持つかどうか尋ねたならば、あなたはほぼ間違いなくいいえと言ったでしょう。そして、何かあるとすれば、あなたはあなたの努力に対してあまり多くを加えなかったでしょう。
あなたは、本当に、セキュリティ要件をする時間をとらなければならなかったということを知っていて、それを構築して、きちんとテストしてもらいます。
大部分のこれらの脆弱性は長年十分理解されました、そして、彼らは避けるのが難しくありません。
あなたはあなたの会社が書いたコードで脆弱性を発見するか、疑いさえするならば、信頼できる行いはあなたの顧客に知らせることになっています。
実際、あなたは顧客に警告する法的義務があってもよいです - ただ不完全なブレーキで車を彼らに売ったように
大部分の買い手は、あなたが進んでこの情報を提供したという事実を尊重して、問題を解決するために、あなたと努力します。

`あなたが裁判所で終わるならば、誰も勝ちません。`
`あなたの宿題をして、それを考え出します。`

この状況の当事者のために唯一の穏やかなものは、問題を解決することと関係している経費を共有する方法を見つけ出すことです。
あなたがこの状況にいるのに気づくならば、最初の行いはあなたの懸念を議論して、考えられるあらゆる問題を解決する計画を提案するために他の関係者に会うことです。
実のところ、あなたが仕事をすることに同意していたとき、どちらの関係者も考えなかったソフトウェアに脆弱性があります。
アプリケーションが修正するためにとりそうであるものの正確な評価を実行するために、独立した第三者について同意します。
双方が結論から利益を得るので、このレビューのコストを共有することは合理的です。
会議は、この状況で責任を割り当てる用語があるかどうか確かめるために、契約言語の慎重なレビューも含まなければなりません。

完全性を確実にするために、第三者レビューは、コード分析といくらかの侵入テストを含まなければなりません。
理にかなった最低限度にWebアプリケーションのために基づいている結論を保つために、レビューがOWASPトップ１０に集中することは、合理的です。
レポートはどんな結論の詳細な記述でも含まなければなりません。そして、コードで間違っていることにちょうど集中します。
レビュアーは、これらの判断をするためにコードへのアクセスを必要として、大きなコードレビュー・スキルを必要とします。
そのうえ、第三者は顧客の企業の具体的な状況で、瑕疵と関連したリスクを推定しなければなりません。

一旦あなたには独立した第三者から問題の正当と認められるリストがあるならば、双方は再び、彼らを修正させる計画をつくることに応じるべきです。
会議の目的は、開発者がどの問題を解決するか、修正がどれくらい難しいか、そして、誰が修正の代金を払いそうか確認しなければならないことになっています。
あなたが若干の見解の一致をここで見つけることができないならば、双方が裁判所で終わる、そして、弁護士だけが勝つことを肝に銘じます。

## 裁判所で起こること

仕事中にそれほど多くの可変部分があるので、これは難問です。
しかし、私の最高の推測は、裁判所が結局なんとしても中間をとることになるということです。
大部分の裁判所はこれらの脆弱性で技術的な問題を理解しそうでないので、彼らは外部標準と工業慣行に目を向けます。
これは専門家証人の闘争として終わります。そして、何人かがこれらの脆弱性が25年の間十分理解されたと言います。そして、他の人が大部分の開発者がセキュリティを理解しない、そして、標準がないと主張します。
最後に、裁判所は何に対して誰に責任があるかについて決定することができそうでありません。
彼らは開発者に有利な決定を下すかもしれません。そして、開発者をはっきりと定まっていなくて、工業慣行でない要件に保持することが不当であると思います。
他方、彼らは、開発者が知っていたか、これらの脆弱性について知っていなければならなかった理論に関して、顧客に簡単にあてはまることができて、したがって彼らのソフトウェアで彼らを防ぐための処置をとらなければなりませんでした。

`いずれの方法でも、これらの問題を修正するためのコストは、問題について訴訟するためのコストにより小さく見えます。`
`それで、あなたのパートナーのことをよく知るようになり、それを解決します。`

## 契約に記載がないとき何を起こるべきでしょうか

契約が問題について語られていないとき、法律はそれが関係者が意味したと思うことで欠けている条件に記入します。
これらの「デフォルト」条件は、制定法、UCC、取引慣行と多くの他の出所から来ます。
しかし、アプリケーション・セキュリティは十分に新しくて、裁判所が事件を決定するためにもたれるかもしれないかは誰にもわからないことであることほど十分に速く動いています。
それで、ただしばらく、立法者帽子をかぶろうとして、起こるべきであることを決定しようとしましょう。

デフォルト契約の条件がゼロ・セキュリティであるならば、世界はより良い場所であるでしょうか？ いいえ、これは適切な答えではありえません。
これは、あなたが特にそれを大声で呼ばない限り、開発者には彼らのコードをセキュアにする義務がないことを意味します。
開発者には、かなりよく理解されている脆弱性を避ける義務がありません。
これは買い手にすべての重荷を与えます。そして、その人はどんな脆弱性が起こるかもしれないかについてわかっているあまり良い立場にありません。
それで、このアプローチは、とても経済的に能率が悪いです。

しかし、反対の極端を想像します、そこで、契約が静かであるならば、開発者は完全にセキュアなアプリケーションを生産するために必要とされます。
これも、適切な答えではありえません。
一般に、問題を避ける最もよい立場で関係者に義務を与えることは、最も効果的な結果を生産します。
しかし、完全にセキュアなコードを作成することが実質的に不可能であるので、これはソフトウェア構築者のために無限責任をつくります。
明らかに、これは彼らの技能を実践するソフトウェア・メーカーの能力に、劇的な影響を及ぼします。
したがって、裁判所は問題について語られていない契約に、なんらかの基本的なセキュリティ要件を読み取らなければなりません。
リストは、話題が議論されたならば、双方が同意しただろう要件を含まなければなりません。
OWASPトップ１０のそれらのようなかなりよく理解されているセキュリティ脆弱性は、理にかなった出発点です。
しかし、買い手と構築者がプロジェクトのために現実的なセキュリティ要件を考え出して、それらを契約書（あなたが問題を無視するならば裁判所が考え出すものに頼ることよりもむしろ）に取り込むならば、それははるかによりよいでしょう。

## 次は?

うまくいけば、大部分の読者は現在この状況になくて、ただそれが将来起こるのを防ぐのが好きです。
適切な方法は、プロジェクトのためにどれくらいよいセキュリティ・ニーズがあるかについて、具体的な契約の条件を準備することです。

Dave Thomasは、品質はあなたが前もって顧客と協議する要件の一部でなければならないと書きました。
NASAは、コードの1行につきだいたい1,000ドルを使います。
非数学専攻のあなたにとって、それは取るに足らない1000行のプログラムのためでさえ100万ドルです。
そして、彼らがソフトウェア品質の上で素晴らしい記録をとるにもかかわらず、彼らはまだ時折調査を失うか、ソフトウェア問題のため、ロケットを衝突させます。

Webアプリケーションの正当な業務理由がセキュリティの異なっているレベルで、セキュリティ（品質のような）はソフトウェア構築者と買い手が協議しなければならない何かです。
買い手は、もちろん、まず最初に、あらゆる脆弱性なしでソフトウェアを期待しそうです。 これは、もちろん、現実的でありません。
構築者、少なくとも、歴史があらゆるガイドであるならば、機能要求を満たすソフトウェアを構築して、まったくセキュリティについて心配したくなさそうです。
デフォルト法律規則が全く不明で、完全にセキュリティを交渉から省くことも適切でありません。

ソフトウェア・構築者と買い手は、以下のような質問に取り組む率直な議論をする必要があります：\*どんな種類のインシデントが、深刻である（例えば暴露、変造、サービス妨害）と思われますか？

  - すべての開発者は、セキュリティの訓練をされなければなりませんか？
  - あなたは、アプリケーションのために文書化されたセキュリティ方針やセキュリティ要求事項を望みますか？
  - あなたは、セキュリティ設計とメカニズムの詳細なドキュメンテーションを望みますか？
  - あなたは、デザインのセキュリティ・レビューを望みますか？
  - あなたは、侵入テストが配備の前にされることを望みますか？
  - あなたは、コードがセキュリティの専門家によってレビューされることを望みますか？
  - 誰が、道の下で発見されるセキュリティ問題を解決して、危険を引き受けますか？

買い手は、強化されたセキュリティのために若干の追加料金があること、また、もしこれらのセキュリティ・サービスを断るならば、より安い価格を得ることができることを期待すべきです。
契約の出発点として、あなたはセキュリティに影響を及ぼすどんな種類のでもどんなバグのためにでも開発者にすべての重荷を与える厳罰を伴うコード完全性保証を考慮することを期待してもよいです。
少なくとも、用語は非常に明白です、しかし、開発者に対する潜在的責任はよろめいています。

## 結論

それで、あなたがソフトウェア開発を外部調達しているならば、あなたの開発者と話します。
彼らがあなたのセキュリティ・ニーズを理解することを確認します。
それを契約に入れることを確認します。
あなたは、ただあなたがどれくらいのセキュリティの代償を払う気があるかといういくらかの難しい質問に答えなければならないかもしれません。
あなたがソフトウェア開発者であるならば、あなたがどんなセキュリティを提供しているかについて明確にします、そして、それをします。
ソフトウェアが生産中である後、セキュリティ脆弱性が発見されるならば、それが誰の責任であるかについて理解します。

[Category:OWASP Legal Project](Category:OWASP_Legal_Project "wikilink")