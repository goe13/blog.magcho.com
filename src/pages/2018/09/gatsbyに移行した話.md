---
title: 'ブログをgatsbyに移行した話'
date: '2018-09-26'
category: '日記'
tags:
  - 'gatsby.js'
  - 'ブログ'
---

前は hatenablog を使っていたものの、自分でブログを構築したくなったので作ってみた。WordPress 等の CMS でやるにはメンテナンスが面倒なこともあって静的サイトジェネレータを使いました。一度 jekyll で作りましたが gatsbyjs を教えてもらってその表示速度に驚かされたのでこれはやるしかないと思い作りました。

gatsby.js は React ベースの静的サイトジェネレータです、つい最近 v2.0.0 になったばかりで公式のドキュメントにかきかけのところがあったりもしますが英語圏に情報が落ちているので大概のことはググればすぐに解決します。ただ日本語の情報が他のジェネレータ系に比べて少ないのでとっつきにくいと言われればそうなのですが最適化とか考えなくてもとりあえず作れば Gatsby がよしなにしてくれて爆速ブログが構築できるのでチャレンジしました。

React ベースということもあり、テーマをカスタマイズするには React のコンポーネント周りの知識があったほうがいいと思います、自分は今までなんとなくの知識しかなかったので、freeCodeCamp で一通り復習してから始めました。あとは gatsbyjs のチュートリアルや graphql のチュートリアル？なんかもやりました。

自分はブログを構築している間はとても楽しいんですが、どうも文章を書くのが億劫で今まで作ったいくつかのブログも 4 つぐらい構築してますが記事を書いたのは合わせても 10 個ぐらいだと思います。プログラムと比べて日本語はエディターが入力ミスを補完とかしてくれないからだと言い訳をしておきます。日本語力が欠如しているともいいます。なので今回こそは日頃から文章を書くように心がけます。

さて、自分で見直して見て読みずらくて自分の日本語力に自信をなくしたところで今回は終わり。今後しばらくは gatsby に関しての技術ネタを書く予定です、では。
