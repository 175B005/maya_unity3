# maya_unity3
maya unity 連携機能３（アニメーション　リグ・キャラクタアニメーション編）

 1. 前回の復習。アニメーションを簡単につけるやり方と、Ｕｎｉｔｙに持っていく方法をやりました。  
今回はその続きになります。リグをつけて、ささっと人間を動かしていきましょう。
 1. はじめにunityとmayaをコラボ状態で起動しておきます。（[一回目ページ1..9](https://github.com/175B005/maya_unity)）
 1. モデルがない人のために、ここではunity assetを使っていきます。（Unityちゃんモデル）
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/direction.jpg)![](https://raw.githubusercontent.com/175B005/maya_unity3/master/direction3.jpg)
 1. unity でアセットをインポートします。（インポートするのはモデルのみでおｋ）  
 1. モデルデータをシーンに出していきます。
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/direction1.jpg)
 1. 右クリック< Convret.. より、編集用のフォルダ（前回ページ参照）にパッケージ化します。
 1. maya側に行き、unityメニューのimportを選択。今のパッケージしたモデルを読み込む。
 1. maya上にunityちゃんがきたら、初期設定完了です。
---

###ここから本番（うにちゃｎがぞ）

 1. 左上メニューバーの「モデリング」を「リギング」に変更（ショートカットが使いやすい）  
色がついていない！と思った方は、上部メニューのサッカーボールマークをONにすると、色が反映されます。  
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/direction2.jpg)
 1. モデルを全選択。→　上部メニューの「スケルトン」<下の「クイックリグ」を選択して、  
出てきたメニューの「自動リグ」を選択。  
すると、あら不思議、勝手にモデルにリグが付きます  
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/direction4.jpg)
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/direction5.jpg)
※エラーの場合の対処法→リンク
 1. ですが、モデルによってはこのUnityちゃんのように、髪の毛が多いキャラが  
いるので、それまで、勝手に認識して、リグを入れてしまいます。
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/direction7.jpg)
 1. なので、少しだけ調節してしきたいと思います。
 1. まず、このコントロールリグは要らないので、上書きで、ガイドを作ります。  
クイックリグ< 段階的に< ガイド< ガイドを作成
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/directionx1.jpg)
 1. このガイドは骨を入れる関節部分のガイドということなので、  
これがしっかりしていないと、リグが入りません。位置を調整して、しっかりとモデルの関節の位置にしましょう。  
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/directionx2.jpg)  
 1. 片方を調節してしまえば、反転させることもできますよ。
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/directionx3.jpg)
 1. 次はスケルトンとコントロールリグをつけます。  
段階的に< スケルトンとリグの作成<▼のどっちも作るを選択< 作成  
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/directionx4.jpg)
 1. ..さっきとほぼ同じのがでてきました。先ほどの「自動リグ」というのは、  
 - このガイド、スケルトン、スキニングを全部やってくれる、ワンクリック機能だったのです。  
      - ガイド：キャラクターの関節位置を表すガイド。後の動きなどには一切関係しなくなる。後で消してもおｋ.  
      - スケルトン：骨。リグ。この形状によって、扱いやすいHumanoidや、Genericなどが存在する。(unityでのAvatarになる)    
      - スキニング：リグとモデルを選択し行う。モデルとリグを紐付けし、リグを動かすことで、モデルを同時に動かす。    

### では、アニメーションをつけていきたいと思います。

1. まず先の手順で、スキニングがエラーなく終わっていれば、  
コントロールリグを動かすと、モデルが動いていることがわかります。  
![](https://raw.githubusercontent.com/175B005/maya_unity3/master/directionx5.jpg)
1. 
1. 
1. 
1. 
1. 

 [前ページ](https://github.com/175B005/maya_unity2)| [次ページ](https://github.com/175B005/maya_unity4)|[目次](https://github.com/175B005/maya_unity_index)
