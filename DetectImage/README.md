## [前のセッションへ](../DetectHPlane)


## DetectImage
### 概要
画像を認識し、3D文字を配置する。
### 作成手順  

1. Xcodeで新規プロジェクトを作成し、「Augmented Reality App」を選択する。  
<img src="images/detect_image_select_ar.png" width="480"/>   

2. 任意のプロジェクト名(ここでは「DetectImage」)、Languageは「Swift」、Content Technologyは「SceneKit」を選択する。  
SceneKit：簡単に3Dゲームを作ることができるフレームワーク  
<img src="images/detect_image_select_swift_scene_kit.png" width="480"/>  

3. 認識対象の画像を追加する。  
Assets.xcassetsを選択し、右クリック（2本指でトラックパッドをタップ）から「New AR Resource Group」を選ぶ。
<img src="images/detect_image_add_resource_group.png" width="480"/>   
画像をドラッグ＆ドロップで追加し、 マーカーのサイズを指定する。 
<img src="https://user-images.githubusercontent.com/23329399/53215625-d51cb980-3694-11e9-9ad0-b73ae0fc6410.png" width="480"/>   

**<a href="https://user-images.githubusercontent.com/23329399/53215533-76574000-3694-11e9-85fe-36ba695ea0ad.png" download="Cello.png">今回はこちらの画像を使用してみましょう</a>**

4. 飛行機を削除し、画像を認識し指定する処理を追加する。  
[変更内容](https://github.com/KantaiMishima/ARKit/commit/518822df211222c2846de0c66a99ced85e8a8124)

5. 画像検出時に3D文字を配置する処理を追加する。  
[変更内容](https://github.com/KantaiMishima/ARKit/commit/f68d684e7040f3821d5d5824ff39fefa1ea57ceb)

6. XCode上でビルドし実行すると、認識した画像に文字が表示される。  
<img src="https://user-images.githubusercontent.com/23329399/53215965-50329f80-3696-11e9-84de-567e70d4f97d.jpeg" width="240"/>   

### [今回のソースコード](https://raw.githubusercontent.com/KantaiMishima/ARKit/master/DetectImage/DetectImage/ViewController.swift)

## [indexへ戻る](../../../)
