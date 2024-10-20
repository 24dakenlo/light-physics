本章は放射生態学 radiation ecologyで必要な物理学的基礎を述べる。radiation ecologyのradiationとは光のことである。

光は生態系において一次生産を駆動する大切なエネルギー源であると同時に, 生物同士（人間を含む）が互いにコミュニケーションに用いる媒体でもある。従って光の科学的性質を理解することは重要である（注: 光のことを「放射」と呼ぶことがある。一般に「放射」と言えばα線やβ線のような粒子線も含むが, 本書ではそれらは考えない）。

光は我々の身近にあるので, 我々は光について体験的によく知っていると思っている。しかし光の科学（物理学）なそんなに簡単ではない。そもそも, 人類が光の科学的な性質を理解したのは20世紀以降なのである。その最も大きな困難は, 光が2つの側面を持つという事実である。すなわち, 「光子」という粒子としての側面と, 「電磁波」という波としての側面である。粒子と言えば砂やピンポン玉のようなものをイメージするし, 波と言えば海の波のようなものをイメージする。これらが同時に両立する何ものかをイメージすることはほとんど不可能だ。にもかかわらず, 光にはこのような二面性（duality）があることを受け入れたことで, 人は光を理解することができるようになった（注: イメージできないのに理解できるということに読者は戸惑うかもしれないが, 「現象を記述し予測できること」を理解と定義すれば, イメージできるか否かは理解とは無関係である。）。

　実は粒子性と波動性の二面性は光に限ったことではなく, 電子や原子や陽子や中性子などの微小な粒子にも存在する。そのような存在（粒子性と波動性の二面性を持つ物理的実体）を「量子」と呼ぶ。そして, 量子の挙動を体系化した理論が「量子力学」である。光が物質に吸収されたり散乱されたり, あるいは物質から光が放射される現象は, 根源的には量子力学で理解・説明される。たとえば葉の光合成色素が光を吸収したり蛍光（注: 後で説明する）を発する現象を理解するには量子力学が必要である。
 
　量子力学に馴染みのある生態学者は多くはないだろう。そこでまず, 量子力学について説明する。以下, 我々の想像や納得が難しい話が続くが, その正しさを裏付けるのは「そう考えれば様々なことが辻褄が合う」という実験的事実であり, 我々は深く考えずに受け入れるべきである（注: 実際, 物理学の専門家ですら, 量子力学の概念を直感的な想像で納得することを諦めている。）。
 
　量子力学では, 量子の状態を1つの数学的な関数（注: あるいはベクトル。ここでいうベクトルとは速度や力のような「向きと大きさを持つ量」ではなく, 抽象的な概念である）で表す。その関数が, 時刻 $t$について周期的な性質を持つとき, その量子のエネルギーが確定すると考え, その状態をエネルギー固有状態と呼ぶ。そしてそのエネルギーEは, 
 
$E = h\nu$      (1)
 
と表されると考える。 $\nu$は振動数, すなわち周期の逆数である（注: $\nu$はギリシア文字のニューである。 $v$と混同しないように注意せよ）。 $h$はプランク定数と呼ばれる, 物理定数で, $6.63\times 10^{-34}\text {J s}$である（注: プランク定数は物理学において最も基本的で重要な定数のひとつである。その値は国際単位系の基盤として$6.62607015\times 10^{-34}\text {J s}$と定義されている。）。

　この式(1)は, 光子でも電子でも同様に成り立つ。特に光子の場合はこの振動数νは波としての振動数（つまり波が単位時間あたりに何回の振動を繰り返すか）と同じである。

　ここで波に関する基本的な事柄を確認しよう。波とは一定のパターンが空間を伝わる現象である。特にそのパターンがsinやcosのような三角関数で表されるものは正弦波と呼ばれ, 最も基本的な波とされる。そして正弦波以外の波は, 周期が異なる多様な正弦波を重ね合わせることで表現できる（注: これはフーリエ解析と呼ばれる数学的な考え方だが, 光を含む多くの現象に理解・記述で有用・重要である）。正弦波について, 速さを $u$, 波長を $\lambda$, 周期を $T$とすると（注: $T$は後で温度の記号としても使う。それぞれの文脈で記号が何を意味するかを正しく識別することは重要である）次式が成り立つ:
 
$u = \lambda/T$        (2)
 
これは, ある地点を基本波形（正弦波の山と谷を1つずつ含む波形）の1つが通過するのにかかる時間が $T$であり, その間, 基本波形の先頭は距離 $\lambda$だけ進むので, その速さ（距離/時間）は $\lambda/T$と考えれば容易に理解できよう。

　そして, 周期 $T$は振動数 $\nu$, 角振動数 $\omega$と以下のような関係にある:
 
$\nu = 1/T$         (3)
 
$\omega = 2\pi/T = 2\pi\nu$   (4)
 
これらの3つの量 ($T$, $\nu$, $\omega$) は上記の式で互いに関係づけられているので, 本質的には1つだけを考えればよい。しかし分野や話題によって, この中のどれを好んで使うかは異なるので, 全てに慣れておくことが望ましい。

　また, 波長 $\lambda$は, 「波数」と呼ばれる量 $k$と以下のような関係にある:
 
$k=2\pi/\lambda$      (5)
 
