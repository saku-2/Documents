# WPF
## 作業
https://elf-mission.net/programming/wpf/getting-started-2020/step09/

https://qiita.com/okazuki/items/7572f46848d0e93516b1

- DataContext(公式チュートリアル）
  https://docs.microsoft.com/ja-jp/dotnet/desktop/wpf/get-started/create-app-visual-studio?view=netdesktop-5.0
  
  https://docs.microsoft.com/ja-jp/samples/browse/?redirectedfrom=MSDN-samples&terms=wpf
  
## List系 - Tab
https://kan-kikuchi.hatenablog.com/entry/ReactiveCollection_ReactiveDictionary

https://qiita.com/okazuki/items/7572f46848d0e93516b1

例）
C:\Documents\C#\Official_Prism-Samples-Wpf-master\12-UsingCompositeCommands

- ラジオボタン        https://araramistudio.jimdo.com/2016/12/27/wpf%E3%81%A7radiobutton%E3%81%AEischecked%E3%81%AB%E5%88%97%E6%8C%99%E5%9E%8B%E3%82%92%E3%83%90%E3%82%A4%E3%83%B3%E3%83%89%E3%81%99%E3%82%8B/

  http://keenag.hatenablog.com/entry/2017/10/08/230227
  
- ListBoxの見た目をラジオボタンにする（複数選択できない）
  http://once-and-only.com/programing/c/radiobutton%E3%81%ABcollection%E3%82%92%E6%B8%A1%E3%81%97%E3%81%9F%E3%81%84%EF%BC%88c-wpf%EF%BC%89/

## 作業前メモ
- 画面遷移
- https://ameblo.jp/tashiro189/entry-12602862511.html

- 公式チュートリアル
- https://docs.microsoft.com/ja-jp/dotnet/desktop/wpf/get-started/create-app-visual-studio?view=netdesktop-5.0

- 画面内で、動的な値を渡す
- https://garafu.blogspot.com/2014/09/wpf_22.html

- ICommandクラス
- http://marikooota.hatenablog.com/entry/2017/05/30/234258
- https://blog.okazuki.jp/entry/2014/10/29/221029

- https://www.atmarkit.co.jp/ait/articles/1011/09/news102_2.html
- https://elf-mission.net/programming/wpf/episode06/

- CommandParameter
- xamlに定義したButtonのCommandParameterをイベントハンドラで受け取る
- https://qiita.com/aiya000/items/1cf31699bf8122e76bd7

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

- MVVMをリアクティブプログラミングで快適にReactivePropertyオーバービュー - かずきのBlog@hatena
- https://blog.okazuki.jp/entry/2015/12/05/221154
- INotifyPropertyChanged実装のありえない面倒くささと、ReactivePropertyの信じられない素晴らしさ - Qiita
- https://qiita.com/ledsun/items/6f4ef754e5ae2507e531
- ReactiveCommand で Subscribe しようとして謎のエラーに悩まされていた話
- https://blog.kazuakix.jp/entry/2015/06/28/233439
- PrismとReactivePropertyで簡単MVVM！
- https://qiita.com/hiki_neet_p/items/e381c687b0644c0e4978
- 【雑記】イベントの購読とその解除 - C# によるプログラミング入門 _ ++C++; // 未確認飛行 C
- https://ufcpp.net/study/csharp/MiscEventSubscribe.html
- こわくないReactive Extensions超入門 - Qiita
- https://qiita.com/acple@github/items/6cfee916f09632037a6e
- C#の主要インターフェース解説：IObservable、IObserver - がりらぼ
- 
- 【WPF】ViewModelがINotifyPropertyChangedを実装していないとメモリリークする件 - aridai.NET
- https://aridai.net/articles/?p=15
- MVVMでメモリリークしちゃってました 原因と対策編 - かずきのBlog@hatena
- https://blog.okazuki.jp/entry/20110227/1298817065
- [WPF] コントロールの任意のイベントとコマンド xaml上で関連付ける - Netplanetes
- http://www.pine4.net/Memo/Article/Archives/417
- ReactivePropertyの後始末 - かずきのBlog@hatena
- https://blog.okazuki.jp/entry/2016/04/30/073755




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
   
   
## おまけ(UI編）
- WPF Themes 
  https://archive.codeplex.com/?p=wpfthemes
  
- 自由度の高いUI
  http://grabacr.net/archives/1240
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








