#概要
golang におけるおける jwt トークン認証の演習。
参考記事(https://www.youtube.com/watch?v=-Scg9INymBs&t=1165s)

#動作確認
/client/maing.go と/server/main.go を起動し、localhost:9001 に接続すると「Super secret Infomation」と表示されれば成功。
/client/maing.go、あるいは/server/main.go/server/main.go の「mySigningKey」の文字列をどちらかだけを変更することで認証が弾かれることも併せて確認できる。
