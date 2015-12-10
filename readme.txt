暮井 慧（プロ生ちゃん） for UE4
Version 2015/12/11

元データ：(c) 2011-2015 プログラミング生放送
改変者　：Kirurobo


■ このデータについて

このデータはプログラミング生放送の
「暮井 慧（プロ生ちゃん） MMD/Unity/FBX 公式データ」
バージョン 11 を元に、Unreal Engine 4.9.2 にインポート後
マテリアル調整等をおこなったものです。

オリジナルデータ（ニコニ立体）
http://3d.nicovideo.jp/works/td8608

利用ガイドライン
http://pronama.azurewebsites.net/pronama/guideline/


また、おまけで含まれる DrawLinePostProcess マテリアルの中身は
http://rarihoma.xvs.jp/2015/02/22/1/
を元にしたものです。



■ データ構成

Content
└Pronama-chan … メインである、スケルタルメッシュがあります
　├Animations … ちょっとだけサンプルで、まばたきとT-ポーズをとるアニメーションが入っています。
　├Materials … マテリアルをまとめたフォルダです。おまけでエッジ描画のPostProcessMaterialもあります。
　│├Standard … 標準ライティング用のマテリアルです
　│└Unlit … ライティング無効のマテリアルです
　├Skeleton … スケルトンがあります。
　└Textures … テクスチャがあります。スパッツ時のサブサーフェイスのテクスチャ以外は元データのものです。

Pronama-chan フォルダの中に、4種類のスケルタルメッシュがあります。
・Pronama-chan … 標準のもの
・Pronama-chan_s … スパッツ着用版
・Pronama-chan_unlit … ライティング無効版
・Pronama-chan_unlit_s … ライティング無効・スパッツ着用版



■ 利用方法

・UE4 にてプロジェクトを作成します。
・一度 UE4エディタは終了し、プロジェクトのフォルダにある Content の下に Pronama-chan フォルダを展開します。
　この際、サブフォルダを作ったりすると失敗します。
　必ず Content フォルダのすぐ下に Pronama-chan フォルダを配置して下さい。
・エディタを再度起動します。うまくいけばアセットを利用できます。

フォルダ構成を変更したい場合は、利用可能になった後でエディタ上にてフォルダ移動などを行ってください。



-----------------------------------------------------------
2015/12/11 Kirurobo
http://twitter.com/kirurobo