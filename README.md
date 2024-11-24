本章は放射生態学 radiation ecologyで必要な物理学的基礎を述べる。radiation ecologyのradiationとは光のことである。

光は生態系において一次生産を駆動する大切なエネルギー源であると同時に, 生物が環境を知覚したり生物同士（人間を含む）が互いにコミュニケーションに用いる情報伝達媒体でもある。従って光の科学的性質を理解することは重要である（注: 光のことを「放射」と呼ぶことがある。一般に「放射」と言えばα線やβ線のような粒子線も含むが, 本書ではそれらは考えない）。

## light, photon, quantum

光は我々の身近にあるので, 我々は光について体験的によく知っていると思っている。しかし光の科学（物理学）はそんなに簡単ではない。そもそも, 人類が光の科学的な性質を理解したのは20世紀以降なのである。その最も大きな困難は, 光が2つの側面を持つという事実である。すなわち, 「光子」という粒子としての側面と, 「電磁波」という波としての側面である。粒子と言えば砂やピンポン玉のようなものをイメージするし, 波と言えば海の波のようなものをイメージする。これらが同時に両立する何ものかをイメージすることはほとんど不可能だ。にもかかわらず, 光にはこのような二面性（duality）があることを受け入れたことで, 人は光を理解することができるようになった（注: イメージできないのに理解できるということに読者は戸惑うかもしれないが, 「現象を記述し予測できること」を理解と定義すれば, イメージできるか否かは理解とは無関係である。）。

　実は粒子性と波動性の二面性は光に限ったことではなく, 電子や原子や陽子や中性子などの微小な粒子にも存在する。そのような存在（粒子性と波動性の二面性を持つ物理的実体）を「量子」と呼ぶ。そして, 量子の挙動を体系化した理論が「量子力学」である。光が物質に吸収されたり散乱されたり, あるいは物質から光が放射される現象は, 根源的には量子力学で理解・説明される。たとえば葉の光合成色素が光を吸収したり蛍光（注: 後で説明する）を発する現象を理解するには量子力学が必要である。
 
　量子力学に馴染みのある生態学者は多くはないだろう。そこでまず, 量子力学について説明する。以下, 我々の想像や納得が難しい話が続くが, その正しさを裏付けるのは「そう考えれば様々なことが辻褄が合う」という実験的事実であり, 我々は深く考えずに受け入れるべきである（注: 実際, 物理学の専門家ですら, 量子力学の概念を直感的な想像で納得することを諦めている。）。
 
　量子力学では, 量子の状態を1つの数学的な関数（注: あるいはベクトル。ここでいうベクトルとは速度や力のような「向きと大きさを持つ量」ではなく, 抽象的な概念である）で表す。その関数が, 時刻 $t$について周期的な性質を持つとき, その量子のエネルギーが確定すると考え, その状態をエネルギー固有状態と呼ぶ。そしてそのエネルギーEは, 
 
$E = h\nu$      (1)
 
と表されると考える。 $\nu$は振動数, すなわち周期の逆数である（注: $\nu$はギリシア文字のニューである。 $v$と混同しないように注意せよ）。 $h$はプランク定数と呼ばれる, 物理定数で, $6.63\times 10^{-34}\text {J s}$である（注: プランク定数は物理学において最も基本的で重要な定数のひとつである。その値は国際単位系の基盤として$6.62607015\times 10^{-34}\text {J s}$と定義されている。）。

　この式(1)は, 光子でも電子でも同様に成り立つ。特に光子の場合はこの振動数νは波としての振動数（つまり波が単位時間あたりに何回の振動を繰り返すか）と同じである。

## wavelength and energy

　ここで波に関する基本的な事柄を確認しよう。波とは一定のパターンが空間を伝わる現象である。特にそのパターンがsinやcosのような三角関数で表されるものは正弦波と呼ばれ, 最も基本的な波とされる。そして正弦波以外の波は, 周期が異なる多様な正弦波を重ね合わせることで表現できる（注: これはフーリエ解析と呼ばれる数学的な考え方だが, 光を含む多くの現象に理解・記述で有用・重要である）。正弦波について, 速さを $u$, 波長を $\lambda$, 周期を $T$とすると（注: $T$は後で温度の記号としても使う。それぞれの文脈で記号が何を意味するかを正しく識別することは重要である）次式が成り立つ:
 
$u = \lambda/T$        (2)
 
これは, ある地点を基本波形（正弦波の山と谷を1つずつ含む波形）の1つが通過するのにかかる時間が $T$であり, その間, 基本波形の先頭は距離 $\lambda$だけ進むので, その速さ（距離/時間）は $\lambda/T$と考えれば容易に理解できよう。

　そして, 周期 $T$は振動数 $\nu$, 角振動数 $\omega$と以下のような関係にある:
 
$\nu = 1/T$         (3)
 
$\omega = 2\pi/T = 2\pi\nu$   (4)
 
これらの3つの量 ($T$, $\nu$, $\omega$) は上記の式で互いに関係づけられているので, 本質的には1つだけを考えればよい。しかし分野や話題によって, この中のどれを好んで使うかは異なるので, 全てに慣れておくことが望ましい。

　また, 波長 $\lambda$は, 「波数」と呼ばれる量 $k$と以下のような関係にある:
 
$k=2\pi/\lambda$      (5)
 
これらの2つの量（ $\lambda$, $k$）も式(5)で互いに関係づけられているので, 本質的には1つだけを考えればよいような気がするが, 実はそうではない。波数は本質的にはベクトルであり, ${\bf k}=(k_x, k_y, k_z)$という3つの成分を持ち（注: 物理学ではベクトルは ${\bf k}$のようにボールド体で表記する慣習である。 $\vec{k}$というふうに, 上付き矢印で表記することもある。）, その方向は波の進行方向を指している。式(5)でいう $k$はベクトル ${\bf k}$の大きさなのである（ただしこのあたりの事情は今は重要ではないので理解にこだわる必要はない）。

　ここで記号の慣習について説明しておく。エネルギーを $E$, 振動数を $\nu$, 周期を $T$などと書いてきたが, それらは慣習であり, そうせねばならないという規則は無い（注: $E$がエネルギーの頭文字であるように, 多くの慣習的記号はその量の呼び名を想起させるものが使われる。しかし角振動数 $\omega$など, その限りではないものもある。また, プランク定数 $h$のような基本定数は慣習よりも強い強制力で記号が定まっている。）。実際, 振動数を $f$と書く慣習もある ( $\nu$は高い振動数, $f$は低い振動数の現象で使われる傾向にある)。だからといって, エネルギーを $T$と書いたり, 振動数を $E$と書いたりするのは混乱の元であり, 極力避けるべきだ。事情が許す限り慣習に沿った記号を使うことで, 科学のコミュニティの中で相互理解が楽になる。