これらの2つの量（$\lambda$, $k$）も式(5)で互いに関係づけられているので, 本質的には1つだけを考えればよいような気がするが, 実はそうではない。波数は本質的にはベクトルであり, ${\bf k}=(k_x, k_y, k_z)$という3つの成分を持ち（注: 物理学ではベクトルは ${\bf k}$のようにボールド体で表記する慣習である。 $\vec{k}$というふうに, 上付き矢印で表記することもある。）, その方向は波の進行方向を指している。式(5)でいう $k$はベクトル ${\bf k}$の大きさなのである（ただしこのあたりの事情は今は重要ではないので理解にこだわる必要はない）。

　ここで記号の慣習について説明しておく。エネルギーを $E$, 振動数を $\nu$, 周期を $T$などと書いてきたが, それらは慣習であり, そうせねばならないという規則は無い（注: $E$がエネルギーの頭文字であるように, 多くの慣習的記号はその量の呼び名を想起させるものが使われる。しかし角振動数 $\omega$など, その限りではないものもある。また, プランク定数 $h$のような基本定数は慣習よりも強い強制力で記号が定まっている。）。実際, 振動数を $f$と書く慣習もある ($\nu$は高い振動数, $f$は低い振動数の現象で使われる傾向にある)。だからといって, エネルギーを $T$と書いたり, 振動数を $E$と書いたりするのは混乱の元であり, 極力避けるべきだ。事情が許す限り慣習に沿った記号を使うことで, 科学のコミュニティの中で相互理解が楽になる。

　さて, 物理学者は $T$, $\nu$, $\omega$のうち $\omega$を好んで使う。そうすると数式の扱いが楽になるからである。そこで式(4)を使って式(1)を書き換えると, 
 
$E = h\omega/(2\pi)$
 
となる。ここで $h/(2\pi)$を $\hbar$（注: エイチバーと発音する。ディラック定数と呼ばれる。）と書いて, 

$E = \hbar\omega$    (6)
 
と書くことが多い。この式は原子や分子のエネルギー準位（後述する）を考えたり, 原子や分子による光子の吸収・放出を考えるときによく出てくる。

　また, 式(4)を使って式(2)を書き換えると, 
 
$u = \omega/k$     (7)
  
となる。式(2)や式(7)は, 波の屈折の議論で登場する（注: この式(7)は位相速度と呼ばれるものであり, 類似するが別の概念として群速度というものがある。）。

　さて, 式(2), (3)より, $\nu=1/T=u/\lambda$であり, それを(1)に代入すると, $E=hu/\lambda$となる。ここで話を光に限定すれば, その速さ$u$は真空中では一定値3.00 m/sであり（注: 正確には $c=299792458 \text{m/s}$。これはプランク定数と同様に国際単位系を定義づける数値。）であり, それを $c$と表すことが決まっている。つまり, 光については, 
 
$E=hc/\lambda$    (8)
 
が成り立つ。これは光子のエネルギーを表す式として頻出する（注: 式(1), 式(6)は光子だけでなくあらゆる量子について成り立つ式だが, 式(8)は光子に限定して成り立つことに注意せよ。）。

演習問題

[エネルギー順位と遷移]

次に, 光子の生成と消滅について学ぼう。太陽, レーザー, 蛍光灯など, 自ら輝いて光子を生成する物体は様々である。それらに共通する基本的な物理過程は, 量子のエネルギー順位の遷移という量子力学的な現象である。

先程, 量子のエネルギー固有状態について述べた。ひとつの量子について, 様々なエネルギー固有状態を考えることができる。例えば原子の中の電子について, 電子が原子核に近い空間に分布するようなエネルギー固有状態がありえるし, 原子核から遠い空間に分布するようなエネルギー固有状態もありえる。そして電子のエネルギーは前者で低く後者で高い（注: これは電子が負の電荷を持ち, 原子核が正の電荷を持つからである。正負の電荷は近接するほどエネルギーは低くなる）。

興味深いことに, 原子の中の電子, つまり原子核に引きつけられている電子のエネルギーは連続的な値を取ることができない, つまり離散的である。これは電子のエネルギー固有状態が, ある数学的な制約条件を満たす必要から生じる。この原子内の電子の例だけでなく, 量子のエネルギーが離散的になることは他にも多い（注: たとえば多原子分子の振動や回転のエネルギーも離散的になる。）。

ある量子に関して, 固有状態のエネルギーが離散化的であるとき, そのエネルギーを高低の順にならべたものをエネルギー準位という（注: それらに対応するエネルギー固有状態を指すこともある）。

量子はエネルギーの異なる固有状態（エネルギー準位）の間で移り変わることがある。これを遷移という。そして, 高エネルギーの状態と低エネルギーの状態の間で量子が遷移するとき, その差に相当するエネルギーが何らかの形で放出または吸収される（注: これはエネルギー保存則から必然的である）。エネルギーを光子として放出するとき（そうでないときもある。熱としてエネルギーが放出される場合もある。）, 物質は光を放ち, エネルギーを光子として吸収するとき, 物質は光を吸収する。そのような場合, 状態間のエネルギーの差は光子のエネルギーに等しいので:

$h\nu = E_\text{high} - E_\text{low}$
 
が成り立つ（$\nu$は放出又は吸収される光子の振動数であり, $E_\text{high}$と $E_\text{low}$はそれぞれ高エネルギーと低エネルギーの量子状態のエネルギーである）。

