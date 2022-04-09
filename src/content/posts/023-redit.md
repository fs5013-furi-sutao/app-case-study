---
template: blog-post
title: Reddit - 世界を動かす井戸端会議
slug: /reddit
date: 2022-04-02 08:00
description: 掲示板型ソーシャルニュースサイト
featuredImage: /assets/023-reddit/reddit-header.png
---

アプリ開発のヒントとなるように、Reddit の巧みな仕組みを解説していきます。

Reddit  
https://www.reddit.com/

Reddit は、2005年のデビュー以来、デザインがあまり変わっていないため、少し退屈に見えるかもしれません。しかし、このサイトをディスカッション用のテキストベースのフォーラムとしか考えていない場合は、Reddit の側面を見逃していることになります。

<br />

### Reddit の創業者

この Reddit の歴史は長く 2005 年から存在しており（Facebookの誕生が2004年）、創設者 Steve Huffman (右)と Alexis Ohanian(左)が当時22歳の時にマサチューセッツで設立しました。創設者のアレクシス・オハニアン氏は、「Reddit」をはじめ、「Evernote」や「Grubwithus」など、数々のスタートアップ企業で実績を持つ人物です。

`Reddit 創業者`<br />
![Reddit](./assets/023-reddit/reddit-ceo.png)

設立から5年間はアクセス数に伸び悩んでいましたが、2010年頃から徐々に利用者が増え始め、2019年12月の時点で月間アクティブユーザーが4億3000万人に達するまでに成長しています。これは、2018年の第二四半期時の月間アクティブユーザー数が3億3000万人だったことから、2年未満で1億人のアクティブユーザーを獲得したのです。

<br />

## Reddit とは

日本では知名度が低い Reddit。

The front page of the internet（インターネットのトップページ）とも呼ばれる Reddit は、世界に5番目に人気のあるサイトで、4億3000万人のユーザがいます。

毎月、ユーザはこのソーシャルニュース集計サイトで300億ページ以上を閲覧しています。

ユーザのフォローやリーチではなく、ユーザがコンテンツを生み出し、それをユーザが見に来るという、エコシステム（循環型社会）の形成。

つまり、これはシステムだけ用意すれば、運営側はコンテンツを継続的に作っていく必要はない。

ユーザ自身がユーザを呼ぶ、どんどんと質の高いコンテンツが勝手に自動増殖する、自己循環型のプラットフォームができあがっているといっていいかと思います。

しかも、このエコシステムは偶然形成されたものではなく、Reddit によって緻密に組み上げられた結果なのです。

`Reddit`<br />
![Reddit](./assets/023-reddit/reddit-screenshot.png)

<br />

## Reddit の基本

Reddit ユーザーは、コンテンツの共有、投票、コメントを行うことができます。

ユーザーが送信されたコンテンツを気に入った場合、ユーザーはそれを賛成（Upvote）します。これらの賛成票は、コンテンツをページのさらに上に移動し、他の人に見られる可能性が高くなります。 提出物が低品質、スパム、過度に宣伝的である、またはその他の方法で基準を満たしていない場合、彼らはそれを反対票を投じることができ、その結果、その地位が低下します。

Reddit はまた、投稿やコメントに賛成票と反対票を使用してカルマ（Karma）をポイント計算します。

このポイントはあなたの公開プロフィールに表示され、他の人があなたがどれだけアクティブであるか、そして Reddit へのあなたの投稿が好評であるかどうかを確認することができます。

<br />

## カルマとは何ですか？

まずは、賛成投票（Upvote）と反対投票（Downvote）という機能。

これは基本的に、誰かが Reddit にコンテンツを投稿すると、他のユーザーがそれを見て「好き（いいね）」か「嫌い（よくないね）」の意見を表明するものです。

