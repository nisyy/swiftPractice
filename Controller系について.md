#Controller系について
1.UIViewController
* インターフェースを管理し、アプリのコンテンツ内のナビゲーションを容易にする。
* 自身のviewプロパティを親として、必要であればsubviewを管理する。また同時に、その画面で必要なリソース（例えばMVCのModel）も管理する。他のViewControllerと連携しながらアプリケーションを構築する。
* メモリ管理を担っている。

2.NavigationViewController
* 複数あるViewControllerを階層的に管理し、画面間を簡単に行き来(ナビゲーション)することができるコントローラ。 前の画面に戻ることができるボタンを自動配置し、タイトルも設定することできる。
プッシュ遷移: 横にスライド
モーダル遷移: 下から出てくる

3.TabbarViewController
* 並列的な画面遷移を管理する。




参照
https://qiita.com/am10/items/191a103053f118dcb1ec
https://qiita.com/edo_m18/items/189acd18f1ecc368b5b0
https://developer.apple.com/documentation/uikit/view_controllers
https://swift-ios.keicode.com/ios/how-to-use-navigationcontroller-1.php
https://ticklecode.com/uiviewcontrollerlifecycle/