例: ナトリウム原子の最外殻電子は, 3$p$軌道と呼ばれるエネルギー固有状態から3$s$軌道と呼ばれるエネルギー固有状態へ遷移することで, 波長が約590 nmの光子を出す。これは黄色い光であり, D線と呼ばれる（注: 細かく見ると, D線の光は微妙に異なる2つの波長の光からなる。なお, D線を用いたナトリウムランプは長寿命で効率が良いため, 長らくトンネル内の照明に使われた。）。このD線の光子のエネルギーを式(8)で計算すると $3.37×10^{-19}$ Jである。上の式によれば, これが両状態のエネルギーの差 $E_\text{high} - E_\text{low}$である。

この例で見たナトリウム原子のように, 物質（原子）はそれぞれに固有のエネルギー準位を持つ。そのため, 特定の波長の光子を強く吸収または放出することが多い（注: これを利用すると, 物体が吸収・放出する光の波長を計測することで, 物体を構成する物質やその状態を推定できる。天文学で彼方の天体の校正元素を知ることができるのはこれを利用している。）。

　たとえば太陽光は後述する熱放射という過程で光を放つが, 地上に届く太陽光は特定の波長の光が顕著に弱くなっている。それをフラウンホーファー線と呼ぶ。そのひとつは590 nmの光である。太陽光中の590 nmの光は弱いのだ。これは上の例で述べたナトリウム原子のD線である。太陽の中にナトリウム原子が存在し, その最外殻電子が遷移することで, D線を吸収するのである（注: 歴史的には話は逆であり, D線はまずフラウンホーファー線として発見された）。フラウンホーファー線の別の例として, A線と呼ばれる波長759 nmの光がある。これは地球大気の酸素分子(O2)による吸収に起因する（注: 従って地球大気の外, すなわち宇宙空間で太陽光を観測するとこのA線は見られない。）。そのためO2A線とかO2Aバンドとも呼ばれる。この波長帯は植生がクロロフィル蛍光（後述）によって放出する光の波長帯と重なっているため, クロロフィル蛍光の観測に利用される。

さて, この遷移は確率的に起きる。つまり, エネルギー準位の高い状態にある量子が, 一定時間の間に低い準位に遷移するのは気まぐれである。その確率は量子力学によって予測できるが, その詳細はここでは述べない（注: フェルミの黄金律）。

基底状態
励起

[熱放射]

さて, 生態系で最も重要な光源は言うまでもなく太陽光である。太陽光は今から説明する熱放射という物理現象で生成される。そして地球上の地物・生物が発する赤外線も熱放射で生成される。熱放射は地球の熱環境を司る最も重要な物理過程である。熱放射について知れば, これらの重要なトピックの理解・研究に役立つ。

熱放射は端的に言えば, あらゆる物体はその温度に応じた強度と波長分布で光を出す, という現象である。これは一見奇妙なことだ。熱く輝く太陽が光を出すのはもっともに思えるが, 冷たい石や氷ですら光を出すのか? 実際, そうなのだ。冷たい石や氷は太陽ほど明るくはないし, 人の肉眼で検知できるほど短い波長でもないが, それなりに光を出す。我々の直感に反するが, これは事実である。実際, その光を検出することで, 人工衛星は極地の氷床の温度を遠隔計測している。

熱放射は, 物体を構成する粒子（電子や原子など）の熱的エネルギーが関係する。すなわち, 物体がある温度にあるとき, その温度に応じた激しさで粒子は運動している。逆に言えば, 温度というのは粒子たちのエネルギーの平均値の指標である（注: エネルギー等し分配則。粒子の1自由度あたりの平均エネルギーは $k_\text{B}T/2$。ここでTは絶対温度, $k_\text{B}$はボルツマン定数=1.38×10^{-23} J/K）。平均値と言ったのは, 実際はそれよりも高いエネルギーの粒子もあれば, 低いエネルギーの粒子もあるからである（注: 物体が熱平衡状態にあるとき, その構成粒子の熱的エネルギーの確率分布は, ボルツマン分布という理論で表現される）。従って, 電子などの量子の一部は, 基底状態から励起され, エネルギー準位の上位に存在する。それらが基底状態に遷移することで光が出る。基底状態に戻ってエネルギーが下がった量子は, 周囲の粒子の熱運動の影響を受けて（他の量子が出した光子を吸収することもある）エネルギーを回復し, 励起し, また光子を出す, ということを繰り返すのだ。こうして光子が物体から次々に放出される現象が熱放射である。

熱放射にはプランクの法則という, 次式で表される理論が存在する。

$B(\lambda, T) = \frac{2 h c^2}{\lambda^5} \frac{1}{\text{exp}\Bigl(\frac{h c}{\lambda k_\text{B} T}\Bigr) - 1}$

where:
$B(\lambda, T)$ is the spectral radiance (power per unit area per unit wavelength per unit solid angle) at wavelength $\lambda$ and temperature $T$; $h$ is Planck's constant ($6.626 \times 10^{-34}$ J$\cdot$s); $c$ is the speed of light in a vacuum ($3.00 \times 10^8$ m/s); $\lambda$ is the wavelength of the photon; $k_\text{B}$ is the Boltzmann constant ($1.381 \times 10^{-23}$ J/K); $T$ is the absolute temperature; $e$ is the base of the natural logarithm.

