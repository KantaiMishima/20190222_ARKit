# ARKit

AppleのAR(Augmented Reality) のアプリ作成用フレームワーク。  
VIO(Visual-Inertial Odometry)：カメラやセンサから環境マッピング、自己位置推定を行う。  
<a href="https://developer.apple.com/jp/arkit/" target="_blank">AppleのARKitサイト</a>

- ARKit 1.0：水平面の認識
- ARKit 1.5：垂直面、画像の認識
- ARKit 2.0：AR空間の永続化、ARの共有、3Dオブジェクトの検出、画像トラッキング

動作環境：iOS11以降のA9プロセッサ以上のプロセッサを搭載したiPhone/iPad  
ここではARKit2.0を対象とし、iOS12以上のiPhone/iPad、Xcode10.0以上を搭載したMacを使用。

# デモ集
## [DetectHPlane](./DetectHPlane)
水平面を認識し、球を配置する。

## [DetectImage](./DetectImage)
画像を認識し、3D文字を配置する。

## [MLKit-ARKit(Firebaseブログへのリンク)](https://firebase.googleblog.com/2018/12/see-how-ml-kit-and-arkit-play-together.html)
Firebaseブログで紹介されている機械学習モジュール(MLKit)とARKitを組み合わせたプロジェクト。  
タップした位置の画像認識結果が3D文字で配置される。  
Firebase：Google提供のモバイルアプリ開発プラットフォーム。

## [BallToWall](./BallToWall)
垂直面を認識し、タップした位置から物理演算により球を投げる。

## [SceneKit公式ドキュメント](https://developer.apple.com/documentation/scenekit)

## [ARKit公式ドキュメント](https://developer.apple.com/jp/documentation/arkit/)

## [インターネット上のdemo](https://github.com/kboy-silvergym/ARKit-Emperor)