すべての Reddit の投稿またはコメントの横には、賛成ボタンと反対投票ボタンがあります。これらのいずれかをクリックすると、投稿に正または負のカルマ（Karma）が与えられます。正のカルマは投稿のポイント数を増やし、負のカルマはその数を減らします。

Upvote されるコンテンツは通常、優れたコンテンツです。Reddit をよく見ているユーザーは、Upvote や Downvote をクリックしてれます。

`Upvote と Downvote`
![Upvote と Downvote](./assets/023-reddit/upvote-downvote.png)

Reddit は、可能な限り最高のコンテンツをユーザーに表示する方法としてKarma を使用します。

たくさんのポイントを含む賛成のコメントや投稿は、ページの上部に表示され、さらに多くの人々がそれらを見て賛成することになります。反対票を投じられたコメントは、スレッドの最後に表示されます。投稿が十分に反対票を投じられた場合、最終的に非表示になり、クリックして展開する必要があります。

投稿やコメントには、カルマ数の横に小さな十字記号（†）が付いている場合があります。これは、投稿が物議を醸していることを示しています。つまり、賛成票と反対票の数が同程度であることを意味します。

それぞれの投稿につけられた Upvote と Downvote の数は、だれでも確認できる場所に表示されています。ユーザーからすると、人気や品質が数値化されていることになるので、とてもありがたい機能です。

<br />

## カルマは何をしますか？

Karma には本質的な価値はありません。そのため、Reddit のヘビーユーザー（Redditor）は、取得しているのは「架空のインターネットポイント」でしかない、と冗談めかして言うこともあります。

ただし、カルマが多く、投稿履歴が豊富なユーザーは、サイトで非常に活発に活動していることを示しています。

カルマを何かと交換することはできませんが、いくつかの Subreddits では、コメントや投稿を行うために最小限のカルマが必要です。

これは、サイト外の人々との出会いや取引を伴うマーケットプレイスの Subreddits に特に当てはまります。複数の投稿にまたがって多くのカルマを持っていると、ユーザーはより信頼できる人物として扱われます。

<br />

## Subreddits とは何ですか？

Web サイトは、特定のトピックに焦点を当てたコミュニティであるSubreddits に編成されています。

サブレディットとは、Reddit の中のカテゴリーのこと。ツイッターで言えば、ハッシュタグみたいなモノ。基本的に Subreddits の趣旨にあった投稿をするというルールになっています。

Subreddits は、r/＊＊＊＊ と表記されており、つまり URL によって自分が今どこの Subreddits にいるかを知ることができるわけです。

`Subreddits`
![Subreddits](./assets/023-reddit/subreddits.png)

アクティブであるという基準を満たすのは13万だけですが、数でいうと 220万を超える数多くの Subreddits が存在します。 

Subreddits はバラエティに富んでおり、ほぼすべての分野に渡って Subreddits を見つけることができます。 例えば、信じられないほどニッチな猫の Subreddits も数多くあり、調べてみると驚くかもしれません。

一部の企業は独自のブランドコミュニティを確立していますが、ほとんどの Subreddits はユーザーによって作成されています。

Reddit には、ほぼすべての Subreddits からサイトで最も人気のある提出物を集約する **r/All Subreddits** と、Subreddits に基づいてカスタマイズされたデフォルトのホームページもあります。

ページの右側には Subreddits の詳細な説明が書かれています。下の図のような統計においては、133の読者と6人のオンラインということがわかります。これは、Reddit アカウントを持つ133人がこの Subreddits をサブスクライブ（購読）し、その中の6人が現在オンラインになっていることを示します。

`コミュニティの詳細`
![コミュニティの詳細](./assets/023-reddit/community-details.png)

各 Subreddits には、独自のモデレーター、ルール、ユーザーのサブセット、音声、および優先コンテンツタイプを備えた、異なるコミュニティの雰囲気があります。 

`Subreddits 独自のルール`
![Subreddits 独自のルール](./assets/023-reddit/rules.png)