ただしこれは状況を理想化・単純化したモデルであるため, 実際の物体の熱放射はこの法則どおりにはいかない。より具体的に言えば, プランクの法則は, 全ての波長で可能な限り最も強い光を出すような理想的な状況を想定している。この想定を満たす物体を黒体（blackbody）もしくは完全黒体と呼び, その熱放射を黒体放射と呼ぶ。プランクの法則が述べるのは, 黒体放射で出てくる光の強度を波長の関数として表したものである。実際の物体の熱放射は黒体放射より小さい。物体の熱放射の強度を黒体放射の強度で割った値を射出率（emissivity）という。射出率は0から1の実数値であり, 物体によって変わるし, 波長によっても変わる。後に述べる「偏光」によっても変わる。

さて, 現実の物体の熱放射と多少のズレがあるとはいえ, プランクの法則は熱放射の良いモデルであり, 我々が熱放射を論じる時の基礎である。プランクの法則をグラフにすると図___のようになる。このグラフを0から∞まで積分すると, 全波長で合計した熱放射のエネルギーが得られ, それは絶対温度の4乗に比例することがわかっている。これをステファン・ボルツマンの法則という。すなわち, 

$B = \epsilon \sigma T^4$      ()

である。ここでBは単位表面積あたり, 単位時間あたりに射出される全エネルギー, εは射出率, σはステファン・ボルツマン定数と呼ばれる定数で, $5.67\times 10^{-8}$ W m$^{-2}$ K$^{-4}$である（注: この定数は, 5, 6, 7, 8が順に並んでいるので覚えやすい。実際, 覚えておくと環境の熱収支を考察するときに便利である。）。

　また, このグラフのピークの位置を求めることもできる。それは関数を微分し, 導関数が0になる波長を求めればよい。その結果, ピーク波長は温度($T$)に反比例することがわかる。これをウィーンの変位則という。すなわち, 
 
$\lambda_\text{max} = 0.003\text{ m K} / T$

である（注: 右辺の分母のTがイタリック体で, 分子のm Kがローマン体であることに注意せよ。イタリック体は変数や定数の記号であり, ローマン体は単位の記号を表す。つまり $T$は温度という量を表す変数で, mとKはそれぞれメートル, ケルビンという単位である。mとKの間にスペースがあることにも注意せよ。これはミリケルビン(mK)ではなく, メートルとケルビンの積であることを意味する。教科書によってはこの分子のm Kを書かないことがあるが, それは間違いである。$T$が温度であり, $\lambda_\text{max}$が長さであるため, 次元を合わせるには, 長さと温度の量が分子になくては辻褄が合わない。ここでは単位長さmと単位温度Kがその役割を果たしている。）。

例題: 太陽の表面温度は約6000 Kである。太陽を黒体と近似し, 太陽からの熱放射の強度とピーク波長を見積もれ。

解答: $\epsilon=1$とおいて, ステファン・ボルツマンの法則とウィーンの変位則を使う:

$B = 5.67\times 10^{-8}\text{ W m}^{-2}\text{ K}^{-4}\times(6000\text{ K})^4 = 7.3\times 10^{11}\text{ W m}^{-2}$

$\lambda_\text{max} = 0.003\text{ m K} / (6000\text{ K}) = 0.00001\text{ m} = 10\text{ }\micro\text{m}$

上の例題で, 太陽の熱放射の強度が大きな値になったことに驚いただろう。太陽はこれほど強力な光源である。しかし, その光は全方向に広がるので, 地球に到達する頃にはずいぶん薄まっている。その効果は距離の2乗に反比例する。太陽ー地球間距離(150,000,000 km)は太陽半径(700,000 km)の210倍なので, 地球に届く太陽放射は上記の1/210$^2$, つまり


# light-physics

In this chapter, we will explain the fundamental physics that we need for studying radiation ecology, without getting too technical.

## Radiation is light

"Radiation" means a beam of tiny particles. For example, $\alpha$ ray is a beam of $\alpha$ particles (nucleus of helium), while $\beta$ ray is a beam of electrons. However, "radiation" in "radiation ecology" means, specifically, a beam of particles called "photons". It is also a wave called "electromagnetic wave". These two words mean a same phenomenon which we call "light". You may wonder "how are particles and a wave same?". We will see it later. 

The theory of light is called "optics". Therefore, radiation ecology is an ecology which is strongly related to optics. 

## Visible light and invisible light

In daily life, by the word "light" we usually mean the light which we can see, such as the light of sun or desktop display. They are categorized as "visible light". Invisible light also exists in nature. Ultraviolet (UV) light and infrared light are examples of the invisible light. What is different is wavelength. The wavelength of the visible light is, roughly speaking, in between 400 nm and 700 nm (nm is "nano meter", which is equal to $10^{-9}\text{ m}$ and $0.001 \micro\text{ m}$). This range of light can activate human eyes' photo receptors, hence we can "see" them. The light which is outside this range is the invisible light. For example, a light with wavelength a little shorter than the visible light is the ultraviolet (UV) light, whereas a little longer one is the near infrared (NIR) light. Likewise, light is categorized into groups by wavelength: from shorter to longer, $\gamma$ ray, X ray, ultraviolet (UV) light, visible light, near infrared (NIR) light, shortwave infrared (SWIR) light, thermal infrared (TIR) light, microwave, etc. The "radio wave" used in the broadcast of TVs or radios are also light, whose wavelength is even longer. 

## Wavelength of light

Wavelength is an important feature of light, because the nature and the behavior of light strongly depends on its wavelength. Wavelength is defined for a wave whose pattern is sinusoidal. "Sinusoidal" means, it is described by a trigonometry function such as sine and cosine. The wavelength is the distance between a peak and the nearest peak (or bottom to the nearest bottom). A Greek letter $\lambda$ is conventionally and popularly used to describe wavelength.