　さて, 物理学者は $T$, $\nu$, $\omega$のうち $\omega$を好んで使う。そうすると数式の扱いが楽になるからである。そこで式(4)を使って式(1)を書き換えると, 
 
$E = h\omega/(2\pi)$
 
となる。ここで $h/(2\pi)$を $\hbar$（注: エイチバーと発音する。ディラック定数と呼ばれる。）と書いて, 

$E = \hbar\omega$    (6)
 
と書くことが多い。この式は原子や分子のエネルギー準位（後述する）を考えたり, 原子や分子による光子の吸収・放出を考えるときによく出てくる。

　また, 式(4)を使って式(2)を書き換えると, 
 
$u = \omega/k$     (7)
  
となる。式(2)や式(7)は, 波の屈折の議論で登場する（注: この式(7)は位相速度と呼ばれるものであり, 類似するが別の概念として群速度というものがある。）。

　さて, 式(2), (3)より, $\nu=1/T=u/\lambda$であり, それを(1)に代入すると, $E=hu/\lambda$となる。ここで話を光に限定すれば, その速さ $u$は真空中では一定値 $3.00\times10^8$ m/sであり（注: 正確には $c=299792458 \text{m/s}$。これはプランク定数と同様に国際単位系を定義づける数値。）であり, それを $c$と表すことが決まっている。つまり, 光については, 
 
$E=hc/\lambda$    (8)
 
が成り立つ。これは光子のエネルギーを表す式として頻出する（注: 式(1), 式(6)は光子だけでなくあらゆる量子について成り立つ式だが, 式(8)は光子に限定して成り立つことに注意せよ。）。

演習 1-1: (1) $\lambda = 450\text{ nm}$、(2) $\lambda = 680\text{ nm}$ の場合における光子のエネルギーを導出せよ（注: （nm は 'ナノメートル' の略で、1 nm は $10^{-9}$ m すなわち 0.001 μm に相当する）。

答え: (1) $E=6.63\times10^{-34}\text{J s}\times 3.00\times 10^{8} \text{m s}^{-1}/(450\times 10^{-9} \text{m})=4.4\times 10^{-19}\text{ J}$。 (2) $E=2.9\times 10^{-19}\text{ J}$。

この演習では、2つの光、すなわち青色光 (1) と赤色光 (2) の光子のエネルギーを計算した。どちらも地上植物の光合成の主な色素であるクロロフィル $a$による吸収のピーク付近にあたる光である。この結果から、青色光の光子のエネルギーが赤色光のエネルギーよりも大きいことがわかる。これは、エネルギーと波長の間には式(8)のように反比例の関係があることから理解できる。つまり波長が長ければ長いほど、エネルギーは小さくなるのだ。この事実に関連する例として、長い間壁に飾られていた古いポスター写真を見ると、赤い色が青い塗料よりも早く消えるため、青っぽく淡い写真が残ることが挙げられる。これは、赤色の顔料が短い波長（青色や紫外線など）の光を選択的に吸収すること、そしてそれらの光が顔料の構造を破壊するのに十分な高いエネルギーを持っているためである。ということは、短波長の破壊的な光子を吸収することによって、赤や茶色の顔料はそれらをブロックするのである。これが、一部の植物の葉が赤い理由でもある。赤色の顔料は、葉の内部に入り組織を破壊しようとする日光や青空の光に含まれる有害な光子をブロックする役割を果たしているのだ。


## エネルギー順位と遷移

次に, 光子の生成と消滅について学ぼう。太陽, レーザー, 蛍光灯など, 自ら輝いて光子を生成する物体は様々である。それらに共通する基本的な物理過程は, 量子のエネルギー順位の遷移という量子力学的な現象である。

先程, 量子のエネルギー固有状態について述べた。ひとつの量子について, 様々なエネルギー固有状態を考えることができる。例えば原子の中の電子について, 電子が原子核に近い空間に分布するようなエネルギー固有状態がありえるし, 原子核から遠い空間に分布するようなエネルギー固有状態もありえる。そして電子のエネルギーは前者で低く後者で高い（注: これは電子が負の電荷を持ち, 原子核が正の電荷を持つからである。正負の電荷は近接するほどエネルギーは低くなる）。

興味深いことに, 原子の中の電子, つまり原子核に引きつけられている電子のエネルギーは連続的な値を取ることができない, つまり離散的である。これは電子のエネルギー固有状態が, ある数学的な制約条件を満たす必要から生じる。この原子内の電子の例だけでなく, 量子のエネルギーが離散的になることは他にも多い（注: たとえば多原子分子の振動や回転のエネルギーも離散的になる。）。

ある量子に関して, 固有状態のエネルギーが離散化的であるとき, そのエネルギーを高低の順にならべたものをエネルギー準位という（注: それらに対応するエネルギー固有状態を指すこともある）。エネルギー準位の最も低い状態を基底状態と呼ぶ。

量子はエネルギーの異なる固有状態（エネルギー準位）の間で移り変わることがある。これを遷移という。特に, 基底状態からそれより高エネルギーの固有状態に遷移することを励起と呼び, その状態を励起状態と呼ぶ。そして, 高エネルギー状態と低エネルギー状態の間で量子が遷移するとき, その差に相当するエネルギーが何らかの形で放出または吸収される（注: これはエネルギー保存則から必然的である）。エネルギーを光子として放出するとき（そうでないときもある。熱としてエネルギーが放出される場合もある。）, 物質は光を放ち, エネルギーを光子として吸収するとき, 物質は光を吸収する。そのような場合, 状態間のエネルギーの差は光子のエネルギーに等しいので:

$h\nu = E_\text{high} - E_\text{low}$
 
が成り立つ（ $\nu$は放出又は吸収される光子の振動数であり, $E_\text{high}$と $E_\text{low}$はそれぞれ高エネルギーと低エネルギーの量子状態のエネルギーである）。

例: ナトリウム原子の最外殻電子は, $3p$軌道と呼ばれるエネルギー固有状態から $3s$軌道と呼ばれるエネルギー固有状態へ遷移することで, 波長が約590 nmの光子を出す。これは黄色い光であり, D線と呼ばれる（注: 細かく見ると, D線の光は微妙に異なる2つの波長の光からなる。なお, D線を用いたナトリウムランプは長寿命で効率が良いため, 長らくトンネル内の照明に使われた。）。このD線の光子のエネルギーを式(8)で計算すると $3.37×10^{-19}$ Jである。上の式によれば, これが両状態のエネルギーの差 $E_\text{high} - E_\text{low}$である。

この例で見たナトリウム原子のように, 物質（原子）はそれぞれに固有のエネルギー準位を持つ。そのため, 特定の波長の光子を強く吸収または放出することが多い（注: これを利用すると, 物体が吸収・放出する光の波長を計測することで, 物体を構成する物質やその状態を推定できる。天文学で彼方の天体の校正元素を知ることができるのはこれを利用している。）。

