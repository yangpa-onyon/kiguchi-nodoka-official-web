---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: about
title: 機口喉歌
title_override_in_header: ホーム
heading: " "
lang: "ja"
---

![機口喉歌](/assets/images/images/kiguchi_nodoka.png)

# 機口喉歌?

機口喉歌は足立レイにインスピレーションを受けて作られた無生物UTAU音源です。声優の録音なしで、物理ベースの発声器シミュレーションだけで声を作り出します。

声帯で作られた音が舌、唇、鼻腔を過ぎて共鳴する過程を時間とともに実際のように変化させるので、単純な子音と母音のリストを越えて説得力のある音色で歌えるのが特徴です。

* [連続音日本語音源ダウンロード](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.2.0/KIGUCHI_NODOKA_JA.zip)

* [VCCV英語音源ダウンロード](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.2.0/KIGUCHI_NODOKA_EN.zip)

* [VCV韓国語音源ダウンロード](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.2.0/KIGUCHI_NODOKA_KO.zip)

* [連続音トキポナ音源ダウンロード](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.2.0/KIGUCHI_NODOKA_TOK.zip)

  * トキポナは別の[ポネマイザー](https://github.com/yangpa-onyon/kiguchi-nodoka-official-web/releases/download/beta_0.2.0/TokiPonaPhonemizer.dll)のインストールが必要です。

* ~~CVV中国語音源ダウンロード~~ Coming soon...

* ~~VCVタガログ語（フィリピン語）音源ダウンロード~~ Coming soon...

* すべての音源はリサンプラーとしてdoppeltlerをお勧めします。

<iframe width="560" height="315" src="https://www.youtube.com/embed/slL1QwSWpvI?si=WrZ83hVeWAhk1DkZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

(原曲: [Portal 2: End Credits Song 'Want You Gone' by Jonathan Coulton](https://youtu.be/dVVZaZ8yO6o?feature=shared))

# 発声機関シミュレーション？

人の声はしばしば「ソース - フィルタモデル」として説明できます。

* ソース：声帯が振動し、基本振動数を持つ音を作り出します。
* フィルタ：その音が舌、唇、口腔、鼻腔などの狭く曲がった通路を通過し、複数の周波数帯域が増幅、減衰され、フォルマント周波数が作成されます。

よく作られた無生物音源は、Vocalizerなどのフォルマントフィルターを使って音を作ります。これは単純なコレクションを作成するのに役立ちますが、音節の複雑さが高い言語になるほど、その制限は明らかになります。

* 時間が経つにつれて、聖徒の形が滑らかに変わる二重コレクション
* 破裂音（p、t、kなど）、摩擦音（s、fなど）などの瞬間的または乱流性を持つ特徴
* 子音群（sp、str、zntなど）

そのため、これまでの無生物音源は、日本語などの音節複雑度の低い言語に主に合わせられており、そのコミュニティも日本や周辺国のコミュニティに限られていました。木口能之は、このような従来の無生物音源製作方式とは異なる方法で作られました。

* 聖度全体を連続した小さな管に分け、各管の断面積の変化に応じて生じる反射/伝達を物理的にシミュレートします。
* 声帯のソース（鳴り、奇跡など）を時間とともに変え、破裂音と摩擦性乱流を聖度に物理的に注入します。
* 舌、唇の自然な位置変化を通じてフォルマントが自然に移動するようにします。

その結果、木口能之は、二重母音や複雑な子音群など、従来のやり方で実現するのが難しかった発音の中で明確な発音を示し、数多くの言語をサポートできる構造を持っています。声優のない無生物音源ですが、発声器官の原因と結果を追って作られた音で説得力のある音色を得ることができます。