A very important fact: a photon's energy $E$ is directly connected to the wavelenght $\lambda$ by a formula:

$E=\frac{hc}{\lambda}$, (eq. 1-1)

$where$, $h\fallingdotseq 6.63\times10^{-34}$ J s is the "Planck constant" and $c\fallingdotseq 3.00\times10^{8} \text{m s}^{-1}$ is the "speed of light", both of which are fundamental constants in physics. Let's try some exercises:

#### Exercise 1-1: Derive enery of a photon in case (1) $\lambda = 450\text{ nm}$, (2) $\lambda = 680\text{ nm}$. 
Answer: (1) $E=6.63\times10^{-34}\text{J s}\times 3.00\times 10^{8} \text{m s}^{-1}/(450\times 10^{-9} \text{m})=4.4\times 10^{-19}\text{ J}$. (2) $E=2.9\times 10^{-19}\text{ J}$.

This exercise calculated energy of photon of two lights: blue light (1) and red light (2) both of which are at the peak of absorption by the chlorophyll $a$ which is a main pigment of photosynthesis by terrestrial plants. The result shows the photon's enegy of blue light is larger than that of red light. It is understandable because the formula indicates inversely proportional relation between the energy and the wavelength: the longer the wavelength, the smaller the energy. An example which is related to this fact is, when we watch an old poster photo which has been displayed on a wall for long time: Red color disappears faster than blue paint, resulting in pale, blueish photo on the poster. It is because the red pigment preferably absorbs light in shorter wavelength (such as blue or UV) who has enough high energy to destroy the structure of the pigment. In other words, by absorbing the destructive photons of the short wave light, the red or brown pigments block them. It is the reason why some plants' leaves are red: their red pigments blocks harmful photons contained in the sunlight or skylight from going inside the leaf and destroy the tissue.

## particle and wave?

But wait. Don't you deel strange? While we were talking about photon's energy, "wavelength" sudenly came up. Wavelength is a feature of a sinusoidal wave. It is hard to connect an idea of wavelength to a particle, because a sinusoidal wave repeats the same pattern from far away to far away. It does not look like a single particle which we imagine like a small basket ball. It is a mysterious story. As mentioned, light has two aspects: wave and particle. Many people try imagining light in such a way that satisfies these two aspects at a same time in vein. Not only you but also everybody may feel uneasy to catch up this mystery. My suggestion: give up imagination and accept the two aspects without asking how and why. We call a mysterious particle which has both particle and wave aspects "quantum". The theory of nature and behavior of a quantum is called "quantum dynamics". 


## Quantum dynamics of light and electron

Quantum dynamics is a big subject in physics. It's theoretical basis depends on advanced mathematics which is too much for most of ecologists. Therefore, we give up getting a systematic understanding of the quantum physics, and instead, we will just summarize the most imporatnt and useful concepts and facts in quantum dynamics for builind radiation ecology. 

A photon is a quantum. An electron is also a quantum. Indeed, an electron, which we may imagine as a particle, behaves as a wave in an electron microscope: in that device, we use an electron wave instead of a light wave to capture an image of a tiny target. Interestingly, a photon and an electron interacts with each other in a way electron absorbs or emits a photon. It is a mechanism of absorption and scattering of light by substances such as:

- Absorption of photons by an electron in chlorophyll molecules. It is the start of photosynthesis.
- Scattering of photons by an electron in atmospheric molecules in the sky. It makes blue sky.
- Absorption and emission of photons by electrons in the Sun. It causes sunlight.
- Emission of photons by an electron in chlorophyll molecules. It causes chlorophyll fluorescence.

Therefore, we must learn about electron in order to understand photon's behavior. We summarize the most important rules in quantum dynamics for this purpose:

1. The behavior of an electron or a group of electrons is described by a concept called "quantum state". "State" here is not something like solid, liquid, and gas, which are "thermodynamic state". You may imagine a quantum state like a mathematical function. The phyical properties such as position, energy, momentum (something rekated to velocity), and angular momentum (something related to rotation) are ambiguous unless the quantum state is a special state called "eigenstate" for each property.

2. If the quantum state depends on time in an oscillating manner with a frequency $\nu$ or an angular frequency $\omega$ ($=2\pi\nu$), it is the eigenstate of the energy and the energy $E$ is decided by the following formula (these two are the same):

$E=h\nu$, (eq. 1-2)

$E=\hbar \omega$, (eq. 1-3)

This is a general rule in quantum dynamics. In fact, the energy of photon $E=hc/\lambda$ is also derived from this formula: for light wave, $\nu$ is how many cycles a wave repeats in unit time, hence it is a distance in unit time divided by wavelength, i.e., $\nu=c/\lambda$. By putting this to $E=h\nu$, we get $E=hc/\lambda$. 

3. Depending on situation, an electron (or other quantum) can take various different energy eigen states in a systematic manner. We call them "energy levels." The electron (or quantum) can change its state from one energy eigen state to another. When it happens, the electron (or quantum) can absorb oremit a photon and the photon's energy $E_\text{photon}$ satisfies the following formula:

$E_\text{photon} = E_\text{high}-E_\text{low}$ (eq. 1-4)

where, $E_\text{high}$ and $E_\text{low}$ are the energies of the states between which the electron (or quantum) make a transition. If the transition is from lower energy state to the higher energy state, the photon is aborbed and disappears. If the transition is from the higher energy state to the lower energy state, the photon is emitted. 