　たとえば太陽光は後述する熱放射という過程で光を放つが, 地上に届く太陽光は特定の波長の光が顕著に弱くなっている。それをフラウンホーファー線と呼ぶ。そのひとつは590 nmの光である。太陽光中の590 nmの光は弱いのだ。これは上の例で述べたナトリウム原子のD線である。太陽の中にナトリウム原子が存在し, その最外殻電子が遷移することで, D線を吸収するのである（注: 歴史的には話は逆であり, D線はまずフラウンホーファー線として発見された）。フラウンホーファー線の別の例として, A線と呼ばれる波長759 nmの光がある。これは地球大気の酸素分子(O2)による吸収に起因する（注: 従って地球大気の外, すなわち宇宙空間で太陽光を観測するとこのA線は見られない。）。そのためO2A線とかO2Aバンドとも呼ばれる。この波長帯は植生がクロロフィル蛍光（後述）によって放出する光の波長帯と重なっているため, クロロフィル蛍光の観測に利用される。

さて, この遷移は確率的に起きる。つまり, エネルギー準位の高い状態にある量子が, 一定時間の間に低い準位に遷移するのは気まぐれである。その確率は量子力学によって予測できるが, その詳細はここでは述べない（注: フェルミの黄金律）。


## 熱放射

さて, 生態系で最も重要な光源は言うまでもなく太陽光である。太陽光は今から説明する熱放射という物理現象で生成される。そして地球上の地物・生物が発する赤外線も熱放射で生成される。熱放射は地球の熱環境を司る最も重要な物理過程である。熱放射について知れば, これらの重要なトピックの理解・研究に役立つ。

熱放射は端的に言えば, あらゆる物体はその温度に応じた強度と波長分布で光を出す, という現象である。これは一見奇妙なことだ。熱く輝く太陽が光を出すのはもっともに思えるが, 冷たい石や氷ですら光を出すのか? 実際, そうなのだ。冷たい石や氷は太陽ほど明るくはないし, 人の肉眼で検知できるほど短い波長でもないが, それなりに光を出す。我々の直感に反するが, これは事実である。実際, その光を検出することで, 人工衛星は極地の氷床の温度を遠隔計測している。

熱放射は, 物体を構成する粒子（電子や原子など）の熱的エネルギーが関係する。すなわち, 物体がある温度にあるとき, その温度に応じた激しさで粒子は運動している。逆に言えば, 温度というのは粒子たちのエネルギーの平均値の指標である（注: エネルギー等し分配則。粒子の1自由度あたりの平均エネルギーは $k_\text{B}T/2$。ここでTは絶対温度, $k_\text{B}$はボルツマン定数=1.38×10^{-23} J/K）。平均値と言ったのは, 実際はそれよりも高いエネルギーの粒子もあれば, 低いエネルギーの粒子もあるからである（注: 物体が熱平衡状態にあるとき, その構成粒子の熱的エネルギーの確率分布は, ボルツマン分布という理論で表現される）。従って, 電子などの量子の一部は, 基底状態から励起され, エネルギー準位の上位に存在する。それらが基底状態に遷移することで光が出る。基底状態に戻ってエネルギーが下がった量子は, 周囲の粒子の熱運動の影響を受けて（他の量子が出した光子を吸収することもある）エネルギーを回復し, 励起し, また光子を出す, ということを繰り返すのだ。こうして光子が物体から次々に放出される現象が熱放射である。

熱放射にはプランクの法則という, 次式で表される理論が存在する。

$B(\lambda, T) = \frac{2 h c^2}{\lambda^5} \frac{1}{\text{exp}\Bigl(\frac{h c}{\lambda k_\text{B} T}\Bigr) - 1}$

where:
$B(\lambda, T)$ is the spectral radiance (power per unit area per unit wavelength per unit solid angle) at wavelength $\lambda$ and temperature $T$; $h$ is Planck's constant ($6.626 \times 10^{-34}$ J$\cdot$s); $c$ is the speed of light in a vacuum ($3.00 \times 10^8$ m/s); $\lambda$ is the wavelength of the photon; $k_\text{B}$ is the Boltzmann constant ($1.381 \times 10^{-23}$ J/K); $T$ is the absolute temperature; $e$ is the base of the natural logarithm.

この式は, 熱放射のエネルギーを波長別に表したものである。このように, 何かを波長別に表したもの（関数やグラフ）をスペクトルという。

（グラフ）

ただしこれは状況を理想化・単純化したモデルであるため, 実際の物体の熱放射はこの法則どおりにはいかない。より具体的に言えば, プランクの法則は, 全ての波長で可能な限り最も強い光を出すような理想的な状況を想定している。この想定を満たす物体を黒体（blackbody）もしくは完全黒体と呼び, その熱放射を黒体放射と呼ぶ。プランクの法則が述べるのは, 黒体放射で出てくる光の強度を波長の関数として表したものである。実際の物体の熱放射は黒体放射より小さい。物体の熱放射の強度を黒体放射の強度で割った値を射出率（emissivity）という。射出率は0から1の実数値であり, 物体によって変わるし, 波長によっても変わる。後に述べる「偏光」によっても変わる。

さて, 現実の物体の熱放射と多少のズレがあるとはいえ, プランクの法則は熱放射の良いモデルであり, 我々が熱放射を論じる時の基礎である。プランクの法則をグラフにすると図___のようになる。このグラフを0から∞まで積分すると, 全波長で合計した熱放射のエネルギーが得られ, それは絶対温度の4乗に比例することがわかっている。これをステファン・ボルツマンの法則という。すなわち, 

$F(T) = \epsilon \sigma T^4$      ()

である。ここで$F$は単位表面積あたり, 単位時間あたりに射出される全エネルギー（注: 後述するエネルギーフラックス）, εは射出率, σはステファン・ボルツマン定数と呼ばれる定数で, $5.67\times 10^{-8}$ W m$^{-2}$ K$^{-4}$である（注: この定数は, 5, 6, 7, 8が順に並んでいるので覚えやすい。実際, 覚えておくと環境の熱収支を考察するときに便利である。）。

　また, このグラフのピークの位置を求めることもできる。それは関数を微分し, 導関数が0になる波長を求めればよい。その結果, ピーク波長は温度($T$)に反比例することがわかる。これをウィーンの変位則という。すなわち, 
 
$\lambda_\text{max} = 0.003\text{ m K} / T$

である（注: 右辺の分母のTがイタリック体で, 分子のm Kがローマン体であることに注意せよ。イタリック体は変数や定数の記号であり, ローマン体は単位の記号を表す。つまり $T$は温度という量を表す変数で, mとKはそれぞれメートル, ケルビンという単位である。mとKの間にスペースがあることにも注意せよ。これはミリケルビン(mK)ではなく, メートルとケルビンの積であることを意味する。教科書によってはこの分子のm Kを書かないことがあるが, それは間違いである。$T$が温度であり, $\lambda_\text{max}$が長さであるため, 次元を合わせるには, 長さと温度の量が分子になくては辻褄が合わない。ここでは単位長さmと単位温度Kがその役割を果たしている。）。

