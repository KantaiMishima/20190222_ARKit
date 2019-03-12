## DetectHPlane
### 概要
水平面を認識し、球を配置する。

### 前準備

持ってきたiPhoneをそれぞれの机のPCに繋げる。

iPhoneやPCから信頼するか聞かれるので信頼するように設定する。


### 作成手順  

1. Xcodeで新規プロジェクトを作成し、「Augmented Reality App」を選択。  
<img src="images/detect_hplane_select_ar.png" width="480"/>   

2. 以下の内容を入力。
SceneKit：簡単に3Dゲームを作ることができるフレームワーク。  

|項目|入力内容|
| -- | -- |
|Project Name|任意のプロジェクト名(ここでは「DetectHPlane」)|
|Team|任意のアカウント(ここが「none」になっていないか確認)|
|Organization Name|任意のチーム名(ここでは「HIT」+A~Cのアルファベット)|
|Organization Id|任意のチームID(ここでは「HIT」+A~Cのアルファベット)|
|Language|Swift|
|Content Technology|SceneKit|

<img src="images/detect_hplane_select_swift_scene_kit.png" width="480"/>  

3. 一旦、実行してみる。iPhone/iPadを接続し、実行ボタンを押下。  
<img src="images/detect_hplane_initial_run.png" width="480"/>  

   実行してみると「キーチェーン」ログインの許可をもらうのでパスワードを入力し、「常に許可」を押す。
   
   <img width="438" alt="2019-02-20 20 03 22" src="https://user-images.githubusercontent.com/23329399/53210375-e8be2500-3680-11e9-8f5b-d727396dd45d.png">

   ここで「信頼されていないデベロッパです」と怒られるので[こちら](https://code-schools.com/xcode-error-2/)を参考に対応。
   
   <img src="https://user-images.githubusercontent.com/23329399/53166650-4454c800-3619-11e9-8704-1f6ea35484cb.PNG" width="150px"><img src="https://user-images.githubusercontent.com/23329399/53167337-fe98ff00-361a-11e9-806c-1d800a871f24.PNG" width="150px"><img src="https://user-images.githubusercontent.com/23329399/53167374-140e2900-361b-11e9-8a3e-0ffa0ea9b934.PNG" width="150px"><img src="https://user-images.githubusercontent.com/23329399/53167379-183a4680-361b-11e9-9be5-3a5367eb8991.PNG" width="150px">
   
カメラスルーが表示される。(飛行機が表示されることもある)  
<img src="https://user-images.githubusercontent.com/23329399/53167139-7286d780-361a-11e9-9e4e-d17b771a4363.PNG" width="200"/>  

4. 飛行機を削除し、水平面認識指定を追加。  
<a href="https://github.com/KantaiMishima/ARKit/commit/fa1a59d1e687bc44aa84e66d01cad7b124b076be" target="_blank">変更内容</a>

5. 水平面検出時に球を配置する処理を追加。  
<a href="https://github.com/KantaiMishima/ARKit/commit/91311e4717aafdb1600b29b091b1e3f11121b920" target="_blank">変更内容</a>

6. XCode上でビルドし、実行。
<img src="https://user-images.githubusercontent.com/23329399/53167203-9e09c200-361a-11e9-924f-007df3f06889.PNG" width="200"/>  

### [今回のソースコード](https://raw.githubusercontent.com/KantaiMishima/ARKit/91311e4717aafdb1600b29b091b1e3f11121b920/DetectHPlane/DetectHPlane/ViewController.swift)


## [次のセッションへ](../DetectImage)