## Thermal radiation

Now we learn about light source. In ecology, the the most important light source is "thermal radiation". Every object spontaneously emit light with certain wavelength and intensity determined by its temperature: a hot object emit photons with shorter wavelength and higher intensity. Accordingly, the the Sun (ca 6000 K) emits photons (sunlight) with wavelength mostly in between 0.1 um and 4 um. On the other hand, the Earth (ca 300 K) emits photons with wavelength mostly in between 4 um and 100 um. These two groups of photons are important in the energy balance in the Earth's environment. The former group (0.1 um to 4 um) is called "shortwave radiation", whereas the latter group (4 um to 100 um) is called "longwave radiation".

The mechanism of thermal radiation is as follows: many particles (molecules, atoms, electrons, etc.) which make up an object are in thermal motion: They 

## 
It is a wave which transfers in the "electromagnetif field". So, what is the "electromagnetic field"? It is a basic feature of space that includes both an "electric field" and a "magnetic field." No one knows exactly why space has these features, but they exist.


Light can be thought of in two main ways. One way is as a "wave which travels in the electromagnetic field." In science, this kind of wave is called an "electromagnetic wave" or "radiation." 

The electric field and the magnetic field exert forces on electrically charged particles such as electrons. The force from electric field is independent of the particle's velocity, whereas the force from magnetic field depends on the particle's velocity. More precisely, this relationship is described by the equation:

${\bf F} = q {\bf E} + q {\bf v} \times {\bf B}$    (1.1)

where, ${\bf F}$ is the force on the particle, ${\bf E}$ is the electric field, ${\bf B}$ is the magnetic flux density (an expression of magnetic field), $q$ is the electric charge of the particle, and ${\bf v}$ is the velocity of the particle. The symbol $\times$ means "vector product" which you can find its definition and meaning in a mathematics textbook. This equation is the fundamental fact which defines the two fields, so that we do not need to worry about why they work this way. 


is For convenience, people prefer using a word "light" to describe electromagnetic wave. 


## Light is photons

Another way to think about light is as a "particle produced by the electromagnetic field." The particle is called "photon". Unlike particles we usually think of, like tiny bits of dust, a photon is a much more abstract concept. It is not a normal particle but a special kind of object known as a "quantum." It is an idea of "quantum physics", which mainly treats objects too small to be treated by the physics of our daily life (so called Newtonian dynamics). 

In the radiation ecology, the quantum physics may appear in some topics involving not only photons but also electrons, such as photosunthesis or chlorophyll fluorescence. Therefore, it is a good idea to know about some of the main ideas in quantum physics: 
- Properties such as energy, momentum, and angular momentum of a quantum particle (such as photon and electron) are impossible to determine in general cases.
- Instead, these properties are described by something called a "linear operator."
- The value of these properties is determined if the system is in a special state called an "eigenstate," where the value is equal to something called the "eigenvalue."

In case of the electromagnetic field's energy, the eigenvalue of its "liner operator" (called "Hamiltonian operator") is related to a non-negative integer $n$. We understand this integer $n$ as the number of photons. In other words, we recognize the eigen state of electromagnetic field's energy as "there are $n$ photons in the space". 

You may feel it is too abstract to understand, but it's ok. It's too much for human's intelligence to imagine a perfect picture of a photon. In many cases you may imagine them as tiny balls, but you should remember that sometimes this imagination is invalid.

## Principle of superposition

Regardless of the aspect, ligh has a very important and useful property called "principle of superposition". It is a general idea which can be applied to many phenomena other than light, but we only mention about light here. The "principle of superposition" says "light can be considered as a superposition of many other lights". "Superposition" is a technical word in physics. It is like "combination" or "mixture". Let's look at an example. 

We imagine several different light waves existing in a same space. We will call electric field of the light waves as ${\bf E}_1, {\bf E}_2, {\bf E}_3,…, {\bf E}_n$. ${\bf E}_i$ describes electric field produced by the $i$-th wave. ${\bf E}_i$ is a function of time and place. Then a new light wave can be created by combining (superpositioning) these waves like this:

${\bf E} = a_1 {\bf E}_1 + a_2 {\bf E}_2 + ... + a_n {\bf E}_n$

Here, ${\bf E}$ is (the electric field of) the new light wave, and it is made up of the original waves ${\bf E}_1$, ${\bf E}_2$, …, ${\bf E}_n$, with each wave multiplied by a certain number (called a scalar) $a_1, a_2,…, a_n$. This form (multiplying things by scalars and summing up them) is exactly called "superposition" in physics, or "linear combination" in mathematics. If you learn the fundamental theories of light, you would find that the any linear combination of lights also satisfies the theory. It is the reason why this principle is valid for light.


## Fourier analysis

For the moment, let's consider light as a wave. The most physics textbooks mention "sinusoidal wave", which is described by the trigonometric functions: cos⁡(x) and sin(x). These functions repeat the same "up and down" pattern over and over again, meaning they are "periodic."

(figure of sinusoidal wave)

However, sinusoidal waves are just one type of waves. A wave is not have to be sinusoidal. Any patterns that moves through space can be a wave. The "pattern" can be mostly any shapes you can imagine, like a pulse, a bell shape, or sinusoidal. For instance, a flash light is like a pulse pattern moving through space. 