例題: 太陽の表面温度は約5800 Kである。太陽を黒体と近似し, 太陽からの熱放射の強度とピーク波長を見積もれ。

解答: $\epsilon=1$とおいて, ステファン・ボルツマンの法則とウィーンの変位則を使う:

$B = 5.67\times 10^{-8}\text{ W m}^{-2}\text{ K}^{-4}\times(5800\text{ K})^4 = 6.4\times 10^{7}\text{ W m}^{-2}$

$\lambda_\text{max} = 0.003\text{ m K} / (5800\text{ K}) = 5.2\times10^{-7}\text{ m} = 520\text{ nm}$

上の例題で, 太陽の熱放射の強度が大きな値になったことに驚いただろう。太陽はこれほど強力な光源である。しかし, その光は全方向に広がるので, 地球に到達する頃にはずいぶん薄まっている。その効果は距離の2乗に反比例する。太陽ー地球間距離(150,000,000 km)は太陽半径(700,000 km)の210倍なので, 地球に届く太陽放射は上記の1/210 $^2$倍, つまり約 $1400\text{ W m}^{-2}$になる。これが地球システムおよびそのサブシステムである生態系を駆動するエネルギーである。そして太陽光の強度がピークになる波長は約500 nm。これは人の目が感知できる可視光に相当する。生物の光受容体や色素が反応する波長は, このようにして太陽からの熱放射に対応しているのである。

グラフ（太陽放射）

## 光のカテゴリー

前節で太陽放射のエネルギースペクトルを学んだ。そのグラフは500 nm付近にピークを持つが, その左右にも広がりを持つ山型だった。特に380 nmから750 nmのレンジに着目すると, 山の面積の半分弱がそこに入りそうだ。実はこのレンジに波長を持つ光は人間の目の光受容体を励起できるため、人間の目で感知できる。そこでこのレンジの光を「可視光」と呼ぶ。日常生活で、'光' という言葉を使うとき、通常は目で見える光、つまりこの可視光を意味することが多い。しかし, このグラフから明らかなように, 太陽光には目に見えない光も含まれる。可視光の範囲の外にある光は目に見えない光なのだ。可視光より少し波長が短い光は紫外線 (UV) であり、少し波長が長い光は近赤外線 (NIR) である。いずれも目には見えない光だ。同様に、光は波長によって分類され、短い方から長い方に向かって、ガンマ線、X線、紫外線 (UV)、可視光、近赤外線 (NIR)、短波赤外線 (SWIR)、熱赤外線 (TIR)、マイクロ波などに分かれる。テレビやラジオの放送に使用される '電波' も光の一種で、その波長はさらに長い。これらのカテゴリの間には明確な境界があるわけではない。実際、光の波長は任意に連続的に正の値を取ることができる。それにもかかわらず、波長のスケールが光の特性や振る舞いに非常に強く依存しているため、これらのグループに分類するのは便利である。例えば、光と植物の葉の相互作用は、可視光とマイクロ波で非常に異なる。可視光は葉によって大部分が吸収または反射されるが、マイクロ波は葉との相互作用が小さい。

## 可視光の色

ここで可視光について, もう少し詳しく見ておこう。

人間の視覚における色覚は、本質的にスペクトルと関連している。つまり、光のスペクトルがわかれば、その色を予測できる。どうやって？人間の目には「錐体」と呼ばれる3種類の色感知細胞があり、脳はこれらの錐体からの信号をもとに色を認識する。具体的には、「S錐体」「M錐体」「L錐体」の3種類であり、それぞれ青、緑、赤に対応している。各錐体の反応の強さは光のスペクトルによって異なる。例えば、スペクトル内で支配的な波長が 400 nm であれば、S錐体の反応が強く、他の錐体の反応は弱くなり、脳は青色として認識する。もし光のスペクトルが複数のピークを持っていたり、広範囲の波長から成り立っていたりすると、S錐体、M錐体、L錐体の全てが異なる反応を示し、青、緑、赤の混合色となり、非常に多様な色が生じる。

先に述べたように、人間の視覚は波長が約 380 nm 未満または約 750 nm以上の光をほとんど感知できない。これは、人間の目の錐体がそのような光に反応しないためである。つまり, 人間とは異なる種類の錐体を持つ動物は、人間には見えない光を見ることができるのだ。実際、鳥や一部の昆虫は人間の可視光より波長の短い紫外線（UV）に反応する錐体を持っている。そのため、これらの動物の視覚を研究する際には、私たちにとって見えない光を考慮する必要がある。

光の色を決定するのはスペクトルだと説明したが、興味深いことに、その逆は成り立たない。つまり、色が光のスペクトルを決定するわけではない。言い換えれば、異なるスペクトルを持つ光が同じ色を持つことがあり得る。例を使って理解してみよう。例えば、550 nm（M錐体を刺激）と 680 nm（L錐体を刺激）の二重ピークを持つ光があるとしよう。この場合、色は緑（M錐体の反応）と赤（L錐体の反応）の混合であり、黄色になる。一方で、610 nm 付近に単一のピークを持つ光があると仮定しよう。この場合、ある程度M錐体とL錐体がその波長に反応し、結果として先ほどと同じ黄色が生じる。

それにもかかわらず、便利さのために色の文脈でスペクトルについて議論することがある。特に、可視光の単色光は波長だけでなく、色でも短い波長から長い波長の順に次のように記述される：紫、青紫、青、緑、黄、橙、赤。この順番が虹の色の順番と同じであることは偶然ではない。実際、虹は単色光の同心円状のアークの集合体であり、内側のアークは短波長（紫や青）で、外側のアークは長波長（赤）である。この色の順番を覚えておくと、光の現象を波長の観点から理解し、想像するのに役立つ。

## 物体の色

前のセクションでは光の色について議論した。ここでは物体の色について議論する。これらは似ているが異なる概念であり、区別すべきである。例えば、植物の緑色の葉を想像してみよう。植物の葉は、ある光源からの光で照らされて, その一部を反射または散乱し, それが私たちの目に入り, その色が知覚される。したがって、植物の葉の色はそれを照らしている光と、その光が植物の葉によってどのように散乱されるかに依存する。色は光の特徴であるため、葉を照らす光源を考慮しない限り、葉の色について議論することはできない。葉の色は、実際には葉によって散乱される光の色に関連して議論される。そして、奇妙なことが起こることがある。もし光が元々赤色で、M錐体（緑の反応を引き起こす）を刺激する光がほとんど含まれていない場合、反射光も赤色になる可能性がある。

植物の葉は、赤や青よりも緑色の光を強く「散乱」する。

## スペクトル

前説で, 太陽光の波長別の強度を論じた。このように, 光や波を論じるときは波長別に論じることが多い。それを「スペクトル」という。スペクトルについて理解を深めよう。

