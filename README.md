#
そのまんま
リポジトリ＝ディレクトリ
ブランチ＝個々のファイル
コミット＝変更の記録
プルリクエスト＝協力プレイを可能にする機能　ソロプレイでも使える
マージ＝プルリクエストのマージ→ファイルの変更を許可する
ここからは新しいブランチ、説明2で追加します。
どうやらブランチはコミットとマージの為に立てるものでつまりブランチを立てる＝ファイルの変更をするって認識が良さそうだ。
となると元々のファイルはreadmeなのかな？
はい。現状認識しましょう。
read.mdのペンマークをクリックしてコミットをするようです。
次の目標はMINGW64でgit hubへの変更を加えたりできるようにする事。
修行するぞ。
えー。つまりブランチってのはマージする際に消す訳だな。必要ないし
.mdとはなんだろう。
リポジトリ→ブランチの流れ。
そして.mdは前に名前付けられた。
ばっかでー。
変える。
OK理解したよ。
これでgouryuu2.mdが見れる。
見れた。
けれでリポジトリ1つに対して.mdは二つまでしか持てないのか？
まぁそれならそれでよし。
しかし、.mdの名前を変更すると二つ目はその名前になる。
さて
次はgitについて。
gitの機能はgit hubと同じ機能だろ。
ただし、gitはこのパソコンでやっている。そしてgit hubはリモートでやっている。
リポジトリって保存先。
リモートリポジトリ
専用のサーバに配置して複数人で共有するためのリポジトリです。
ローカルリポジトリ
ユーザ一人ひとりが利用するために、自分の手元のマシン上に配置するリポジトリです。
やった。
gitをインストール。一通りの使い方を実践。
git hubの一通りの使い方を実践。
vimをインストール。まだ分からん。
今の課題。
git git hub　ローカルリポジトリとリモートリポジトリ。このパソコンとgit hub上のサーバーって事でいいんだろ。
リポジトリのコピー＝クローン。
やったがうまくいったかどうか判断できない。
さて、もうひとつはvimでリポジトリを弄れるようにするって感じか。
追加
コマンドにおいてgit httpsと続けてた。バカス。
git clone https
というのが正しい。疲れてきたな。
休憩しよう。
追加
これでリモートリポジトリ→ローカルリポジトリへのコピーつまりクローンはできた。
次は逆の流れをやってみる。
その後にvimを使うか。
といってもgit bashで使えるんだが。。。
あ、後git hubはプライベートモードが使えない
あと、パスワードが正しいのに無効と出た可能性が高い。
1スマホで作ったアカウントはパソコンでは使えない→どうしようもない。
2海外のサイトで円記号が使えない→日本語に変えてみよう。
end
追加
git bash
↓
対象ディレクトリへ移動しvimでファイルを作成する
↓
以下のように記述する
git add 追加したいファイル
注意gut hubで対象リポジトリを開いていると警告される。
で、今ここって話です。
追加
CUIでどうやら作業は完結できそうだ。
コピー＝クローンするにはgit hubにサインインしてコード→URLのコピーが必要になるみたいだが。。。
とりあえずマスターへの目途が立ったので寝る。
またこのアカウントはこれでお終いかな。コピペ。
