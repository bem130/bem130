# <ruby>蓓眸<rt>べむ</rt></ruby> (Bem130)

作りたくなったものを衝動的に作る人です。

自作プログラミング言語、処理系、マークアップ言語、論理回路のDSL、ブラウザで動くツール、タイピング・暗記ソフト、学習可視化ツール、3Dまわりの実験、入力デバイスなどを作っています。

個人寄りの制作物は [bem130](https://github.com/bem130) に、少し大きめの実験的なプロジェクト群は [Neknaj](https://github.com/neknaj) に置いています。  
[Neknaj](https://neknaj.com) は、私とその仲間たちのプロジェクト群の名前です。

## 主なプロジェクト

### [NEPLg2](https://github.com/neknaj/NEPLg2)
前置記法・式指向・オフサイドルールを中核にした自作言語です。  
WebAssembly / WASI を主要ターゲットにしていて、Playground とチュートリアルも整備しています。

- Playground: https://neknaj.github.io/NEPLg2/
- Tutorial: https://neknaj.github.io/NEPLg2/tutorials/getting_started/00_index.html

### [prefix-lang-compiler-book](https://github.com/bem130/prefix-lang-compiler-book)
前置記法の小さな言語を題材に、TypeScript で言語を作りながら学ぶための本です。  
Compiler / Runtime / CLI / Web エディタまで、自分で組み立てながら理解することを目標にしています。

### [Neknaj Circuit Game](https://github.com/neknaj/circuitgame)
論理回路をテキストで設計・検証するための DSL と処理系です。  
CLI と Web の両方で扱えるように作っていて、論理回路・記法設計・実装の交点にあるプロジェクトです。

- Web: https://neknaj.com/circuitgame/README
- Playground: https://neknaj.github.io/circuitgame/web/index.html
- Tutorial: https://neknaj.github.io/circuitgame/tutorials/index.html

### [NDDS / NML](https://github.com/neknaj/ndds)
自作マークアップ言語 NML と、それをブラウザで表示するための仕組みです。  
インデントベースの記法、JavaScript 関数呼び出しによる部品化、プレイグラウンド、VSCode まわりまで含めて作っています。  
自分のサイトのかなりの部分もこれで書いています。

- Web: https://neknaj.com/ndds/README
- Playground: https://neknaj.github.io/ndds/playground.html

## 作っているものの系統

### 1. 言語と処理系
- [NEPLg2](https://github.com/neknaj/NEPLg2)
- NEPLg1
- NLPS
- njplang
- [prefix-lang-compiler-book](https://github.com/bem130/prefix-lang-compiler-book)

自作言語を作ることと、その周辺の処理系・記法・実行環境を設計することを継続してやっています。

### 2. 文書記法とブラウザ上の表現
- [NDDS](https://github.com/neknaj/ndds)
- markup
- custommd

文書をどう書くか、どうレンダリングするか、どう部品化するかに強い関心があります。  
マークアップ言語そのものや、ブラウザでの表示系を作っています。

### 3. 論理回路と DSL
- [Neknaj Circuit Game](https://github.com/neknaj/circuitgame)
- cpu-circuitgame
- circuitgame_tutorial

論理回路をテキストで書いて扱うための DSL や、その処理系、周辺ツールを作っています。

### 4. タイピング・暗記・学習
- [Typing Web](https://github.com/neknaj/typingweb)
- GeoQuiz
- [PeriodicTableMemorizer](https://github.com/neknaj/PeriodicTableMemorizer)
- typingmp
- typing
- [chemquiz](https://github.com/bem130/chemquiz)

タイピングを単なる速度練習ではなく、暗記や学習のためのインターフェースとして使うことに興味があります。

### 5. 学習記録と可視化
- [Common Test Score Tracker](https://github.com/bem130/commontestscoretracker)
- [Study Time](https://bem130.com/studytime/README)
- Study Time Dashboard

勉強時間や模試データの記録・集計・可視化のためのツールも作っています。

### 6. ブラウザで動く実験ツール
- [Real-time Audio Analyzer](https://bem130.com/audioanalyzer/app.nml.php)
- Convolution
- springsimu
- JSON Viewer
- visualBinary

ウェブブラウザでそのまま動く、小さめの実験ツールや可視化ツールをよく作ります。

### 7. 3D・入出力・ハードウェア
- Neknaj 3D Library
- 3DTree / 3DTreeWeb
- maze
- virtualworld
- nvg
- [MorseBLEkeyboard](https://github.com/bem130/MorseBLEkeyboard)
- Bem配列

3D 描画、入力方式、キーボード配列、物理デバイスなど、ソフトウェアの外側にある入出力にも興味があります。

### 8. 開発基盤・テンプレート・道具
- [tsrust](https://github.com/neknaj/tsrust)
- [kp](https://github.com/bem130/kp)

開発を進めやすくするためのテンプレートや CLI ツールも作っています。

## 制作方針

- 作りたくなったものを作る
- できる限り自分で実装する
- 自由度の高いソフトを目指す
- 作品は基本的にフリーライセンスで公開する

## リンク

- 個人サイト: https://bem130.com
- Neknaj: https://neknaj.com
- GitHub (bem130): https://github.com/bem130
- GitHub (Neknaj): https://github.com/neknaj