まずは、光を波として考えることにしよう。物理の教科書には多くの場合「正弦波」が出てくる。これは三角関数である cos⁡(x) や sin(x) で記述される。この関数は「上下」のパターンを繰り返すため、「周期的」である。

(正弦波の図)

しかし、正弦波は波の一つの形に過ぎない。波は必ずしも正弦波である必要はない。空間を移動するパターンであれば、ほぼどんな形でも波でありうる。その「パターン」は、パルスやベル型、あるいは正弦波のような形など、ほとんどどんな形でもよい。例えば、懐中電灯の光は空間を移動するパルスパターンのようなものである。

それでも、正弦波の概念は光波を記述し理解するために非常に有用である。なぜか？正弦波は非常に単純で、扱いやすく理解しやすいからだ。さらに、前述の「重ね合わせの原理」を使うことで、あらゆる光波のパターンを正弦波の重ね合わせで記述することができる。驚くべきことに、数学者たちはほとんどすべての波の形状がこの方法で記述できることを証明している。この考え方と理論は「フーリエ解析」と呼ばれている。それは、様々な波長を持つ正弦波の重ね合わせによって任意の波を作成（または波を分解）することである。

ここから、正弦波の光を「単色光」と呼ぶことにしよう。これは「単一の波長を持つ光」を意味する。「単色」という言葉は、「単一」を意味する「モノ」と「色」を意味する「クローム」に由来する。なぜ「色」なのかは、すぐに理解できるだろう。

フーリエ解析を用いることで、光を様々な波長を持つ単色光の重ね合わせとして考えることができる。したがって、単色光を理解することに焦点を当てればよい。より複雑なケースを考える必要がある場合は、様々な波長を持つ単色光 ${\bf E}_1, {\bf E}_2, {\bf E}_3,…, {\bf E}_n$ の重ね合わせを想像すればよい。次に重要なのは、それらの単色光の寄与を示す係数 $a_1, a_2, ... a_n$ である。言い換えれば、$a_1, a_2, ... a_n$ のそれぞれは各単色光の振幅を表している。多くの場合、それらの二乗値に関心がある。なぜなら、光のエネルギーは振幅の二乗に比例するからである。波長（x軸）と単色光の振幅の二乗をグラフにしたものを「スペクトル」と呼ぶ。

すでに示した太陽光のグラフは, 要するに太陽光のスペクトルを表したものである。すなわち太陽光が様々な波長の正弦波から構成されていることを意味している。


## Lambert Beerの法則

光が媒質（森林樹冠のような構造物や, エアロゾルが充満した大気など, 光を遮る少物体や粒子が空間内に分布した状況）を通貨するとき, 距離が進むにつれて光は減衰していく。その様子の最も単純なモデルを説明する。それはLambert Beerの法則（注: Beer Lambert's law, Bouguer-Lambert-Beer’s lawなどとも呼ばれる）というものである。すなわち, 光の進んだ距離を $x$とし, そこでの光強度を $I(x)$とすると, 何らかの定数 $\beta$を使って, 

$I(x) = I(0) \exp(-\beta x)$　　　(LB01)

と表せる（注: $\exp x$は $e^x$ を意味する。 $e=2.718...$は自然対数の底である）。ここで $\beta$は消散係数と呼ばれる定数であり, 媒質や構造, 入射角などによって決まる。 

これを単純な植物群落内の光の透過について導出してみよう。

今, 単純化のために, 等しい大きさ $a$の水平な葉が樹冠内にランダムに分布しており, 水平方向には粗密は無いとする（鉛直方向には粗密はあっても構わない）葉以外の構造物（枝, 幹など）は無視できるとする。単位体積中に葉は $n$枚あるとする。この林冠に, 光が平行光線となって真上から注ぐとする。 $x$は群落表面からの距離とする。森林の面積を $A$とすると, この光はその中のどこかに落ちようとしている。

さて, 森林の表面から $x$までの深さと, そこから $\Delta x$進んだ深さで挟まれる薄い層状の空間を考えると, その空間内にある葉の面積は $anA\Delta x$である（注: $A\Delta x$がその層の体積, それに $n$をかけるとその層内の葉の枚数になることから理解できよう。）。つまり, その層が光を遮る確率は, $anA\Delta x/A=an\Delta x$となる。つまり, 光がこの層を通過するときに, $an\Delta x$という割合で強さを失う。すなわち, 

$I(x+\Delta x)-I(x)=-an I(x) \Delta x$　　　(LB02)

となる。両辺を $\Delta x$で割り, $\Delta x$を十分に0に近づけると（注: $\lim_{\Delta x \rightarrow 0} \frac{I(x+\Delta x)-I(x)}{\Delta x} = \frac{dI}{dx}$）, 

$\beta = an$　　(LB03)

とすると, 

$\frac{dI}{dx} = -beta I(x)$　　　(LB04)

となる。もし $\beta$が $x$によらない定数なら（つまり鉛直方向に葉の粗密が無いなら）, この微分方程式は簡単に解けて, 

$I(x) = I(0) \exp (-\beta x)$　　(LB05)

となる（注: ここでは微分方程式を解いたが, 別の方法でも(LB05)を導出できる。まず(LB02)から, 
$I(x+\Delta x) = (1 - an \Delta x) I(x)$である。群落を表面($x=0$)から深さ　$x$までを, 厚さ $\Delta x$の　$N$枚の水平層に分割すれば($x=N\Delta x$), 各層を通過すたびに光はこの式に従って乗算的に弱まっていく。つまり, 

$I(x) = I(N \Delta x) = I((N-1) \Delta x + \Delta x) =  (1 - an \Delta x) I((N-1)\Delta x)$

$=  (1 - an \Delta x)^2 I((N-2)\Delta x) = ... = (1 - an \Delta x)^N I(0) = (1 - \frac{anx}{N})^N I(0)$

となる。ここで　$N$が十分に大きい（層が十分に薄い）とみなせば, 数学の公式

$\lim_{N\rightarrow\infty} \Bigl(1+\frac{x}{N}\Bigr)^N = e^x$

を使うと, $I(x) = I(0)\exp(-anx)=I(0)\exp(-\beta x)$。）。

## 2-stream, 4-stream, モンテカルロモデル

このLambert-Beer理論 (L-B理論)は適用範囲が広いのだが, 限界もある。導出過程に遡れば以下のような前提があったことがわかるだろう:
- (1) 光は平行光線である。つまり一方向からのみやってくる。
- (2) 葉に当たった光は完全に遮られる, つまり, 光は葉に吸収されるかそのまま透過するだけであり, 散乱（反射）されない。
- (3) 葉は水平方向に一様にランダムに分布している。つまり水平方向の粗密は無い。これによってLB02やLB04が得られた。
- (4) 葉は深さ方向にも一様にランダムに分布している。つまり深さ方向に粗密が無い。これによってLB05が得られた。

