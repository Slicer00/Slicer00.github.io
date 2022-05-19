# Slicer00.github.io
7 zipのインストール
    指示に従っていけばOK

gccのダウンロード
    winlibs.com

右クリック→7zip→ここに解凍

MinGWのフォルダをC:\program files\に移動

pathを通す
設定→システム情報→システムの詳細設定　画面下、pathをダブルクリックしてC:\mingw64\binを入力

コマンドプロンプトを開く（検索するか、Win+Rキー→cmdと入力してEnter）
次のコードを打ち込む（C:/の状態で）(cd ../を打てば上のディレクトリに移動できる）
    gcc -v

VScodeでC/C＋＋の拡張機能をインストール

あとはCドライブ直下に英語名でフォルダを作り、
VScodeのファイル→フォルダーを開く→フォルダを選択

エクスプローラを開き、新しいファイルからtest.cなど.c拡張子のファイルを作る

試しに以下のソースコードを入力して、F5キーを押して実行

#include<stdio.h>
int main(void)
{
    printf("Hello, World\n");
    return 0;
}


どうだろう、表示できただろうか
画面下部のターミナルで動作確認は出来るので試してみてほしい。