Reddit は、ブランドにとって敵対的な環境であるという評判を得ており、例えばビデオゲームブランドの Electronic Arts は、Reddit の歴史の中で最も否定的な投稿をしており、Subreddits **r/HaiCorporate** は、露骨なマーケティング活動を呼びかけ、あざけることに専念しています。

ただし、時間をかけて土地の配置を理解し、コミュニティへの貴重な貢献者になると、Redditに投稿することで、大勢の熱心で忠実な視聴者との永続的な関係を築く機会が得られます。

<br />

## GameStop事件

Reddit が近年ひと際目立つ存在となったトピックとして GameStop 事件が話題になりました。  

GameStop 事件とは、米国市場の投資アプリ Robinhood を利用していた個人投資家達（ロビンフッター）が、r/wallstreetbets 内で、投資行動を呼びかけ、個人投資家が結託し、空売りを仕掛けていた超巨大ヘッジファンド・メルビンキャピタルを倒産間際まで追い込んだ事件。

2021年1月に GameStop（GME）というアメリカに実店舗を展開するゲームストア会社の株価が突如としてはね上がっりました。これにより空売りを狙っていたウォール街のヘッジファンドが大損をすることになりました。

1月はじめに17ドル台だった GME 株は1月29日に約483ドル、去年一番低迷していたときの約28倍も高騰した。GME 株はテスラやアップルを抜き1月の取引額がNYダウでもっとも大きい銘柄となってしまったのです。

`GME 株急騰`
![GME 株急騰](./assets/023-reddit/game-stop.png)

この Reddit から始まった打倒ヘッジファンド運動に、テスラCEOのイーロン・マスクもツイートで賛同し、事態は一般人 VS ウォール街の億万長者の様相を呈し始めました。

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Gamestonk!! <a href="https://t.co/RZtkDzAewJ">https://t.co/RZtkDzAewJ</a></p>&mdash; Elon Musk (@elonmusk) <a href="https://twitter.com/elonmusk/status/1354174279894642703?ref_src=twsrc%5Etfw">January 26, 2021</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<br />

## 人気の Subreddits

Reddit の仕組みや概要を知ったところで、最後に Reddits で人気となっている Subreddeits を見ていきましょう。

<br />

### r/IAmA

https://www.reddit.com/r/IAmA

AMA（Ask Me Anything）と言われる人気の Subreddits。

俳優・映画監督・宇宙飛行士などの超有名人から、コロンバイン高校銃乱射事件の生存者、機械の腕を持つ美女、NASAで働いていた天才高校生など、個性豊かな「なんか質問ある？」を受付けている。

Microsoft 元会長が Reddit に降臨

`ビル・ゲイツだけど質問ある？`
![ビル・ゲイツだけど質問ある？](./assets/023-reddit/bill-gates.png)

<br />

### r/MadeMeSmile

https://www.reddit.com/r/MadeMeSmile/

笑顔にさせてくれるビデオクリップであふれている。

<div style='position:relative; padding-bottom:calc(75.00% + 44px)'><iframe src='https://gfycat.com/ifr/RichJadedBeardeddragon' frameborder='0' scrolling='no' width='100%' height='100%' style='position:absolute;top:0;left:0;' allowfullscreen></iframe></div>

<br />

### r/NatureIs****ingLit

https://www.reddit.com/r/NatureIsFuckingLit/

あなたが見たこともない自然の驚くべき瞬間。

<div style='position:relative; padding-bottom:calc(56.25% + 44px)'><iframe src='https://gfycat.com/ifr/DimpledUnconsciousHaddock' frameborder='0' scrolling='no' width='100%' height='100%' style='position:absolute;top:0;left:0;' allowfullscreen></iframe></div>

<br />

### r/nevertellmetheodds

https://www.reddit.com/r/nevertellmetheodds/

すべての論理に逆らう瞬間を目撃すること。

