#Storyboardとxib
##Storyboard
* GUI でアプリの各ページの View や画面遷移 (Segue) を実装するもの。
* View のコンポーネント化は苦手で、View 全体の管理に適している。
* アプリUIを視覚的に表現できる機能  ラッグ&ドロップでのViewの配置やAutoLayoutの指定、背景や文字色・サイズの設定、画面遷移などの多くのことが行える
* UIViewController 間の関係を組むことが出来る。
* アプリの遷移を集約して書くことができ、処理の流れが理解しやすい

##xib
* XML Interface Builderの略で、GUI で各ページの View やコンポーネントを作るもの。部品の構造をXMLで記述したもの
* View の再利用に適している。
* Xib で作成した View のコンポーネントは Storyboard やコードから利用可能。
* UIViewで、単体では使用しない。
* UIを部品化して使い回したい場合、XIBファイルを使って実現することが多い。



Storyboard の場合では、UIStoryboard のメソッド instantiateViewController(withIdentifier:) 等で、Storyboard ファイル内のレイアウトを読み込んで UIViewController を生成する。
Xib の場合では、UIViewController のイニシャライザ init(nibName:bundle:) を使い、Nib ファイル内のレイアウトを読み込んで UIViewController を生成する。





##参照
https://techlife.cookpad.com/entry/2015/06/24/190546
https://culumn.hatenablog.com/entry/2018/12/07/230000
https://mo-gu-mo-gu.com/ios-storyboard-basic
https://qiita.com/os1ma/items/a8b946dba891f01ccc4e