この(4)だけが成り立たない場合は, (LB05)のかわりに以下のような解が成り立つ（注: この式で $\beta$が $x$によらない定数ならば(LB05)に一致する）:

$I(x) = I(0) \exp (-\int_0^x \beta dx)$　　(LB06)

(2)(4)が成り立たない場合, 特に葉が反射して逆方向（鉛直上向き）の光が生じる場合は, その光がまた上の葉で反射されて再び下向きの光に合流する, というようなことが発生する。それを扱う理論をKubelka-Munk理論 (K-M理論)という。K-M理論は下向きの上向きという2つの方向を扱うのでtwo stream modelという。その観点では, L-B理論はone stream modelと言えよう。

(1)(2)(4)が成り立たない場合, 特に, 特定方向からやってくる太陽光球からの直射光と, 天空全体から全方位に対してやってくる散乱光を分離して扱い, なおかつ観測者の方向も特定方向として扱う場合は, 4つの方向を考えることになる。これはfour stream modelと言われ, SAILモデルがその代表例である。

(1)から(4)の全てが成り立たない場合は, 媒質や構造物（植物群落等）の幾何学的なモデルを構築した上で, 全方向の光の経路を計算することが必要になり, その実装例がKobayashi et al. による3次元モンテカルロモデルFLiESである。


## フラックス

光の"強さ"を定量的に表すには, フラックスという概念を使う。一般的に言えば, フラックスは, ある面を単位面積あたり単位時間あたりに通過する量である。光の場合, その「量」は光子の数であらわすこともあるし, 光子たちが運ぶエネルギーで表すこともある。前者の場合は, 光子数をmol単位で表すと, たとえば mol/(m^2 s)という単位になるし, 後者の場合は, エネルギーをJ単位で表すと, たとえばJ/(m^2 s)つまりW/m^2という単位になる（注: Wワットはpowerつまり単位時間あたりのエネルギーの単位であり, W = J/sである。）。どちらで表すかは, 話題の性質による。

生態系や地球システムの中の温度や水環境を考える場合は, エネルギーフラックスを使うことが多い。というのも, 温度は熱エネルギーの収支で決まるからであり, 水循環, 特に蒸発散は潜熱（固体や液体の水を気体にするために必要なエネルギー）の供給に強くコントロールされるからである。光合成について考える場合は光子数フラックスを使うことが多い。上述のように光合成における光利用は量子力学的な現象であり, 光子単位で起きるからである。

上述のステファン・ボルツマンの法則で求まる $F(T)$は後者である。

## 短波放射, 長波放射, 光合成有効放射

生態系内の光エネルギーフラックスは, 便宜上, 主に2つの波長領域で取り扱うことが多い。すなわち, 波長4 $\micro\text{m}$を境に, それより短波長の光を短波放射, 長波長の光を長波放射という。それらは概ね, 太陽と地球のそれぞれからの熱放射に対応している。実際, 太陽表面温度（5700 K）の黒体放射のエネルギーフラックスにおいて, 約99.0 %は短波放射（波長4 $\micro\text{m}$以下）であり, 地球表面温度（300 K）の黒体放射のエネルギーフラックスにおいて, 約99.8 %は長波放射（波長4 $\micro\text{m}$以上）である（注: プランクの法則を数値積分すればわかる。）。

短波放射の中に前述の可視光（約 380 nm 以上約 750 nm以下）が含まれる。そしてその中に「光合成有効放射」(PAR)が含まれる。それは植物が光合成に利用できる光である。いくつかの異なる定義があるが, よく採用されるのは400 nm から 700 nm の波長を持つ光である。実際は, どようのような光がどのくらい光合成に寄与するかは, 葉緑体を構成する色素や葉緑体の構造によって決まる。それを示すのが作用曲線

## 電磁波としての光

ここまでは光を光子の集合として扱ってきた。すなわち, 粒子性と波動性という二面性（duality）のうちの前者の立場（量子論）で考えてきたのである。ところが, それではうまく取り扱えない（注: 正しく言えば, 原理的には取り扱うことができるけど実際は複雑過ぎて無理である）ような性質が光にはある。それは, 光が相互作用する物質や媒質が非常に多くの同質的な粒子で満たされている場合である。そのようなケースでは, 個々の光子と粒子のミクロな相互作用を量子論的に扱うのはあまりに迂遠なやり方になってしまう。状況を巨視的に扱うことで, シンプルでありながら十分に高精度な扱いが可能になるのだ。それが電磁波としての扱いである。

電磁波は電磁気学の理論で扱うことができる。そして電磁気学の理論は, Maxwell方程式と呼ばれる4つの偏微分方程式を基本法則とする。光（電磁波）を含む全ての電磁気的現象はこの方程式に遡る。といっても, radiation ecologyを志す生態学者は, その詳細に立ち入る必要は少ないだろう。大事なことは, 光の物理学のほとんどの理論は量子論とMaxwell方程式から得られるという体系性を知っておくことである。

ではMaxwell方程式を以下に示す。これはどんな状況でも成り立つ, 普遍的な形式である：

$\nabla \cdot \mathbf{E} = \frac{\rho}{\epsilon_0}$

$\nabla \cdot \mathbf{B} = 0$

$\nabla \times \mathbf{E} = -\frac{\partial \mathbf{B}}{\partial t}$

$\nabla \times \mathbf{B} = \mu_0 \mathbf{J} + \mu_0 \epsilon_0 \frac{\partial \mathbf{E}}{\partial t}$

ここで $\nabla$は $(\partial/\partial x, \partial/\partial y, \partial/\partial z)$として形式的に定義される微分演算子であり, $\nabla \cdot$はgradient, $\nabla \times$はrotationと呼ばれる微分演算を表す（注: 詳しくはベクトル解析または電磁気学の参考書を参照されたし）。 $\epsilon_0$と $\mu_0$はそれぞれ真空の誘電率, 真空の透磁率と呼ばれる定数である（時刻や位置に依存しない）。

この方程式の主役は $\mathbf{E}$, $\mathbf{B}$であり, 前者は電場, 後者は磁束密度というベクトル場（空間の各点にベクトルが付与されたような物理量）である。これらがセットになって電磁気学的現象を起こす。 ${\rho}$は電荷密度, $\mathbf{J}$は電流密度（電荷フラックス）である。以上の4つの量は, 時刻($t$)と位置($x, y, x$)の関数である。おおまかにいえば, ${\rho}$と $\mathbf{J}$によって $\mathbf{E}$と $\mathbf{B}$が決まると考えてよい。 ${\rho}$と $\mathbf{J}$は $\mathbf{E}$と $\mathbf{B}$によって力を受けて運動し, その結果が $\mathbf{E}$と $\mathbf{B}$に反映されるのだが, その運動過程は別の物理法則（ニュートンの運動方程式など）によって決まる。そういう意味では, Maxwell方程式だけで電磁気学的現象の全てが説明されるというのは言いすぎである。

