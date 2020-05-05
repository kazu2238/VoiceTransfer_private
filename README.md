
Discord 上で人狼ゲームを行うための GM bot です．

主にボイス人狼(ボイスチャットを用いた人狼) を想定した bot です．  
しかしボイスチャンネルを使わずにテキストチャンネルのみの使用，または ボイスチャンネルをBGMや効果音を聞く専用とし，マイクミュートで使用しても楽しめます．

詳しくは [wikiページ](../../wiki/) を御覧ください．

[インストール方法](../../wiki/インストール方法)

[ゲームの進行](../../wiki/ゲームの進行)

[役職](../../wiki/役職)

[コマンド一覧](../../wiki/コマンド一覧)

# 概要

Discord 上で人狼ゲームを行うための GM bot です．ゲームの進行を bot が完全に行ってくれるため進行役ユーザーを必要としません．  
また，ゲーム中は閲覧権限・書き込み権限等の権限切り替えも bot が完全に行うため，「狼以外は狼チャットは見ないでね！」と言った紳士協定も必要ありません．  

ゲーム中に処刑され，霊界へ行っても霊界にいる人同士でのボイスチャットができ，また生存者の会話は霊界にも流れるため，生存者の考察を霊界でガヤを入れることも出来ます．（生存者は霊界チャット・ボイスは見れません）  

また，ボイスチャットには各フェーズごとに BGM も流れているため，雰囲気を楽しむことも出来ます．ボイス人狼でなくても BGM を聞く為だけに マイクミュートでチャット人狼しても良いでしょう．

![](../../wiki/img/desc/make_room2.jpg)

![](../../wiki/img/desc/fin1.jpg)



また，今システムでは「ブラウザモニター」が実装されています．  
ゲーム内のコマンドを使用することで「カミングアウト」などができるのですが，
- 現在のフェーズ
- 残り時間
- カミングアウト・白/黒出しの整理
- 誰が今喋っているのか（緑枠の人）
- 誰が処刑・噛まれたのか（処刑は十字架，噛みは遺影）
などゲームの進行状況を分かりやすくまとめて表示してくれます．
![](../../wiki/img/desc/browser.jpg)

この図は，以下のコール宣言の直後の状態に対応しています．
![](../../wiki/img/desc/call_co2.jpg)

コール・カミングアウト した順番・時間なども整理して表示されるため，「今誰が言った？」「CO遅くなかった？」「ほぼ同時だった」「把握遅くない？」論争などのあまり本質ではない議論(諸説あり)が一掃できます．（この機能をあえて使わないで進行することももちろん出来ますし，「2秒遅かったが狂人が真占いの結果見てから宣言したのでは」議論などはできます）


[ゲームの進行](../../wiki/ゲームの進行) にて，ゲーム中の様子を含め，詳しく説明されています．