But still, sinusoidal wave concepts are useful enough to describe and understand light waves. Why? Because sinusoidal light wave is so simple that its treatment is easy and straightforward. Moreover, by using the afforementioned "principle of superposition", we can describe any pattern of light waves by superposition of sinusoidal lights. And surprisingly, mathematicians have proved that virtually any shapes of waves can be described in this way. This idea and theory is called "Fourier analysis". It is creating an arbitrary wave (or decomposing a wave) by superposition of sinusoidal waves with various wavelength. 

Hereafter, we may call a sinusoidal light as a "monochromatic light". It means "light with a single wavelength". The word "monochromatic" consists of "mono" meaning "single" and "chrome" meaning "color". Why color? You would understand later soon. 


## Spectrum

By using Fourier analysis, we may consider light as superposition of monochromatic lights with various wavelength. Therefore, we may simply focus on understanding the monochromatic light. If we need to consider more complicated cases, we can imagine the superposition of monochromatic lights ${\bf E}_1, {\bf E}_2, {\bf E}_3,…, {\bf E}_n$ with various wavelength $\lambda_1, \lambda_2, ..., \lambda_n$. Then what matters next is the coefficients $a_1, a_2, ... a_n$ which tell us the contribution of the monochromatic lights. In other words, each of $a_1, a_2, ... a_n$ describes the amplitude of each monochromatic light. In many cases we are interested in their squared values because the energy of light is proportional to the square of its amplitude. The graph of the wavelength (x-axis) and square of the amplitudes of the monochromatic lights is called a "spectrum." 

The spectrum is a very common way of describing phenomena of light so that we should be familiar with it. For instance, the spectrum of the sunlight is as follows (Figure):

We can see the sunlight consists of various wavelength of sinuspidal lights. Particularly, the graph has a peak in between 400 nm to 700 nm. It means that a big portion of energy of the sunlight comes from the sinusoidal waves with wavelength in between 400 nm and 700 nm. This category of light is called "visible light" because our human eyes can sense them. Coincidentally, they are "photosynthetically active radiation" which activates photosynthesys in many of the terrestrial plants. 


## Categories of light

As I wrote, the wange of wavelength of visible light, or the light human's eyes can detect, is between 400 nm to 700 nm. Although it occupies a big portion of solar light, it is a very narrow and limitted category of light in nature. In fact, lights' wavelength can be much shorter or longer than them. From short to long, we can call lights as: gamma-ray, X-ray, ultraviolet (UV), visible light, infrared light, microwave, .... These cateories do not have reasonably clear boundaries with each other. Actually, the wavelength of light can take positive values arbitrarily and continuously. Nonetheless, it is convenient to categorize light into these groups because the features and behaviours of light depends on the scale of wavelength so strongly that we may need to consider a different model for each of them. For example, interaction of light and a plant leaf is very different between visible light and microwave: visible light can be largely absorbed or reflected by the leaf, while microwave may have little interaction with the leaf.


## Colors of visible light

The color sense of human's vision is essentially related to the spectrum. In short, if a spectrum of light is given, we can predict its color. How? The human's eyes have three different types of color-sensing cells called "cones". The brain recognizes colors by the signals from these three types of cones, namely, "S-cones", "M-cones", and "L-cones", as blue color, green color, and red color, respectively. The intensity of the response of each type of cone depends on the light's spectrum: If the dominant wavelength are 400 nm in the spectrum, the S-cones' response is big and other cones' response is small, resulting in the recognition of blue by the brain. If the light's spectrum consists of multiple peaks or broad range of wavelength, all the S-, M-, and L-cones responds differently and the color is a mixture of blue, green, and red, resulting in a huge variation of possible colors. 

As I wrote, the human's vision takes place when our eyes are illuminated by the light called "visible light", whose wavelength is in between about 400 nm and about 700 nm. Our eyes cannot detect light whose wavelength is outside this range. It is because the cones in human's eyes do not respond to such light. Therefore, if some animals have different types of cones from human, they may be able to see light which is invisible for human. In fact, birds and some insects have cones which respond to UV light, whose wavelength is shorter that our visible light. Therefore, we should consider invisible light (for us) when we study about those animal's vision.

I explained that a spectrum decides color of the light. Interestingly, the reverse story is invalid. Namely, a color does not decide lights' spectrum. In other words, lights with different spectrum can have a same color. Let's understand it by an example: suppose a light with a spectrum of double peaks at 550 nm (stimulating M-cones) and 680 nm (stimulating L-cones). Then the color is a mixture of green (response by M-cones) and red (response by L-cones), which is yellow. On the other hand, suppose a light with a single peak around 610 nm. To some extent, both M-cones and L-cones repond to this wavelength, resulting in the the color of a mixture of green and red, which is yellow which is the same as the previous example.

Nonetheless, we may discuss spectrum in a context of colors for convenience. In particular, we describe monochromatic visible ligh not only by wavelength but also its color in an order of shorter wavelength to longer wavelength as follows: violet, purple, blue, green, yellow, orange, red. It is not a coincident that this order is the same as the order of colors in a rainbow. In fact, rainbow is a collection of concentric arcs of monochromatic lights: the inside arc is shorter light (violet or blue) and the outside arc is longer light (red). It is a good idea to memorize this order of colors because it helps us understand and imagine the phenomena of light in terms of wavelengths.

## Features of monochromatic light

Now let's learn about some important feature of monochromatic light. Suppose we consider a monochromatic light 