<div style='position:relative; padding-bottom: 125.00%'><iframe src='https://redgifs.com/ifr/narrowilliteratehammerheadshark' frameBorder='0' scrolling='no' width='100%' height='100%' style='position:absolute; top:0; left:0;' allowFullScreen></iframe></div><p><a href='https://redgifs.com/watch/narrowilliteratehammerheadshark'>via RedGIFs</a></p>

<br />

### r/whatcouldgowrong

https://www.reddit.com/r/Whatcouldgowrong/

人々が考えていないときに起こること。

<div style='position:relative; padding-bottom:calc(53.91% + 44px)'><iframe src='https://gfycat.com/ifr/ActualTeemingArabianhorse' frameborder='0' scrolling='no' width='100%' height='100%' style='position:absolute;top:0;left:0;' allowfullscreen></iframe></div>

<br />

### r/ThisBlewMyMind

https://www.reddit.com/r/ThisBlewMyMind/

驚かされる準備を。おそらく「おっ」と言うでしょう。

<div style='position:relative; padding-bottom:calc(56.33% + 44px)'><iframe src='https://gfycat.com/ifr/OblongFavoriteGiraffe' frameborder='0' scrolling='no' width='100%' height='100%' style='position:absolute;top:0;left:0;' allowfullscreen></iframe></div>

<br />

### r/wholesomegifs

https://www.reddit.com/r/wholesomegifs/

世界にはたくさんの良いものがあることを思い出してください。

<div style='position:relative; padding-bottom:calc(124.69% + 44px)'><iframe src='https://gfycat.com/ifr/HideousGleefulCats' frameborder='0' scrolling='no' width='100%' height='100%' style='position:absolute;top:0;left:0;' allowfullscreen></iframe></div>

<br />

### r/ChildrenFallingOver

https://www.reddit.com/r/ChildrenFallingOver/

ほんの少しのシャーデンフロイデ（誰かが失敗した時に思わず湧き起こってしまう喜びの感情）のために。

<div style='position:relative; padding-bottom:calc(56.11% + 44px)'><iframe src='https://gfycat.com/ifr/LameDopeyFrog' frameborder='0' scrolling='no' width='100%' height='100%' style='position:absolute;top:0;left:0;' allowfullscreen></iframe></div>

<br />

### r/DadReflexes

https://www.reddit.com/r/DadReflexes/

父親が英雄的な救済をするのを見たい場合。

<div style='position:relative; padding-bottom:calc(56.11% + 44px)'><iframe src='https://gfycat.com/ifr/MindlessUnluckyBellfrog' frameborder='0' scrolling='no' width='100%' height='100%' style='position:absolute;top:0;left:0;' allowfullscreen></iframe></div>

<br />

### r/oddlysatisfying

https://www.reddit.com/r/oddlysatisfying/

ここ数年、ネットで密かに増殖をし続けている Oddly Satisfying Video。

Oddly satisfying videos  
https://en.wikipedia.org/wiki/Oddly_satisfying_videos

視聴者が心地よいと感じる出来事や特定のアクションを収集している。

<iframe width="560" height="315" src="https://www.youtube.com/embed/W-N2aKzPF_Y?autoplay=1&mute=1&playsinline=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br />

### r/aww

https://www.reddit.com/r/aww

ペット愛好家、またはペットを飼うことの喜びを体験したい人へ。

<div style='position:relative; padding-bottom:calc(56.11% + 44px)'><iframe src='https://gfycat.com/ifr/SandySplendidAbyssiniangroundhornbill' frameborder='0' scrolling='no' width='100%' height='100%' style='position:absolute;top:0;left:0;' allowfullscreen></iframe></div>

<br />

### r/GetMotivated

https://www.reddit.com/r/GetMotivated

誰もみな達成したい目標を持っている。だから時々、励ましてほしくなる。

`簡単なことは長続きしない。続けることは簡単ではない。`
![ビル・ゲイツだけど質問ある？](./assets/023-reddit/what-comes-easy.png)

