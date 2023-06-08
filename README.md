# Kadai04
課題04_Firebase


<h3>①課題内容（どんな作品か）</h3>
・前回提出した「お口の健康シミュレーション」のWebアプリに対し、以下要素を盛り込みました。<br>
　・Firebase　RealtimeDatabese<br>
　・Firebase　Storage<br>
　・Tensorflo　CocoSSD（AI物体検出）<br>

・AIによる口腔診断を実現するために、どうしてもAI解析要素を入れたかったため機械学習について勉強しました。<br>
・が、さすがにMLモデル構築は現実敵ではなかったため、すでに事前トレーニング済みのMLモデルで一番簡単に応用できる、TensorflowのJavaScript向けMLモデルであるCocoSSDを利用しました。<br>
・本当は歯を検出できるようにしたかったのですが、人物検出くらいまでしかできなさそうでしたが、一応残してあります。<br>
・MLモデルを自分で構築するにはいろいろハードルが高そう（1万枚くらい被験写真必要かな、、）がわかりました。<br>

・プログラミングについては、非同期処理について勉強しました。<br>
・JSフォルダ内に「firebase.js」ファイルが存在しますが、APIKeyが書かれているためUPLOADしていません。<br>


---------------------------[前回提出したReadMe]----------------------------

<h3>①課題内容（どんな作品か）</h3>
・お口の健康シミュレーションのWebアプリです。<br>
・卒業制作(仮)で提出したサイトのフロントサイドを作成してみました。<br>
・AI画像診断と記載していますが、今は実装できてません（卒業制作予定）<br>


<h3>②工夫した点・こだわった点</h3>
・年齢や歯磨きの頻度などの情報を入力し、その情報をローカルストレージに格納しています(5秒に一回)<br>
・5秒に一度Input内容をチェックする仕様としていて、内容をローカルストレージに格納します。意図せぬリロードなどが発生した際、ローカルストレージにでーたがあればそれを反映できるようにしています。
・シミュレーション結果ページでは、ローカルストレージに格納したデータを用いて、IF文などを使い結果を表示させています。<br>
・必須項目をすべて選択したらボタンがクリックできる機能を入れましたが、リロード後ローカルストレージから値をとってくる際にボタン状態を正しく反映できるようにした点。<br>
・フレキシブルレイアウトに調整しました。<br>

<h3>③難しかった点・次回トライしたいこと(又は機能)</h3>
・6/2　2:30時点で、CSSについてはスマホ用ページしか完成しておりません。（760px以上で見ると崩れます）<br>
　PC用ページについては、いったん提出後、土曜日までに仕上げます。<br>
　6/2　18：00時点で、上記修正いたしました。<br>

・画像をLocal storageに格納した際、ファイル名も同じく格納して利用したかったのですが、セキュリティ上の問題でエラーとなり実装ができませんでした。<br>


<h3>④質問・疑問・感想、シェアしたいtips等なんでも</h3>
[感想]今週はあまり時間が取れず、かなりきつかったです。来週は余裕をもって進められるよう頑張ります。