この4つの方程式を, 恒等的に $\rho=0$, $\mathbf{J}=\mathbf{0}$という条件, つまり真空という条件で変形すると, $\mathbf{E}$と $\mathbf{B}$に関する, 波を表す偏微分方程式（波動方程式）が導出される。それが電磁波を表す。そして, 以下のことも数学的に示される:

性質1: 電場と磁束密度と伝播方向が互いに直交する。

性質2: 電場から磁束密度に右ねじを回すとその進行方向が伝播方向に一致する。

性質3: 波の速さ（電磁波つまり光の速さ）は $1/\sqrt{\epsilon_0 \mu_0}$である（注: それは実際に光速 $c=299792458\text{ m/s}$に一致する。）。

ところが光が水やガラスなどの媒質・物質を伝播するときは, それらの中の無数の電子や原子核などがこの式の中の $\rho$や $\mathbf{J}$に関与してくるので, この式を直接扱うことは大変むずかしい。そこで, それらの媒質を構成する物質たちが作る電荷や電流を, ある仮定のもとに巨視的にモデル化することで, 媒質中の巨視的な電磁気現象を扱えるように工夫されたのが, 媒質中のMaxwell方程式と呼ばれるものである。それは上の式の中の第一方程式と第四方程式をそれぞれ以下のように書き換えたものである（第二, 第三方程式はそのまま生きる）:

$\nabla \cdot \mathbf{D} = \rho$

$\nabla \times \mathbf{H} = \mathbf{J} + \frac{\partial \mathbf{D}}{\partial t}$

ここで $\rho$, $\mathbf{J}$は媒質内の電荷が寄与しない電荷密度と電荷フラックスである（真空中のMaxwell方程式における $\rho$, $\mathbf{J}$とは意味が違うことに注意）。 $\mathbf{D}$は電束密度, $\mathbf{H}$は磁場と呼ばれる物理量である。それぞれ $\mathbf{E}$と $\mathbf{B}$に関係するベクトル場だが, 必ずしもその関係は単純ではない。しかし, 実用上, 多くの媒質（物質）では

$\mathbf{D} = \epsilon\mathbf{E}$

$\mathbf{B} = \mu\mathbf{H}$

と表すことができる。ここで $\epsilon$, $\mu$は媒質の誘電率と透磁率と呼ばれるスカラー量（注: 一般には行列（テンソル）だが, 等方性を仮定できるならスカラー量になる）である。これらは媒質の物性や温度などに依存する。つまりもはや定数として扱うことはできない。さらに, これらは電磁場が振動するときはその振動数（角速度）にも依存しうる。 ともあれ, この仮定のもと, さらに $\rho$, $\mathbf{J}$をそれぞれ零とおけば（媒質中の電荷の変位や偏りで発生する巨視的な電荷や電荷フラックスの存在は許容する）, $\mathbf{E}$, $\mathbf{B}$に関する波動方程式が得られ, 上記の真空中の電磁波と同様の性質1, 2が証明される。ただし性質3は, 

性質3': 波の速さ（電磁波つまり光の速さ）は $1/\sqrt{|\epsilon \mu|}$である。

となる。このことから, 媒質中の光速が真空の光速とは違った値を持つことがわかる。実際は, 媒質中の光速は真空中の光速を越えることは無い。

## 誘電率と屈折率

ここで奇妙なことが起きる。 $\epsilon$, $\mu$は複素数, つまり虚数部を持つ量になり得るのだ。物理学のように現実の現象を扱う学問で「虚数」が現れることは多くの学生を戸惑わす。しかしそこまで深く考えることはなく, これは数式の便宜的な表現の結果である。すなわち, 正弦波的に振動する電場や磁束密度が入ってくれば, 媒質中の電荷も正弦的な力を受け, 正弦的に運動する。つまり $\epsilon$, $\mu$が正弦的に変わるのである。その際, $\mathbf{E}$, $\mathbf{B}$の振動の周波数（角速度）と, $\epsilon$, $\mu$の振動の周波数（角速度）は同じと考えられるが（注: 非線形光学材料と呼ばれる特殊な物質ではその限りではない）, 振動のピークのタイミング（位相）は同じとは限らない。そのズレを, 虚数を含めた複素数（複素数平面における偏角）で表すのである。上の性質3で分母の $\epsilon \mu$に絶対値をつけたのは, そのためである（光速は虚数部を持つことは無い）。

さて, 媒質の電磁波には屈折率 $n$という量が次式のように定義される:

$n=\sqrt{\frac{\epsilon\mu}{\epsilon_0\mu_0}}$

これは $\epsilon \mu$が一般に複素数である（注: 実数も複素数の一種である。虚数部が0であるような複素数が実数である）ため, 複素屈折率とも呼ばれる。この両辺の絶対値をとれば, 