<br />

### r/YouShouldKnow

https://www.reddit.com/r/YouShouldKnow

YSK と呼ばれるお金、時間、そしてあなたの健康に役立つヒント。それと豆知識。

[食洗機の正しいセットのしかた](https://www.reddit.com/r/YouShouldKnow/comments/csj1xc/ysk_that_you_should_mix_types_of_cutlery_in_the/)、うまくいかなかった [音声メールを最初からやり直す方法](https://www.reddit.com/r/YouShouldKnow/comments/cw7enr/ysk_if_youre_leaving_a_rambling_voicemail_you_can/)、[スリ被害から身を守る方法](https://www.reddit.com/r/YouShouldKnow/comments/cs6n9r/ysk_that_you_shouldnt_visibly_check_for_your/)など、思いつく限りあらゆるトピックが網羅されている。

`YouShouldKnow`
![YouShouldKnow](./assets/023-reddit/you-should-know.png)

<br />

### r/malefashionadvice と r/femalefashionadvice

https://www.reddit.com/r/malefashionadvice

https://www.reddit.com/r/femalefashionadvice

自分の着こなしに自信がない。服のコーディネートがどうもいまいち。気候がぜんぜん違うところへ旅行するので、服装のヒントがほしい―そんなときのアドバイスなら、この2つのサブレディットをどうぞ。着こなしから、おすすめの服、今の流行、ウォードローブを充実させる秘訣まで、アドバイスがたくさん載っています。

`malefashionadvice`
![malefashionadvice](./assets/023-reddit/male-fashion.png)

<br />

### r/houseplants

https://www.reddit.com/r/houseplants

観葉植物のことなら、何から何まで載っています。具体的なトピックにフォーカスしたすばらしいサブレディットのひとつで、実に見ごたえがあります。自宅の観葉植物について、育て方のアドバイスを探せるだけでなく、ほかの人が育てている自慢の植物の写真も紹介されています。購入のアドバイスや生育のヒントを探すにも、自分の育てた植物を披露するにも、最高の場所です。

`houseplants`
![houseplants](./assets/023-reddit/house-plants.png)

<br />

### r/changemyview

https://www.reddit.com/r/changemyview

今の世界には、意見が違う人に対して、かたくなな態度や、ひどいときにはヘイトが横行してしまう残念な風潮が広がっています。**r/changemyview** は、あちこちで見かける侮辱や悪口雑言を避け、理性的な話し合いをする場です。

<br />

### r/IWantToLearn

https://www.reddit.com/r/IWantToLearn

[ゲームのプログラミング](https://www.reddit.com/r/IWantToLearn/comments/cw5th3/iwtl_how_to_be_a_game_developer/)、[手品の技術](https://www.reddit.com/r/IWantToLearn/comments/cw4n9g/iwtl_magic_tricks_mostly_sleight_of_hand_card/)、[効率的な情報収集術](https://www.reddit.com/r/IWantToLearn/comments/cvj3v2/iwtl_effective_methods_to_absorb_information/) など、何かを新しく学びたくなったときは、**r/IWantToLearn** が手ほどきをしてくれます。このサブレディットで網羅されているトピックは膨大なので、追いつくのは大変ですが、自分を磨こうと思っているのであれば理想的なリソースです。

<br />

### r/mildlyinteresting

https://www.reddit.com/r/mildlyinteresting

何の役にも立たない、人間のちょっとした気づき。でも何でこんなにも幸せを与えてくれるのだろう。

`両親の家の隣に住む素敵な高齢女性が玄関先に残したメモ。そこには「お宅の車のタイヤの傍に鹿の赤ちゃんが眠っているので気を付けてあげてね」と書かれてあった。`
![手紙](./assets/023-reddit/letter.png)
![鹿の赤ちゃん](./assets/023-reddit/baby-dear.png)
