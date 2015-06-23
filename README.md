# Learning Haskell

2015年 Haskell 勉強会

## Teaching materials.

- 【日本語版】 [『すごいHaskellたのしく学ぼう!』](http://www.amazon.co.jp/dp/4274068854)
    - 【英語】オンラインで閲覧可能 [Learn You a Haskell for Great Good](http://learnyouahaskell.com/)

- 【課題】検討中 ⇒ [課題集](./exercises.md) のページを作りました
 
> :memo: 日本語版が英語よりも注釈が豊富なようなので日本語訳を使うことにする。
ただし、「用語」は適時英語版のものを補う（学習者が検索しやすくするため）。

## Progress

- （終了）第1回 2015/1/21(水) : v～viii, P1 ～ P15
    - v イントロダクション ( [Introduction](http://learnyouahaskell.com/introduction) )
    - :
    - 1.4 レンジでチン！( [Texas Rangers](http://learnyouahaskell.com/starting-out#texas-ranges)  )
- （終了）第2回 2015/1/27(火) : P15 ～ P28 
    - 1.5 リスト内包表記 ( [I'm a list comprehension](http://learnyouahaskell.com/starting-out#im-a-list-comprehension) )
    - :
    - 2 型を信じろ ( [Types and Typeclasses - Believe the type](http://learnyouahaskell.com/types-and-typeclasses#believe-the-type) )
    - :
    - 2.4 型クラス 初級講座( Eq 型クラス まで) ( [Typeclasses 101](http://learnyouahaskell.com/types-and-typeclasses#typeclasses-101) )
- （終了）第3回 2015/2/3(火) : P29 ～ P39
    - 3.1 リストのパターンマッチとリスト内容 tell から ( [Syntax in Functions](http://learnyouahaskell.com/syntax-in-functions#pattern-matching) )
- （終了）第4回 2015/2/10(火) : P39 ～ P51 
    - : 
    - 3.5 関数の構文 case 式 ( [Case Expression](http://learnyouahaskell.com/syntax-in-functions#case-expressions) )
- （終了）第5回 2015/2/17(火) : P51 ～ 第4章 Hello 再帰!  ( [Recursion](http://learnyouahaskell.com/recursion) )
    - 【提案】 課題がないので、[「関数プログラミング入門」](http://www.amazon.co.jp/dp/427406896X/) を使うのがよいかもしれない
    - P59 再帰的に考える
    - 【課題】フィボナッチ数列を再帰で書く 
-  (終了) 第5回 2015/3/3(火) : P61 ～ P75 第5章 高階関数 ( [High Order Function](http://learnyouahaskell.com/higher-order-functions) )
    - (会場の都合により 2/24 から 3/3 へ延期になりました)
    - :
    - 5.4 ラムダ式 ( [Lambdas](http://learnyouahaskell.com/higher-order-functions#lambdas) )
-  (終了) 第6回 2015/3/10 : P75～P85 畳み込み、見込みアリ！ ( [Only folds and horses](http://learnyouahaskell.com/higher-order-functions#folds) )
    - : 
    - 5.7 関数合成 ( [Higher Order Functions - Function composition](http://learnyouahaskell.com/higher-order-functions#composition) )
    - 【課題】 サンプルのコードを自前で、foldを使い実装してみる (reverse' , product' , filter' , last')
-  (終了) 第7回 2015/3/17 : P85～P100 5.7 関数合成 多引数関数の関数合成 ( [Function composition](http://learnyouahaskell.com/higher-order-functions#composition) )
    -  :  
    - 6.2 標準モジュールの関数で問題を解く ( [Modules](http://learnyouahaskell.com/modules) )
-  (終了) 第8回 2015/3/24 : P95～P102 6.3 キーから値へのマッピング ( [Data.map](http://learnyouahaskell.com/modules#data-map) )
    - （前回の復習を兼ねて）
-  (終了) 第9回 2015/4/7 : P102～110 Data.Map - 6.3 キーから値へのマッピング ( [Data.map](http://learnyouahaskell.com/modules#data-map) )
    - :
    - [7.Module - Making our own modules](http://learnyouahaskell.com/modules#making-our-own-modules)
-  (終了) 第10回 2015/4/14 : P111～ 第7章 型や型クラスを自分で作ろう ( [Making Our Own Types and Typeclasses](http://learnyouahaskell.com/making-our-own-types-and-typeclasses) )

-  (終了) 第11回 2015/4/21 : P117～127 7.3 レコード構文 ( [Record syntax](http://learnyouahaskell.com/making-our-own-types-and-typeclasses#record-syntax) )
    -  :
    - 7.5 インスタンスの自動導出 [Derived instances](http://learnyouahaskell.com/making-our-own-types-and-typeclasses#derived-instances)
-  (終了) 第12回 2015/4/28 : P127～P134 7.5 インスタンスの自動導出 [Derived instances](http://learnyouahaskell.com/making-our-own-types-and-typeclasses#derived-instances)
    - :   
    - 7.6 型シノニム [Type synonyms](http://learnyouahaskell.com/making-our-own-types-and-typeclasses#type-synonyms)
-  (終了) 第13回 <s>2015/5/12</s> 2015/5/19  : P134-P143 - 7.6 型シノニム [Type synonyms](http://learnyouahaskell.com/making-our-own-types-and-typeclasses#type-synonyms)
    -  (5/19 日に延期になりました)
    -   :
    - 7.8 型クラス ( [Typeclasses 102](http://learnyouahaskell.com/making-our-own-types-and-typeclasses#typeclasses-102) )
-  (終了) 第14回 2015/5/26  : P143-P152 7.8 型クラス 中級講座 ( [Typeclasses 102](http://learnyouahaskell.com/making-our-own-types-and-typeclasses#typeclasses-102) )
    - :
    - 7.10 Functor 型クラス 「Maybe は Functor だよ、たぶん」まで ( [The Functor typeclass](http://learnyouahaskell.com/making-our-own-types-and-typeclasses#the-functor-typeclass) )
-  (終了) 第15回 2015/6/2 : P152-157 7.10 Functor 型クラス ( [The Functor typeclass](http://learnyouahaskell.com/making-our-own-types-and-typeclasses#the-functor-typeclass) )
- (終了) 第16回 2015/6/9 : P159-174 8 入出力 ( [Input and Output - Learn You a Haskell for Great Good!](http://learnyouahaskell.com/input-and-output#hello-world) )
    - 次回は二週間後です。
- (終了) 第17回 2015/6/23 : P175-186 第9章 もっと入力、もっと出力 ( [Input and Output - Learn You a Haskell for Great Good!](http://learnyouahaskell.com/input-and-output#files-and-streams) )
    - 9.2 ファイルの読み書き
- (予定) 第18回 2015/6/30 : P186-202(目安) 9.3 ToDOリスト ( [ToDo リスト - Learn You a Haskell for Great Good!](http://learnyouahaskell.com/input-and-output#files-and-streams) )

