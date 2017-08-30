# CSSレイアウトを特徴で使い分ける
## Grid Layout, Flexbox, Floatの特徴
**Grid Layout, Flexbox, Float**はそれぞれCSSにおいてレイアウトを設定上で必要なプロパティとなっている。一昔前まではFloatだけでレイアウトを設定していたが、現在はより効率的にレイアウトを設定できるようにFlexboxやGrid Layoutが注目されている。それらの特徴をおさえて効率的にレイアウトを設定できる備忘録としていく。また新しくレイアウトの仕様が変わる毎にリライトしていく。

1. Grid Layout  
- 要素の順番やフローは無関係に、要素の配置される位置を指定できる  
- 整列された行や列に要素を配置できる  
- ヘッダー、コンテンツ、フッターのように画面を分割するようなレイアウトに向いている

2. Flexbox  
- 要素を整列させるのに向いている
- 要素を横並びに整列する際に余白を均等に揃えたり、整列する方向や順番も指定できる
- 要素の整列において少量のコードで様々なレイアウトを実現できる

3. Float  
- 指定された要素をleftやrightで左右に浮かせることができるため、要素の周りにテキストなどを回り込ませるようなレイアウトが実現できる


## それぞれが向いているレイアウトについて  
1. Grid Layout  
  <p><img src="img/grid-layout.png" width="500px"></p><br>
  Grid Layoutは画面全体を分割したようにレイアウトや、タイルレイアウトを組むのに適している

2. Flexbox  
- flex-start
  <p><img src="img/flex1.png" width="200px"></p><br>
- space-between
  <p><img src="img/flex2.png" width="200px"></p><br>
- center
  <p><img src="img/flex3.png" width="200px"></p><br>
- space-around
  <p><img src="img/flex4.png" width="200px"></p><br>
  Floatやその他のCSSプロパティだと面倒な等間隔の横並びや上下左右の中央寄せもFlexboxなら簡単に実現できる

3. Float
- float: left  
  <p><img src="img/float1.png" width="200px"></p>
- float: right
  <p><img src="img/float-right.png" width="200px"></p>
  記事でよく見るように画像の周りに文字が回り込むようなレイアウトが実現できる
