# Toy-Box

※リンク先のファイルは「右クリックで保存」を推奨します。(ブラウザーに直接表示してしまう可能性がある為)  
※私の都合に合った仕様としているため、パッチはインストーラー的に使う前提であることをご理解ください。  
※パッチはかなりの確率でセキュリティ機能に誤検知されます。[VirusTotal](https://www.virustotal.com/gui/home/upload) 等をご活用ください。  
※公式へのコミットを可能な範囲で行いますが、私の拙い英語力が原因で成果が得られない場合もあります。  
※Windows 10 Pro 21H2 x64 用に最適化しています。その他の OS では表示が崩れる可能性があります。  
※更新停止しているような古いアプリは [Study-Room レポジトリ](https://github.com/Rukoto/Study-Room) を参照ください。  
※「jetAudio 日本語言語パック」は [こちら](https://github.com/Rukoto/JetAudio-Japanese-Language-pack) を参照ください。

---
## 「中の人からのコメント」
[こちら](https://github.com/Rukoto/Toy-Box/blob/master/Comment.md)に掲載しております。

---
## 「7-Zip Ver.21.07」日本語環境対応パッチ
高い圧縮率を誇る多機能アーカイバ「[7-Zip](https://sevenzip.osdn.jp/)」の日本語環境対応パッチを更新しています。  
ヘルプ含む各ファイルの日本語化と訳文の修正、ファイルマネージャーの整形を行います。

ダウンロード: [7-Zip-21.07_x64-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/7-Zip-Japanese-Patch/7-Zip-21.07_x64-jp.exe)  
ダウンロード: [7-Zip-21.07_x86-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/7-Zip-Japanese-Patch/7-Zip-21.07_x86-jp.exe)  

[COPYING (LGPLv3)](https://www.gnu.org/licenses/lgpl-3.0.ja.html)  
-「7-Zip」の著作権は Igor Pavlov氏 にあります。  
リソースを書き換えただけなので、バイナリ自体がソースです。リソースエディターで確認できます。

ヘルプのソース (Ver.21.07): [7-Zip-21.07_Help-jp.7z](https://github.com/Rukoto/Toy-Box/raw/master/7-Zip-Japanese-Patch/7-Zip-21.07_Help-jp.7z)  
ヘルプに関しては機械翻訳の割合が高いです。更新はバージョンアップ時に気が向いたら。

---
## 「Autoruns Ver.14.07」日本語化パッチ
スタートアップ確認ユーティリティ「[Autoruns](https://docs.microsoft.com/en-us/sysinternals/downloads/autoruns)」には [wwwcfe氏](https://wwwcfe.hatenablog.com/entry/20100609/autoruns) の日本語化パッチがありますが、  
UI の改善と訳文を追加・変更、さらに倍直対応した日本語化パッチを公開しています。

ダウンロード: [Autoruns-14.07_x64-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/Autoruns-Japanese-Patch/Autoruns-14.07_x64-jp.exe)  
ダウンロード: [Autoruns-14.07_x86-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/Autoruns-Japanese-Patch/Autoruns-14.07_x86-jp.exe)  
なお、ARM64 版の作成予定はありません。作れるけど検証できないので。

作成のきっかけは [wwwcfe氏](https://wwwcfe.hatenablog.com/entry/20100609/autoruns) の日本語化パッチですが、すべて刷新した完全なる別モノとなっております。

-「Autoruns」の著作権は Sysinternals にあります。

---
## 「CPU-Z Ver.1.99」日本語化パッチ
ハードウェア情報確認ユーティリティ「[CPU-Z](https://www.cpuid.com/softwares/cpu-z.html)」には [wwwcfe氏](https://wwwcfe.hatenablog.com/entry/20100325/cpuz) の日本語化パッチがありますが、  
UI の改善と訳文を追加・変更、さらに倍直対応した日本語化パッチを公開しています。

ダウンロード (20220107140604): [CPU-Z-1.99_x64-jp_20220107140604.exe](https://github.com/Rukoto/Toy-Box/raw/master/CPU-Z-Japanese-Patch/CPU-Z-1.99_x64-jp_20220107140604.exe)  
同一バージョンのまま差し替えることがあるらしく、タイムスタンプを追記。  
適用できない場合は旧版を試すか、当方が気がついて更新するのをお待ち下さい。  
ファイル名前を変更すれば Setup 版にも適用出来ます。x86 版の作成予定はありません。

-「CPU-Z」の著作権は Franck Delattre氏 にあります。

---
## 「Driver Store Explorer Ver.0.11.75」日本語言語ファイル (コメントのみ)
ドライバーストア管理アプリ「[Driver Store Explorer](https://github.com/lostindark/DriverStoreExplorer)」の日本語訳を更新しています。  
ドライバーストア内に残存してしまった使われていない古いドライバーを簡単に確認でき、  
バージョン等を列挙して表示することで、確実にクリーンアップできるのが特徴です。

---
## 「FileZilla Client Ver.3.57.0」日本語言語ファイル (作業用)
## 「libfilezilla Ver.0.35.0」日本語言語ファイル (作業用)
高機能 FTP クライアント「[FileZilla Client](https://FileZilla-project.org/)」の日本語言語ファイルを更新しています。  
また C++ ライブラリの「[libfilezilla](https://lib.filezilla-project.org/)」も併せて翻訳しています。  
公式バイナリに同梱されているもので十分な翻訳率ですので、通常は公式版のままご使用ください。

ダウンロード (Ver.3.15.0.2 for Win2K): [filezilla.mo](https://github.com/Rukoto/Toy-Box/raw/master/FileZilla_Client-Japanese-Language-File/3.15.0.2/filezilla.mo)

[COPYING (GPLv2)](https://www.gnu.org/licenses/old-licenses/gpl-2.0.ja.html)  
-「FileZilla Client」および「libfilezilla」の著作権は Tim Kosse氏にあります。

---
## 「FileZilla Server Ver.0.9.60.2」日本語化パッチ
無料 FTP サーバーアプリ「[FileZilla Server](https://FileZilla-project.org/)」の日本語化パッチを更新しています。  
古いバージョンですので、公開サーバーとしての運用は厳禁です。  
Ver.1.X.X の日本語化は倍直の負荷が高すぎるため、対応予定はありません。

ダウンロード (Ver.0.9.60.2 用): [FileZilla_Server-0.9.60.2-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/FileZilla_Server-Japanese-Patch/FileZilla_Server-0.9.60.2-jp.exe)  
ダウンロード (Ver.0.9.43 for WinXP): [FileZilla_Server-0.9.43-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/FileZilla_Server-Japanese-Patch/FileZilla_Server-0.9.43-jp.exe)

古いバージョンの本体は [ココ](https://download.filezilla-project.org/server/) から入手できます。  
OpenSSL の DLL ファイルは [ココ](https://indy.fulgan.com/SSL/) の openssl-1.0.2u-i386-win32.zip で上書きを推奨。

[COPYING(GPLv2)](https://github.com/Rukoto/Toy-Box/raw/master/FileZilla_Server-Japanese-Patch/COPYING)  
-FileZilla Server の著作権は Tim Kosse氏にあります。

元となった日本語化パッチを公開されている [パソコンおやじ氏](http://www.aconus.com/~oyaji/) に感謝。

---
## 「Fort Firewall Ver.3.4.3」日本語言語ファイル (作業用)
パーソナルファイアウォールアプリ「[Fort Firewall](https://github.com/tnodir/fort)」の日本語言語ファイルを更新しています。  
といっても 5ch のリクエストに応えただけで、もしかしたら一時的な公開になるかも?

ダウンロード: [i18n_ja.qm](https://github.com/Rukoto/Toy-Box/raw/master/Fort_Firewall-Japanese-Language-File/i18n_ja.qm)

[COPYING (GPLv3)](https://www.gnu.org/licenses/gpl.html)  
-「Fort Firewall」の著作権は Nodir Temirkhodjaev氏 にあります。

---
## 「Greenshot Ver.1.3.220」日本語言語ファイル
スクリーンキャプチャアプリ「[Greenshot](https://getgreenshot.org/)」の日本語言語ファイルを更新するパッチです。  
プラグインによる Imgur へのアップロードが便利で、随分昔から愛用しています。  
ローカライズの仕様がそもそも微妙なので、一部に妥協した翻訳を含みます。  
また、プラグインが部分的に翻訳されない等の不具合が内在しています。

ダウンロード: [Greenshot-1.3.220-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/Greenshot-Japanese-Patch/Greenshot-1.3.220-jp.exe)

-「Greenshot」の著作権は Thomas Braun氏、Jens Klingen氏、Robin Krom氏 にあります。

---
## 「Homedale Ver.2.02」日本語化パッチ
WiFi/WLAN モニターアプリ「[Homedale](https://www.the-sz.com/products/homedale/)」を日本語化するパッチです。

ダウンロード: [Homedale-2.02-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/Homedale-Japanese-Patch/Homedale-2.02-jp.exe)

-「Homedale」の著作権は the sz development にあります。

---
## 「Locate32 Ver.3.1.11.7100」日本語環境対応パッチ
データベース型高速ファイル検索アプリ「[Locate32](https://locate32.cogit.net/)」を日本語化します。ネットワークドライブの検索用に。  
UI の日本語化と訳文修正、および最適化、さらに設定バックアップツールの日本語化も含まれます。

ダウンロード: [Locate32_3.1.11.7100_x64-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/Locate32-Japanese-Patch/Locate32_3.1.11.7100_x64-jp.exe)  
ダウンロード: [Locate32_3.1.11.7100_x86-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/Locate32-Japanese-Patch/Locate32_3.1.11.7100_x86-jp.exe)

作成のきっかけは [Tilt氏](http://tiltstr.seesaa.net/) の言語ファイルですが、すべて刷新した完全なる別モノとなっております。

---
## 「LockHunter Portable Ver.3.4.3.146」日本語化パッチ
ファイル等のロックを解除するツール「[LockHunter](https://lockhunter.com/)」を日本語化するパッチです。

ダウンロード: [LockHunter_Portable-3.4.3.146-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/LockHunter_Portable-Japanese-Patch/LockHunter_Portable-3.4.3.146-jp.exe)

セットアップ版には本パッチは適用できませんし、作成予定もありません。

-「LockHunter」の著作権は Crystal Rich Ltd にあります。

---
## 「Open-Shell Ver.4.4.169」日本語言語ファイル
スタートメニュー等のカスタマイズアプリ「[Open-Shell](https://open-shell.github.io/Open-Shell-Menu/)」の日本語言語ファイルを公開しています。

ダウンロード (4.4.156 ～ 4.4.162 用): [Open-Shell-4.4.156-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/Open-Shell-Japanese-Language-File/4.4.156/Open-Shell-4.4.156-jp.exe)  
ダウンロード (4.4.163 ～ 4.4.165 用): [Open-Shell-4.4.163-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/Open-Shell-Japanese-Language-File/4.4.163/Open-Shell-4.4.163-jp.exe)  
ダウンロード (4.4.166 ～ 4.4.169 用): [Open-Shell-4.4.166-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/Open-Shell-Japanese-Language-File/4.4.166/Open-Shell-4.4.166-jp.exe)

ダウンロード (4.4.170-fpwrxbaq 用): [Open-Shell-4.4.170-fpwrxbaq-jp.exe](https://github.com/Rukoto/Toy-Box/raw/master/Open-Shell-Japanese-Language-File/4.4.170-fpwrxbaq/Open-Shell-4.4.170-fpwrxbaq-jp.exe)

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
## 「Resource Hacker Ver.4.X / Ver.5.X」日本語言語ファイル
定番リソースエディター「[Resource Hacker](http://www.angusj.com/resourcehacker/)」には [wwwcfe氏](http://d.hatena.ne.jp/wwwcfe/20100917/resourcehacker) の日本語言語ファイルがありますが、  
UI の改善と訳文を追加・変更、サイズダウンを適用した言語ファイルを公開しています。

ダウンロード (Ver.4.5.30.180 用): [ResourceHacker.JP](https://github.com/Rukoto/Toy-Box/raw/master/Resource_Hacker-Japanese-File/4.5.30.180/ResourceHacker.JP)  
ダウンロード (Ver.5.1.8.360 用): [ResourceHacker.JP](https://github.com/Rukoto/Toy-Box/raw/master/Resource_Hacker-Japanese-File/5.1.8.360/ResourceHacker.JP)

Ver.4.5.30.180 の本体は [ココ(Wayback Machine)](https://web.archive.org/web/20180223164138/http://www.angusj.com/resourcehacker/) から入手できます。

作成のきっかけは [wwwcfe氏](http://d.hatena.ne.jp/wwwcfe/20100917/resourcehacker) の言語ファイルですが、すべて刷新した完全なる別モノとなっております。

-「Resource Hacker」の著作権は Angus Johnson にあります。

---
## 「WuMgr Ver.1.1b」日本語対応言語ファイル (作業用)
サードパーティ製 Windows Update クライアント「[WuMgr](https://github.com/DavidXanatos/wumgr)」の言語ファイルを更新しています。  
公式バイナリに同梱されているもので十分な翻訳率ですので、通常は公式版のままご使用ください。

[COPYING (GPLv3)](https://www.gnu.org/licenses/gpl.html)  
-「WuMgr」の著作権は DavidXanatos氏 にあります。
