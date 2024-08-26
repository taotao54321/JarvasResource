+++
title = "TAS (1:02:14.82)"
+++

## ムービー

[Jarvas-tas-20240816.fm2](Jarvas-tas-20240816.zip) (FCEUX 2.6.6, 224458 frames)

Encode: [part1](https://www.nicovideo.jp/watch/sm44003991), [part2](https://www.nicovideo.jp/watch/sm44004001)

2コン技 (UUDDABAB でスタート地点へワープ) を使っている。これは説明書には載っていないが、通常プレイでは詰み防止のために事実上必須であり、またゲーム内で割とストレートなヒントが得られるので問題ないと判断した。
しかし、TASVideos への投稿を考えるならば事前にフォーラムなどで確認すべきだろう。


## チャート

従来の TAS/RTA チャートからの主な改善点:

* 名声値稼ぎを先に済ませることで、タクテカ〜オシーランドへの訪問回数を 1 回に抑えた (従来は 2 周していた)。
* 各所に存在する手形の落とし物 (手形所持数が 0 の場合のみ 1 枚拾える) の活用。
* [パタンの町からキネラシア城へのワープ](@/map/map-12/_index.md#event-20-202)の利用。
* [兵力バグ](https://taotao54321.github.io/blog/nes-jarvas-force-glitch/)の利用。

### [ユース地方](@/map/map-01/_index.md)

後ほど[アネイデアの町](@/map/map-12/_index.md)で[討伐クエスト](@/map/map-13b/_index.md#event-16-240)報酬の金 250 を得るため、それまでに討伐数を 50 稼いでおく。傭兵やアマゾネスなどのNPCもカウント対象であり、これらはレベル 0 初期武器でも一撃で倒せるので積極的に狙っていく。

HPに余裕がないので、無駄な被弾は避ける。[オシーランド地方](@/map/map-11/_index.md)に到達するまではノーダメージで行く。

* 手形を拾う。
* ベルトを入手。
* ブルガの町へ。
  - 船小屋からバフィン島へ。
* 壺を入手。
* 2コン技でスタート地点へ。
* ブルガの町へ。
  - クエスト屋で壺を売り、金 200 入手。初期所持金と合わせて金 280 となる。
  - ギルドで格闘士になる。
  - ギルドで手形を 1 枚買い、名声値を 3 上げる。名声値 3, 金 30, 手形 2 となる (後ほど関所で通行料を取られるので金は実質 0)。
* 2コン技でスタート地点へ。
* 関所から[ラタニア北地方](@/map/map-04/_index.md)へ。手形 1 となる。

ここでの壺クエストはおそらくカットできないと思われる。[ラタニア北地方](@/map/map-04/_index.md)にも手形は[落ちている](@/map/map-04/_index.md#event-93-245)が遠すぎる。また、ここで名声値 3 を稼いでおかないと後の金策が苦しい。

職業はおそらく格闘士が最適だと思うが、そこまで厳密には検証していない。

### [ラタニア北地方](@/map/map-04/_index.md)

* 関所から[ラタニア南地方](@/map/map-08/_index.md)へ (通行料 100)。金 0, 手形 0 となる。

### [ラタニア南地方](@/map/map-08/_index.md)

* 関所を出てすぐのアマゾネス出現ポイントで討伐数を稼ぐ。
* なくしたハートを入手 (要: ベルト)。
* アネイデアの町の西で占い師から切り株ワープを習得。
  北回りで来て予めスクロール調整しておくとよい。
* アネイデアの町へ。ここまでに討伐数を 50 にしておく。
  - クエスト屋で[討伐クエスト](@/map/map-13b/_index.md#event-16-240)報酬の金 250 を得る。金 250 となる。
  - クエスト屋の裏口を通る。右から行く方が少し早い(他の店の裏口も同様)。
  - 船小屋から[リカントス地方](@/map/map-05/_index.md)へ。

### [リカントス地方](@/map/map-05/_index.md)

後ほど再度[アネイデアの町](@/map/map-12/_index.md)で[討伐クエスト](@/map/map-13b/_index.md#event-16-240)報酬の金 250 を得るため、それまでに討伐数を 50 稼いでおく。

ここでパタンの町のギルドに行くまでに経験値を 100 以上稼ぎ、レベル 1 になれるようにしておく。

* 曼荼羅を入手。
* 手形を拾う。
* パタンの町へ。
  - 近接武器屋の裏口を通って長老の家へ行き、骨ワープ習得 (要: なくしたハート)。
  - 北西の墓の前で曼荼羅を使い、パタンの洞窟への扉を開ける。
  - パタンの洞窟へ。出口からリカントス地方の砂漠へ。
* 砂漠の北東に出現する魔道士から石ワープを習得。
* ひかりごけを入手。
* パタンの町へ。ここまでに経験値を 100 以上稼いでおく。
  - クエスト屋でひかりごけを売り、金 400 入手。金 650 となる。
  - ギルドで手形を 2 枚買い、名声値を 9 上げる (このときレベルも上がる)。レベル 1, 名声値 12, 金 0, 手形 3 となる。
  - 船小屋からヘレナ島へ。
* ハーモニカを入手。
* 骨ワープで大陸へ戻る。
* 北東の関所から[キネラシア南地方](@/map/map-06/_index.md)へ。手形 2 となる。

ここでレベル 1 にしておかないと、後に[オシーランド地方](@/map/map-11/_index.md)へ渡った直後の敵の弾に耐えられずゴリ押し突破ができない。

ここでの手形購入は必須ではないが、[キネラシア南地方](@/map/map-06/_index.md)、[エウロン東地方](@/map/map-02/_index.md)での手形拾い(特に後者はやや遠い)をカットできるので結果的に早くなる。

### [キネラシア南地方](@/map/map-06/_index.md)

* 北の関所から[エウロン東地方](@/map/map-02/_index.md)へ。手形 1 となる。

### [エウロン東地方](@/map/map-02/_index.md)

* 東の関所から[キネラシア北西地方](@/map/map-02/_index.md)へ。手形 0 となる。

### [キネラシア北西地方](@/map/map-02/_index.md)

* 手形を拾う。
* 切り株ワープで[キネラシア南地方](@/map/map-06/_index.md)へ (外見は木だが、実際は切り株)。

### [キネラシア南地方](@/map/map-06/_index.md)

* 星のかけらを入手 (要: ハーモニカ)。
* 石ワープで北西の半島へ。
* 北の関所から[エウロン東地方](@/map/map-02/_index.md)へ。手形 0 となる。

### [エウロン東地方](@/map/map-02/_index.md)

* 手形を拾う。
* 東の関所から[キネラシア北西地方](@/map/map-02/_index.md)へ。手形 0 となる。

### [キネラシア北西地方](@/map/map-02/_index.md)

* 手形を拾う。
* 東の関所から[キネラシア北東地方](@/map/map-03/_index.md)へ。手形 0 となる。

### [キネラシア北東地方](@/map/map-03/_index.md)

* ペイチンの町へ。
  - クエスト屋で星のかけらを売り、金 5000 入手。金 5000 となる。
  - ギルドで手形を 1 枚買い、名声値を 98 上げる。名声値 110, 金 0, 手形 1 となる。
* 西の関所から[キネラシア北西地方](@/map/map-02/_index.md)へ。手形 0 となる。

### [キネラシア北西地方](@/map/map-02/_index.md)

* 切り株ワープで[キネラシア南地方](@/map/map-06/_index.md)へ。

### [キネラシア南地方](@/map/map-06/_index.md)

* 隊長を 200 加える。
* 星のかけらを入手 (要: ハーモニカ)。
* 石ワープで北西の半島へ。
* 手形を拾う。
* 西の関所から[リカントス地方](@/map/map-05/_index.md)へ。手形 0 となる。

### [リカントス地方](@/map/map-05/_index.md)

* パタンの町へ。
  - [惑いの宿](@/map/map-13b/_index.md#event-240-150)から[タクテカ地方](@/map/map-09/_index.md)へワープ。

手形を拾って関所から行くルートもあるが、惑いの宿を使う方が約 12 秒早い。

### [タクテカ地方](@/map/map-09/_index.md)

* 手形を拾う。
* 船小屋からタクテカ大陸へ。
* タクテカ城を制圧 (要: ハーモニカ)。隊長 100 となる。
* グルカ兵を 300 加える。
* 船小屋から[リングワールド地方](@/map/map-10/_index.md)のマダガス島へ。

### [リングワールド地方](@/map/map-10/_index.md)

* 船小屋からリングワールド本島へ。
* 将軍を 250 加える。
* 船小屋から[オシーランド地方](@/map/map-11/_index.md)のジャバ島へ。

### [オシーランド地方](@/map/map-11/_index.md)

* 石ワープでオシーランド大陸へ。
  このときの敵弾はロスなしに回避することはできないと思われる。レベル 1 格闘士の場合、26 ダメージ受ける (残HP 4)。
* 海の涙を入手 (要: ハーモニカ)。
* 十字氷からオシーランド城の島へワープ (要: 曼荼羅、海の涙)。
* オシーランド城を制圧 (要: 将軍 20, 隊長 100, グルカ兵 300)。将軍 125, グルカ兵 150 となる。
* 切り株ワープで大陸へ戻る。
* クリスタルを入手。追尾型の敵が出現するため、飛び道具を食らいつつ適当に処理 (2 ダメージ受け、残HP 2)。
* 志願兵を 50 加える。
* 北の船小屋からニューの島へ。
* 切り株ワープで[ラタニア南地方](@/map/map-08/_index.md)の南西の島へ。

オシーランド城制圧後、隊長は不要となる。

### [ラタニア南地方](@/map/map-08/_index.md)

* 骨ワープで大陸へ。
* アマゾネスを 800 加える。
  スクロール調整を行った上でラタニア城北の湧きブロックを利用する。ここは他の敵の湧きブロックと隣接しているが、TAS ならばアマゾネスだけを出すのは容易。
* ラタニア城を制圧 (要: 志願兵+傭兵+グルカ兵+アマゾネス 1000)。将軍 62, 志願兵 25, グルカ兵 75, アマゾネス 400 となる。
* アネイデアの町へ。ここまでに討伐数を 50 にしておく。
  - クエスト屋で[討伐クエスト](@/map/map-13b/_index.md#event-16-240)報酬の金 250 を得る。金 250 となる。
  - ギルドで手形を 2 枚買い、兵力バグを 1 回行う。金 0, 手形 3 となる。
    兵力バグにより志願兵 1542, 傭兵 257, グルカ兵 4626 となる。
  - クエスト屋の裏口を通り、船小屋から[リカントス地方](@/map/map-05/_index.md)へ。

ここでの手形購入は以前と同様に[キネラシア南地方](@/map/map-06/_index.md)、[エウロン東地方](@/map/map-02/_index.md)での手形拾いをカットするため。

### [リカントス地方](@/map/map-05/_index.md)

* リカントス城を制圧 (要: グルカ兵 400, アマゾネス 400)。将軍 31, 志願兵 771, 傭兵 128 となる。
* 魔道士を 250 集める。
* 北東の関所から[キネラシア南地方](@/map/map-06/_index.md)へ。手形 2 となる。

リカントス城制圧後、グルカ兵およびアマゾネスは不要となる。

### [キネラシア南地方](@/map/map-06/_index.md)

* 北の関所から[エウロン東地方](@/map/map-02/_index.md)へ。手形 1 となる。

### [エウロン東地方](@/map/map-02/_index.md)

* 東の関所から[キネラシア北西地方](@/map/map-02/_index.md)へ。手形 0 となる。

### [キネラシア北西地方](@/map/map-02/_index.md)

* 手形を拾う。
* 東の関所から[キネラシア北東地方](@/map/map-03/_index.md)へ。手形 0 となる。

### [キネラシア北東地方](@/map/map-03/_index.md)

* 参謀を 250 加える。ペイチンの町から東の湧きブロックを利用する。ここは普通にやると地形的に効率が悪いが、スクロールさせてからセーブ->ロードすることで良い感じのスクロール調整ができる。
* ペイチンの町へ。
  - クエスト屋で海の涙を売り、金 5000 入手。金 5000 となる。
  - ギルドで手形を 4 枚買い、兵力バグを 1 回行う。手形 4 となる。
    兵力バグにより傭兵 7196 となる。
  - 薬屋で薬を 1 個買う。
* 西の関所から[キネラシア北西地方](@/map/map-02/_index.md)へ。手形 3, 傭兵 6297 となる。

ここで手形を多めに買うのは各所での手形拾いをカットするため (特に[キネラシア南地方](@/map/map-06/_index.md)での手形拾いは若干遠い)。

これ以降は金は不要。また、志願兵も不要となる。

### [キネラシア北西地方](@/map/map-02/_index.md)

* 西の関所から[エウロン東地方](@/map/map-02/_index.md)へ。手形 2, 傭兵 5510 となる。

### [エウロン東地方](@/map/map-02/_index.md)

* 薬を使い、HPを 50 回復。以降、死なない範囲でゴリ押ししていく。
* エウロン城を制圧 (要: 将軍 30, 魔道士+参謀 500)。傭兵 2755 となる。
* 南西の関所から[キネラシア南地方](@/map/map-06/_index.md)へ。手形 1, 傭兵 2411 となる。

### [キネラシア南地方](@/map/map-06/_index.md)

* 西の関所から[リカントス地方](@/map/map-05/_index.md)へ。手形 0, 傭兵 2110 となる。

### [リカントス地方](@/map/map-05/_index.md)

* パタンの町へ。
  - [十字岩からキネラシア城へワープ](@/map/map-12/_index.md#event-20-202) (要: 星のかけら)。

### [キネラシア北西地方](@/map/map-02/_index.md)

* キネラシア城を制圧 (要: クリスタル)。傭兵 1055 となる。
* 手形を拾う。
* 東の関所から[キネラシア北東地方](@/map/map-03/_index.md)へ。手形 0, 傭兵 924 となる。

キネラシア城制圧後は2コン技で[ユース地方](@/map/map-00/_index.md)へ戻ることもできるが、ペイチンの町まで行って惑いの宿を使う方が約 6 秒早い。

### [キネラシア北東地方](@/map/map-03/_index.md)

* ペイチンの町へ。
  - [惑いの宿](@/map/map-13b/_index.md#event-240-150)から[ユース地方](@/map/map-00/_index.md)の南西の島へワープ。

### [ユース地方](@/map/map-01/_index.md)

* ユース城を制圧 (要: 傭兵 500)。
* エンディング。