$|n|=\sqrt{\frac{|\epsilon\mu|}{\epsilon_0\mu_0}} = \frac{c}{c'}$

となる。ここで $c$は真空の光速, $c'$は媒質中の光速（性質3'）である。つまり複素屈折率の絶対値は, 光速の比（真空の光速/媒質中の光速）である。当然ながら, もしも $\epsilon \mu$が実数なら, $n$も実数なので, 上の式で絶対値をつける必要は無くなり, 

$n=\frac{c}{c'}$

となる。この式はhigh schoolの初等物理学でよく見られる式だが, それは屈折率が実数であるという特別なケースであることを理解されたい。

また, 透磁率$\mu$は, 磁性体でない限りほぼ$\mu_0$とみなせるため, 非磁性体では

$n=\sqrt{\frac{\epsilon\mu}{\epsilon_0\mu_0}}\fallingdotseq \sqrt{\frac{\epsilon\mu_0}{\epsilon_0\mu_0}}\fallingdotseq \sqrt{\frac{\epsilon}{\epsilon_0}}$

となる。ここで

$\epsilon_\text{r}:=\frac{\epsilon}{\epsilon_0}$

を比誘電率という。すると上の式は, 

$n\fallingdotseq \sqrt{\epsilon_\text{r}}$ あるいは, $\epsilon_\text{r}\fallingdotseq n^2$

となる。つまり, 非磁性体の屈折率は（近似的に）比誘電率の平方根に等しい。

## 偏光

光には偏光という属性がある。端的に言えばぞれは電場の向きである。前述のように
人の目では感知できない。昆虫や頭足類, 鳥類には, 偏光を感知できるものがある。
無偏光

## 双極子放射と散乱

光が物体に当たったとき, 入射光とは別の方向に向けて物体から光が出ることがある。それを散乱という。後に述べる反射は散乱の一種である。

散乱はどのように起きるのだろうか? 量子論的な説明と, 古典論的（電磁気学的）な説明がある。入射光の光子が物体中の電子を励起し, それが遷移することで別の光子が出るというのが前者の説明である。これは正しいのだが複雑であり, 現実の散乱では後者の説明が使われることが多い。それは, 入射波の電場が物体中の電子に力を及ぼし, それによって電子が振動することで, あたかも電子が1つの小さなアンテナのように光を出すというものである。これを双極子放射という。その原理は, 荷電粒子が運動するとき, その加速度に比例する電場を持つような光を放射するというものである（注: この原理は多くの現象を説明する。たとえばタンパク質のX線解析に利用される, 加速器の放射光は, 高速運動する電子を磁場で曲げたり振動させることで得られる。）。なお, 双極子とは, 正と負の電荷がわずかな距離を隔てて存在する状況を意味する。双極子放射はこの正負が時間と共に入れ替わるときに光が生じるのである。

双極子放射は, 振動する電荷（交流電流）が光源である。その強さと方向には強い異方性がある。これは多くの散乱現象の特徴を説明するので, ここで詳しく見ておこう: まず双極子放射の電場は, 粒子の加速度に比例する。電荷が原点付近でz軸に沿って振動しているとする。光は全方向に広がるが, 特にz=0の平面で最も強く, z軸の正負の方向で弱い。イメージとしてはドーナツ状に光が広がると考えればよい。そして, 偏光はz軸を含む平面内に限定される。たとえばxz平面内の光はその偏光はy成分を持たない。

さて, 最もシンプルな散乱はレーリー散乱である。これは空間中に薄くランダムに分布する小粒子による散乱である。個々の粒子に光があたり, それが1個の双極子として光を出す。レーリー散乱には2つの顕著な特徴がある。まず, 波長が短い光ほど強く散乱される。そして, 強く偏光する。前者は次のように説明される: 入射光の波長を$\lambda$とすると, 振動の角速度$\omega$は, $\omega=ck=2\pi c/\lambda$であり, つまり波長に反比例する。角速度$\omega$の正弦的な力を受ける電子は同じ角速度で正弦的に振動するが, その加速度は位置の2階導関数なので$\omega^2$に比例する。従って双極子放射の電場は$\omega^2$に比例する。光の強度（エネルギー）は電場の2乗に比例するため, この場合は$\omega^4$に比例する。つまり, レーリー散乱による双極子放射の強度は波長の4乗に反比例するのだ。これが空が青い理由である。大気分子は太陽光をレーリー散乱するが, 可視光の中で最も波長の短いのが青色であるため, 我々の目には空は青く見えるのである。

粒子がそれなりに大きいと, 粒子内で複数の双極子が互いにズレたタイミングで双極子放射することになる。その場合は, 複数の双極子放射が重ね合わさるために, 結果として散乱光の波長特性, 方向性, 偏光などはケースバイケースで様々なものになるが, レーリー散乱に比べれば, 波長特性は弱くなる。つまり様々な波長の光をそれなりに均等に散乱する。これがミー散乱であり, 塵（エアロゾル）や雲が白い理由である。

レーリー散乱もミー散乱も, 入射光と同じ波長の光が生じる。ところが, 入射光とは違う波長の光が生じる散乱もある。それがラマン散乱である。ラマン散乱は量子論で説明される。すなわち, 入射光の光子が電子を励起し, それが遷移する際に, 基底状態とはやや異なる状態に遷移する。従って放出される光子は入射光の光子より低エネルギーだったり高エネルギーだったりする。すなわち, 散乱光の波長は入射光の波長とは異なる。ラマン散乱はレーリー散乱よりもはるかに微弱である。

## 反射

光がその波長よりはるかに大きな物体に当たった場合, その散乱は反射と呼ばれる。それは膨大な数の粒子による双極子放射が重なり合うことで実現されるのだが, むしろ一様な媒質どうしが隣接し合う状況でのマクスウェル方程式の境界値問題として説明されるのが普通である。特に境界が平面の場合はフレネル反射と呼ばれ, その結果は以下のようになる：

$r_{H}=-\frac{Z_{1}\cos\theta_{2}-Z_{2}\cos\theta_{1}}{Z_{1}\cos\theta_{2}+Z_{2}\cos\theta_{1}}$

$r_{V}=\frac{Z_{1}\cos\theta_{1}-Z_{2}\cos\theta_{2}}{Z_{1}\cos\theta_{1}+Z_{2}\cos\theta_{2}}$

ここで, $r_\text{H}$は水平偏波の電場反射係数, $r_\text{V}$は垂直偏波の電場反射係数である。下付きの1, 2は媒質1, 媒質2を表す。$\theta_1$は入射角, $\theta_2$は透過角で, それらの間にはSnellの法則と言って, 以下の式が成り立つことが示される:

$n_1 \sin \theta_1 = n2 \sin \theta_2$

$Z$はインピーダンスで, 次式で定義される:

$Z:=\sqrt{\mu/\epsilon}$

ここで, 媒質1, 2が非磁性体なら $\mu_1\fallingdotseq \mu_2 \fallingdotseq \mu_0$とみなせるので, $Z_1/Z_2\fallingdotseq=\sqrt{\epsilon2/\epsilon1}=n_2/n_1$となる。この $n_\text{r}:=n_2/n_1$は相対屈折率と呼ばれる。それを使うと上の式は次のようになる:

$r_{H}=-\frac{n_\text{r}\cos\theta_{2}-\cos\theta_{1}}{n_\text{r}\cos\theta_{2}+\cos\theta_{1}}$

$r_{V}=\frac{n_\text{r}\cos\theta_{1}-\cos\theta_{2}}{n_\text{r}\cos\theta_{1}+\cos\theta_{2}}$

ここで$n_\text{r}=1$の場合, スネルの法則から$\theta_{1}=\theta_{2}$となり, 上の式はともに0になる。つまり反射は消える。そのため「屈折率が等しい媒質同士の境界では反射が起きない」とよく言われる。しかしこれは「非磁性体」の仮定のもとでの話である。厳密には, 「インピーダンスが等しい媒質同士」である。

さて, 相対屈折率$n$は, 非磁性体という条件では比誘電率 $\epsilon_\text{r}$の平方根にほぼ等しい。これを使って上の式を変形すると次式が得られる:

$r_{H}=\frac{\cos\theta_{1}-\sqrt{\epsilon_\text{r}-\sin^{2}\theta_{1}}}{\cos\theta_{1}+\sqrt{\epsilon_\text{r}-\sin^{2}\theta_{1}}}$

$r_{V}=-\frac{\sqrt{\epsilon_\text{r}-\sin^{2}\theta_{1}}-\epsilon_\text{r}\cos\theta_{1}}{\sqrt{\epsilon_\text{r}-\sin^{2}\theta_{1}}+\epsilon_\text{r}\cos\theta_{1}}$

これをグラフに描くと以下のようになる：
（図）

なめらかな平面とは言えない場合
Lambertian


## 分散

## 光の吸収
キルヒホッフの法則

単一散乱アルベド

先に言及した熱放射において, 放射率

## 分光測定