The most important fact of photons is relation between the energy $E$, frequency $\nu$, wavelength $\lambda$,  of a single photon $E$ is 



## Colors of objects

In the previous section, we discussed about colors of lights. Now we discuss about colors of things (objects). They are similar but different ideas which we need to distinguish carefully. For example, let's imagine a plant's green leaf. The plant's leaf is illuminated by some light coming from a certain light source. Then the plant's leaf scatters the light to our eyes. Therefore, the color of the plant's leaf depends on the color of the illuminating light and how the light is scattered by the plant's leaf. reflectance to our eyes is a scattered light. Because color is a feature of light, we cannot discuss color of the leaf unless considering light source which illuminates the leaf. The color or leaf is, in fact, discussed in relation to the color of light which is scattered by the leaf. Then something strange may happen: if the light is originally red, containing little light which stimulates M-cones (which gives response of green), the reflected light can be also red. 

plants' leaf "scatters" green light stronger than other lights (red and blue). 

simple: the response of our eyes' cones give signals of green in response to the lights' spectrum. 



some more about colors. Colors 
absorption
reflection
color of shadow

 The important lesson for us is:
- Light is not necessarily visible to human's eyes. There is a broan range of invisible light and they are also important for ecology.
- Color is a feature of visible light only. There is no color for invisible light.
- Nevertheless, the idea of monochromatic light can be applied to the invisible light, too. It simply means "ligh with a single wavelength".




## Three optics

When we talk about how light behaves, we usually use one of three different approaches: geometrical optics, wave optics, or quantum optics. In geometrical optics, we think of light as traveling in straight lines. In wave optics, we treat light as a wave that spreads out in space. In quantum optics, we treat light as a group of photons.

You might wonder why we need three different ways to describe the same thing. The reason is that it is related to the idea of "modeling," which is a key concept in physics. Natural phenomena are often too complex for us to describe perfectly, so we simplify them by focusing on the most important features and ignoring the rest.

For example, when we talk about a rainbow in the sky, we usually use geometrical optics. This approach assumes that light travels in straight lines and bends when it passes a boundary between air and water. We can calculate its angle using the well known value of "refractive index" of each wavelength of the light in the water. 

However, if we want to understand how the refractive index is determined, we need to use wave optics. Wave optics is based on something called the "Maxwell equations," which are the fundamental rules of electromagnetism. This theory uses two key properties: "permittivity" and "permeability," which describe electromagnetic feature of materials (like water in a rainbow). If you have enough math skills, you can work with the Maxwell equations and create "wave equations" that explain how light behaves as a wave. These wave equations show how the refractive index is related to permittivity and permeability.

You might then ask, "How are permittivity and permeability determined?" They are actually derived using quantum optics. Quantum optics explains how light interacts with tiny particles like a molecule, an atom, and an electron, each of which is known as a "quantum."

The three types of optics—geometrical, wave, and quantum—overlap, but they use different ways to describe light. In other words, they are different models of light. Geometrical optics is useful for tracing how light travels through space involving reflection, absorption, and transmission at the boundary or inside of big objects. However, it is not accurate if the light's wavelength is as large as the the objects (or the objects are as small as the wavelength of light). In those cases, we need wave optics, which is more complex because it involves tracking the light wave’s "phase" (we'll learn about that later).

The geometrical optics is essentially a kind of simplification and apptoximation of wave optics. Therefore, essentially, there are (not three but) two perspectives of light: electromagnetic wave and photon. 

The quantum optics is necessary if we deeply analyze the interaction of the light with materials involving the transition of energy and/or angular momentum, such as "thermal radiation", "Rayleigh scattering", "Mie scattering", "Raman scattering", "fluorescence", and so on.


## Generation of light
How does light happen? According to the wave optics, light happens when an electric charge moves with non-zero
acceleration. For example, if an electron is moving around a circle, it emits light. It is the principle of "synchrotron radiation". According to the quantum optics, a photon (the element of light in the quantum mechanics' perspective) happens when a system change its energy from a level to some lower level.


## Thermal radiation
In ecology, The most important process of light generation is perhaps "thermal radiation" (or "thermal emission"). It says, depending on its temperature, every object emits light. For example, because the sun is an object, it emits light depending on its temperaturre. It is the sunlight. 

You may know temperature of an object is an index of mean energy of particles which make up the object. Therefore, if an object is hot, the particles are in high-energy states. They may sometimes transit to lower states, yielding photons. It is a rough summary of the thermal radiation. You should know three formula about it. The first one is Planck's low. It is the most fundamental law of thermal radiation:

$B(\lambda, T) = \frac{2 h c^2}{\lambda^5} \frac{1}{\text{exp}\Bigl(\frac{h c}{\lambda k_B T}\Bigr) - 1}$

where:
$B(\lambda, T)$ is the spectral radiance (power per unit area per unit wavelength per unit solid angle) at wavelength $\lambda$ and temperature $T$; $h$ is Planck's constant ($6.626 \times 10^{-34}$ J$\cdot$s); $c$ is the speed of light in a vacuum ($3.00 \times 10^8$ m/s); $\lambda$ is the wavelength of the photon; $k_B$ is the Boltzmann constant ($1.381 \times 10^{-23}$ J/K); $T$ is the absolute temperature; $e$ is the base of the natural logarithm.
    
Because energy of the photon is inversely proportional to the wavelength, 


## Polarization

## Refraction

量子的なphotonとレイトレーシングのphotonは違う

## Flux

## PAR


