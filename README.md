# AR.js（バージョン2.0）で可能になったGPSデータを使った「ロケーションベースAR」を紹介
Location Bassed AR test
After launching of Ar.js ver.2, it is possible to use GPS data from mobile phones for addressing AR contents.
So this is to test the function.

[オフィシャルの説明AR.js(github)]( https://github.com/jeromeetienne/AR.js/blob/location-based/aframe/README.md#location-based)

[このプロジェクトの中心人物がstep by stepで説明しているのがこちら](Build your Location-Based Augmented Reality Web App　https://medium.com/chialab-open-source/build-your-location-based-augmented-reality-web-app-c2442e716564)

基本的にこのチュートリアルに従えばできるはず。使える方法は、
1. HTMLオンリー　ただし<a-scene>にGPS座標を直接記入するので、地点の登録は１か所のはず（？）
2. JavaScriptも利用　複数地点を登録できる
3. JSとFourSquareのAPIを利用　有名なスポットは自動的に入る。ただし地点ごとの表示・非表示はできない？

エンジニアでもなんでもない私は、この３パターンのうち１どまり。

ただ、AR.jsのロケーションベースについて、Googleした限りでは日本語情報がなかったので、取り急ぎアップした次第。
