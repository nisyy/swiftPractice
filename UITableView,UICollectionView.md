## UITableView
- どんなことが出来るか
　配列などで格納されたデータをリストとして画面に表示する。
 
- どういったものを作る際に使用するか
 - iphoneの設定画面
 - ニュースアプリ
 - メールアプリ

 
- 作り方について（どのような情報が必要？）
1. メインストーリーボードの設定
 1. 画面サイズの設定
 1. ViewControllerにTableView
 1. TableViewのレイアウトを設定
 1. TableViewのOutletsを設定
 1. TableViewにTableViewCellを追加
 1. TableViewCellのIdentifierを設定
2. コードに追加
 1. UITableViewDataSource」と「UITableViewDelegate」を追加
 1. リストの中身を定義
 1. セルの個数を指定するコードを追加
 1. セルの中身を表示するコードを追加  


 
 dataSource（データソース）とは、テーブルビューのデータソースとして機能するオブジェクト
 
 delegate（デリゲート）はTable VIewを使用する上で、リストの行数を返す、セクション数を返すなどのデリゲートメソッドをViewControllerにデリゲートする
 UITableViewの操作イベントをハンドリングするプロトコル
あるクラスは、他のクラスのインスタンスに、処理を任せることができる

## UICollectionView
- どんなことが出来るか
　複数ののアイテムをパネルのように一覧として表示する。
 
- どういったものを作る際に使用するか
 - フリマアプリ
 - インスタグラムのプロフィール
 - 映画アプリ

 
- 作り方について（どのような情報が必要？）
1. StoryboardにCollectionViewを配置する
 1. CollectionViewを設置する
 2. dataSouceとdelegateを設定する
 3. CollectionViweCellのIdentifierを設定する

2. CollectionViewのセクション数やセル数を設定する
  1. UICollectionViewDelegate, UICollectionViewDataSourceを追加する
  2. UINibファイル、UICollectionElementKindCellを設定する
  
3. UICollectionViewDelegateFlowLayoutを使用したレイアウト設定
 1. UICollectionViewDelegateFlowLayoutを追加する

##参照
* UITableView
https://www.sejuku.net/blog/36626  
https://qiita.com/pe-ta/items/cafa8e20029047993025
https://qiita.com/chanNaru/items/326bd50a78cf34371169

* UICollectionView
https://program-life.com/345  
