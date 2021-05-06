# WPF
## Other
- 「完全コンストラクタパターン」

## Prism
- MVVMするライブラリです。
- コードビハインド⇒VM呼出 => Command使うこと

##「ReactiveProperty」
- 変更通知ができるデータバインド(コード量少ない）
- ReactivePropertyクラス
- ReactiveCommandクラス
- ReactiveCollectionクラス
- ReadOnlyReactiveCollectionクラス
- INotifyPropertyChanged/INotifyCollectionChangedをIObservableに変換するメソッド群
- その他Reactive ExtensionsにないちょっとしたIObservableファクトリメソッド
- 通知系のNotifier系クラス
- IFilteredReadOnlyObservableCollectionインターフェース

## DOC
- https://elf-mission.net/programming/wpf/getting-started-2020/step10

## かずき先生
- 【 ReactiveProperty 】
- 「イベント引数を加工するような仕組み (ReactiveProperty)」
- https://blog.okazuki.jp/entry/2019/04/19/172010
- 目次
- https://blog.okazuki.jp/archive/category/ReactiveProperty
- マスト？
- https://blog.okazuki.jp/entry/2015/02/22/212827
- BooleanNotifierクラスは、IObservable<bool>として扱うことのできる、bool型の値を切り替える機能を持ったクラスです.
- ReactiveTimerは停止と再開が可能なTimerクラスです。
- 全ての最後の値がTrueの時にTrueを流すCombineLatestValuesAreAllTrueメソッドと、その逆のCombineLatestValuesAreAllFalseメソッドがあります。このメソッドは、複数のバリデーションの結果がすべてTrueだった場合に有効にするCommandを作ったりする際にとても有用です。
- Json.NETを使ってJSON形式でシリアライズ、デシリアライズ可能です。ViewModelの値を一時的に保管するケースではJson.NETを使ってください。
- https://blog.okazuki.jp/entry/2015/12/05/221154
- まとめ(3個）
- https://qiita.com/okazuki/items/7572f46848d0e93516b1

- 便利♪
- https://nprogram.hatenablog.com/entry/2018/02/07/200905

- 初心者♪
- http://tmori3y2.hatenablog.com/entry/2016/01/25/220928
- ViewModelが大きくなる。。。
- 結論：「ModelもReactivePropertyで実装したら良い。」
- 下の方に、いろんな検証へのリンクあり。
- 初心者が迷ったReactivePropertyを使用した数値型のModel
- 初心者が迷ったReactiveCollectionとDataGridのエラーと変更フラグの集計など

- 【C#】ReactiveProperty全然分からねぇ！って人向けのFAQ集【修正済】 - Qiita
- https://qiita.com/YSRKEN/items/5a36fb8071104a989fb8
- リンク多数掲載

## Livetの開発者の尾上大先生
- MVVMのModelにまつわる誤解
- http://ugaya40.hateblo.jp/entry/model-mistake
GUIアーキテクチャパターンの基礎からMVVMパターンへ (スライド)
スライド17
スライド31
スライド43
スライド53
スライド55
スライド58-62
スライド63-68
スライド77-79 (2016/01/30追記)
スライド81-85
本文
コメントの応答
自分の躓いた部分をすっきりさせてくれたのは、この辺かな？

## コードスニペット入力
- 「Prism Template Packをインストール」+ (スニペットの設定)
   propp" + Tab
   ct + Tab + Tab
- 「ReactivePropertyのスニペットの設定」
   rprop" + Tab
   rcommg" + Tab
   
   

- 
- 
- 
- 
- 
- 
- 
- 
- 
- 
- 
- 
- 








