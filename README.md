# Toy-Box

※リンク先のファイルは「右クリックで保存」を推奨します。(ブラウザーに直接表示してしまう可能性がある為)  
※私の都合に合った仕様としているため、パッチはインストーラー的に使う前提であることをご理解ください。  
※パッチはかなりの確率でセキュリティ機能に誤検知されます。[VirusTotal](https://www.virustotal.com/gui/home/upload) 等をご活用ください。  
※公式へのコミットを可能な範囲で行いますが、私の拙い英語力が原因で成果が得られない場合もあります。  
※Windows 11 Pro 24H2 用に最適化しています。その他の OS では表示が崩れる可能性があります。  
※更新停止/低需要/諸事情アリといった優先度の低いアプリは [Study-Room レポジトリ](https://github.com/Rukoto/Study-Room) を参照ください。  
※「jetAudio 日本語言語パック」は [こちら](https://github.com/Rukoto/JetAudio-Japanese-Language-pack) を参照ください。

---
## 「中の人からのコメント」
[こちら](https://github.com/Rukoto/Toy-Box/blob/master/Comment.md)に掲載しております。

---
## 「7-Zip Ver.25.00」日本語環境対応パッチ
高い圧縮率を誇る多機能アーカイバ「[7-Zip](https://www.7-zip.org/)」の日本語環境対応パッチを更新しています。  
ヘルプ含む各ファイルの日本語化と訳文の修正、ファイルマネージャーの整形を行います。

ダウンロード (x64): [7-Zip-25.00_x64-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/7-Zip-Japanese-Patch/7-Zip-25.00_x64-jp.exe)  
ダウンロード (x86): [7-Zip-25.00_x86-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/7-Zip-Japanese-Patch/7-Zip-25.00_x86-jp.exe)  
今回はヘルプの日本語化を含みません。時間ができたらヘルプを含めて再リリースします。

[COPYING (LGPLv3)](https://www.gnu.org/licenses/lgpl-3.0.ja.html)  
-「7-Zip」の著作権は Igor Pavlov氏 にあります。  
リソースを書き換えただけなので、バイナリ自体がソースです。リソースエディターで確認できます。

ヘルプのソース (Ver.23.01): [7-Zip-23.01_Help-jp.7z](https://github.com/Rukoto/Toy-Box/raw/master/7-Zip-Japanese-Patch/7-Zip-23.01_Help-jp.7z)  
ヘルプに関しては機械翻訳の割合が高いです。更新はバージョンアップ時に気が向いたら。

---
## 「Autoruns Ver.14.11」日本語化パッチ
スタートアップ確認ユーティリティ「[Autoruns](https://docs.microsoft.com/en-us/sysinternals/downloads/autoruns)」には [wwwcfe氏](https://wwwcfe.hatenablog.com/entry/20100609/autoruns) の日本語化パッチがありますが、  
UI の改善と訳文を追加・変更、さらに倍直対応した日本語化パッチを公開しています。

ダウンロード (x64): [Autoruns-14.11_x64-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/Autoruns-Japanese-Patch/Autoruns-14.11_x64-jp.exe)  
ダウンロード (x86): [Autoruns-14.11_x86-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/Autoruns-Japanese-Patch/Autoruns-14.11_x86-jp.exe)  
なお、ARM64 版の作成予定はありません。作れるけど検証できないので。

作成のきっかけは [wwwcfe氏](https://wwwcfe.hatenablog.com/entry/20100609/autoruns) の日本語化パッチですが、すべて刷新した完全なる別モノとなっております。

-「Autoruns」の著作権は Sysinternals にあります。

---
## 「Driver Store Explorer Ver.0.12.88」日本語言語ファイル (コメントのみ)
ドライバーストア管理アプリ「[Driver Store Explorer](https://github.com/lostindark/DriverStoreExplorer)」の日本語訳を更新しています。  
ドライバーストア内に残存してしまった使われていない古いドライバーを簡単に確認でき、  
バージョン等を列挙して表示することで、確実にクリーンアップできるのが特徴です。

---
## 「EasyBCD Ver.2.4.0.237」日本語言語ファイル
ブートローダー編集アプリ「[EasyBCD](https://neosmart.net/EasyBCD/)」の日本語言語ファイルを公開しています。

ダウンロード: [EasyBCD-2.4.0.237-ja.exe](https://github.com/Rukoto/Toy-Box/raw/master/EasyBCD-Japanese-Language-File/EasyBCD-2.4.0.237-ja.exe)

-「EasyBCD」の著作権は [NeoSmart Technologies](https://github.com/neosmart) にあります。

---
## 「FileZilla Client Ver.3.69.1」日本語言語ファイル (作業用)
## 「libfilezilla Ver.0.49.0」日本語言語ファイル (作業用)
高機能 FTP クライアント「[FileZilla Client](https://FileZilla-project.org/)」の日本語言語ファイルを更新しています。  
また C++ ライブラリの「[libfilezilla](https://lib.filezilla-project.org/)」も併せて翻訳しています。  
公式バイナリに同梱されているもので十分な翻訳率ですので、通常は公式版のままご使用ください。

[COPYING (GPLv2)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.ja.html)  
-「FileZilla Client」および「libfilezilla」の著作権は Tim Kosse氏にあります。

---
## 「FileZilla Server Ver.1.8.0」日本語化パッチ
無料 FTP サーバーアプリ「[FileZilla Server](https://FileZilla-project.org/)」の日本語化パッチを更新しています。  
すべて倍直であることと、一部の参照先が共有モジュール化されているため、  
一部が意図的に未翻訳だったり、アクセスキーが省略されたりしています。

ダウンロード (1.8.0 用): [FileZilla_Server-1.8.0-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/FileZilla_Server-Japanese-Patch/FileZilla_Server-1.8.0-jp.exe)  
ダウンロード (0.9.60.2 用): [FileZilla_Server-0.9.60.2-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/FileZilla_Server-Japanese-Patch/FileZilla_Server-0.9.60.2-jp.exe)  
ダウンロード (0.9.43 for WinXP): [FileZilla_Server-0.9.43-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/FileZilla_Server-Japanese-Patch/FileZilla_Server-0.9.43-jp.exe)

古いバージョンの本体は [Internet Archive](http://web.archive.org/web/20231115122607/https://download.filezilla-project.org/server/) から入手できます。  
0.9.X 系の OpenSSL の DLL ファイルは [ココ](https://indy.fulgan.com/SSL/) の openssl-1.0.2u-i386-win32.zip で上書きを推奨。

[COPYING(GPLv2)](https://github.com/Rukoto/Toy-Box/raw/master/FileZilla_Server-Japanese-Patch/COPYING)  
-FileZilla Server の著作権は Tim Kosse氏にあります。

元となった日本語化パッチを公開されている [パソコンおやじ氏](http://www.aconus.com/~oyaji/) に感謝。

---
## 「Greenshot Ver.1.3.290 RC1」日本語言語ファイル
スクリーンキャプチャアプリ「[Greenshot](https://getgreenshot.org/)」の日本語言語ファイルを更新するパッチです。  
プラグインによる Imgur へのアップロードが便利で、随分昔から愛用しています。

ダウンロード (1.3.290 RC1 用): [Greenshot-1.3.290-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/Greenshot-Japanese-Patch/Greenshot-1.3.290-jp.exe)  

-「Greenshot」の著作権は Thomas Braun氏、Jens Klingen氏、Robin Krom氏 にあります。

---
## 「ImDisk Toolkit 20250206」日本語化ファイル
仮想ドライブ作成アプリ「[ImDisk Toolkit](https://sourceforge.net/projects/imdisk-toolkit/)」の日本語化ファイルを更新しています。

ダウンロード (20241123 / 20250206 用): [ImDiskTk-20241123-jp.zip](https://github.com/Rukoto/Toy-Box/raw/master/ImDisk_Toolkit-Japanese-File/ImDiskTk-20241123-jp.zip)

インストール時にセットアップファイルを日本語化する使い方になりますので、  
公式の files.cab と同じディレクトリに上記 Zip ファイルの中身を展開し、  
install_jp.bat を実行するだけです。言語は「English」を指定する必要があります。

一部は意図的に翻訳しておりません。(ショートカット名やコンテキストメニュー)

[COPYING (WTFPL)](http://www.wtfpl.net/)  
-「ImDisk Toolkit」の著作権は Olof氏、v77氏、Kenneth Bell氏、その他の方々にあります。

---
## 「Locate32 Ver.3.1.11.7100」日本語環境対応パッチ
データベース型高速ファイル検索アプリ「[Locate32](https://locate32.cogit.net/)」を日本語化します。ネットワークドライブの検索用に。  
UI の日本語化と訳文修正、および最適化、さらに設定バックアップツールの日本語化も含まれます。

ダウンロード (x64): [Locate32-3.1.11.7100_x64-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/Locate32-Japanese-Patch/Locate32-3.1.11.7100_x64-jp.exe)  
ダウンロード (x86): [Locate32-3.1.11.7100_x86-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/Locate32-Japanese-Patch/Locate32-3.1.11.7100_x86-jp.exe)

作成のきっかけは [Tilt氏](http://tiltstr.seesaa.net/) の言語ファイルですが、すべて刷新した完全なる別モノとなっております。

---
## 「LockHunter Portable Ver.3.4.3.146」日本語化パッチ
ファイル等のロックを解除するツール「[LockHunter (Portable)](https://blog.crystalrich.com/lockhunter-3-4-released/#more-1148)」を日本語化するパッチです。

ダウンロード: [LockHunter_Portable-3.4.3.146-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/LockHunter_Portable-Japanese-Patch/LockHunter_Portable-3.4.3.146-jp.exe)

セットアップ版には本パッチは適用できませんし、作成予定もありません。

-「LockHunter」の著作権は Crystal Rich Ltd にあります。

---
## 「Open-Shell Ver.4.4.196」日本語言語ファイル
スタートメニュー等のカスタマイズアプリ「[Open-Shell](https://open-shell.github.io/Open-Shell-Menu/)」の日本語言語ファイルを公開しています。

ダウンロード (Latest: 4.4.194以降用): [Open-Shell-4.4.194-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/Open-Shell-Japanese-Language-File/4.4.194/Open-Shell-4.4.194-jp.exe)

Windows 11 では[ExplorerPatcher](https://github.com/valinet/ExplorerPatcher) の併用を推奨します。  
ただし、Windows セキュリティによる ~~誤検知~~ **嫌がらせ** に対処できる方に限ります。

「Classic Shell」時代からの言語ファイル更新機能の仕様に従っていますので、  
%ALLUSERSPROFILE%\OpenShell\Languages へ ja-JP.dll をインストールします。  
本体と同じ場所に再配置しても動作しますが、この場合の優先順位は下位となります。  
言語ファイルが複数の場所に存在してしまわないよう、注意してください。

---
## 「PDF-XChange Viewer Ver.2.5.322.10」日本語言語ファイル
「[PDF-XChange Viewer](https://www.tracker-software.com/product/downloads/discontinued)」の日本語言語ファイルを更新するパッチです。

ダウンロード: [PDF-XChange_Viewer-2.5.322.10-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/PDF-XChange_Viewer-Japanese-Patch/PDF-XChange_Viewer-2.5.322.10-jp.exe)

パッチ処理が「差分」ではなく「上書き」なのは個人的な理由による仕様です。  
後継の「PDF-XChange Editor」の更新作業にも着手しており、進捗は 95% ぐらい。  
個人的には低品質と思うものの不都合だとも聞かないので、気長にやります。

-「PDF-XChange Viewer」の著作権は PDF-XChange Co Ltd にあります。

---
## 「Resource Hacker Ver.5.2.8.448」日本語言語ファイル
定番リソースエディター「[Resource Hacker](http://www.angusj.com/resourcehacker/)」には [wwwcfe氏](http://d.hatena.ne.jp/wwwcfe/20100917/resourcehacker) の日本語言語ファイルがありますが、  
UI の改善と訳文を追加・変更、サイズダウンを適用した言語ファイルを公開しています。  
(複数の箇所で表記揺れがあったので差し替えました。)

ダウンロード: [ResourceHacker.JP](https://github.com/Rukoto/Toy-Box/raw/master/Resource_Hacker-Japanese-File/ResourceHacker.JP)

作成のきっかけは [wwwcfe氏](http://d.hatena.ne.jp/wwwcfe/20100917/resourcehacker) の言語ファイルですが、すべて刷新した完全なる別モノとなっております。

-「Resource Hacker」の著作権は Angus Johnson氏 にあります。

---
## 「simplewall Ver.3.8.6.1」日本語対応言語ファイル (作業用)
その名の通りのシンプルなファイアウォール「[simplewall](https://github.com/henrypp)」の日本語言語ファイルを更新しています。  
公式のアップデート機能がありますので、通常は公式版のままご使用ください。

[COPYING (GPLv3)](https://www.gnu.org/licenses/gpl.html)  
-「simplewall」の著作権は Henry++氏 にあります。

---
## 「Windows Update MiniTool 22.04.2022」日本語言語ファイル
サードパーティ製 Windows Update クライアント「[Windows Update MiniTool](http://forum.ru-board.com/topic.cgi?forum=5&topic=48142#2)」の言語ファイルを更新しています。  
「WuMgr」と同期させるために、あえていくつかの訳文が原文と合致していません。  
以前のバージョンに比べ、UI が詳細/拡大した事は好みが分かれる気がします。

ダウンロード: [ja.lng](https://github.com/Rukoto/Toy-Box/raw/master/Windows_Update_MiniTool-Japanese-Language-File/22.04.2022/ja.lng)

元となった日本語言語ファイルを公開されていた [しろみち氏](https://twitter.com/Nico_LunaOrbit) に感謝。

---
## 「WuMgr Ver.1.1b」日本語対応言語ファイル (作業用)
サードパーティ製 Windows Update クライアント「[WuMgr](https://github.com/DavidXanatos/wumgr)」の言語ファイルを更新しています。  
公式バイナリに同梱されているもので十分な翻訳率ですので、通常は公式版のままご使用ください。  
小生は前項の「Windows Update MiniTool」よりもこちらを愛用しています。

[COPYING (GPLv3)](https://www.gnu.org/licenses/gpl.html)  
-「WuMgr」の著作権は DavidXanatos氏 にあります。
