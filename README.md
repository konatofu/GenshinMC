# Genshin Impact Multiple Calculator (Genshin MC)
 
株式会社miHoYoがサービス提供している「原神」の多機能計算機です。

# ScreenShots
![](https://github.com/konatofu/GenshinMC/blob/e5eab885d0f8fcc2be951315f31c898ca5e6bb42/images/1.png)
![](https://github.com/konatofu/GenshinMC/blob/e5eab885d0f8fcc2be951315f31c898ca5e6bb42/images/2.png)
![](https://github.com/konatofu/GenshinMC/blob/f972fd1c485e8040f39930e511fae854e68cd9e7/images/artifact-std.png)
![](https://github.com/konatofu/GenshinMC/blob/f972fd1c485e8040f39930e511fae854e68cd9e7/images/artifact-ar.png)
![](https://github.com/konatofu/GenshinMC/blob/28295030a485bac083d9288a8630543e171f1533/images/5.png)
 
# Features
 
・課金アイテムの購入数から課金額を算出

・課金予算額から購入数を算出

・聖遺物スコア計算を2種類搭載

  - スタンダード方式
  
  - Artifact-Rater方式
 
# Requirement
 
OS：Windows 7 / 8 / 8.1 / 10 / 11

CPU：Intel x64 x86 CPU 及びRyzen CPU

Mem：RAM 1GB以上

Free：128MB以上

Runtime：.NET Core 3.1以上  
 
# Installation
 
[ ポータブル版 ]

インストールは不要です。

解凍フォルダ内にある、exeファイル（GenshinMC.exe）を実行してください。

必要ランタイムパッケージ(.NET Core 3.1)が入っていない方は、各々導入してください。

署名確認が取れず、Microsoft SmartScreenで実行できない方は、必要に応じて証明書のインストールもお願いします。

解凍フォルダ内の[ ./CA ]フォルダに、証明書導入キットを同梱しています。

CAフォルダ内の[ CertMainProcess.bat ]を実行して頂くと、証明書がインストールされます。


[ インストーラ版 ] 

1．Githubダウンロードぺージより、32bitインストーラ(GenshinMCSetup_xxx_x86.exe)、64bitインストーラ(GenshinMCSetup_xxx_x64.exe)を使用環境に応じてダウンロードしてください。


2．ダウンロードしたファイルを実行してください。

　この時、Microsoft SmartScreenにより実行できない方は、SmartScreenの詳細情報を開いて頂き、そこから実行してください。


3．あとはインストーラの流れに沿って、進めてください。

　この時、必要ランタイムパッケージがインストールされていない場合は、自動的にインストールされます。

　さらに、このタイミングで証明書のインストールも実施されます。

# Usage
 
各機能にて、必要項目を入力するだけで自動計算されます。

聖遺物スコア計算機能における、Artifact-Rater方式のみ、必要に応じて係数設定が必要です。

本ツールのGithub Wikiにてご確認ください。

[GenshinMC Wiki - Artifact-Rater方式](https://github.com/konatofu/GenshinMC/wiki/%233---%E8%81%96%E9%81%BA%E7%89%A9%E3%82%B9%E3%82%B3%E3%82%A2%E3%83%AA%E3%83%B3%E3%82%B0%E6%A9%9F%E8%83%BD#artifact-rater%E6%96%B9%E5%BC%8F)
 
# Note

### 利用規約

[Genshin Impact Multiple Calculator ソフトウェア利用規約](https://github.com/konatofu/GenshinMC/blob/master/Term%20of%20Use_jp.md)
 
### 注意事項

1．天井到達可能推定数は小数点以下切り捨てで、仮天井、本天井の算出が可能です。

2．空月の祝福は180日を超える個数（購入数7個以上）は指定できません。

3．聖遺物スコア計算のArtifact-Rater方式は、本家Artifact-Rater BOTのソースコードを使用していない為、多少の誤差があります。ご了承ください。

4．本ソフトウェアがアンチウィルスソフトで検知される場合がありますが、誤検知のため使用の際はホワイトリストにいれて使用してください。

　※本ソフトウェアは外部通信等の制御やシステムファイルを参照する等コードは含まれておらず、スタンドアロン型のソフトウェアです。
 

### 免責事項
1．画像類の著作権は株式会社miHoYoに帰属します。

2．本ソフトウェアのリバースエンジニアリング、逆コンパイルや改ざん、無断転載はしないでください。

3．HoYoLAB及び原神の利用規約に基づき、株式会社miHoYoが所持する知的財産（本サイト及びゲーム等）への不正行為（破壊スクリプトコードや不正アクセス等）や不正改ざんを行うようなコード、プログラム処理は一切含まれておりません。

参照元：[HoYoLAB利用規約](https://www.hoyolab.com/agreement)

参照元：[原神利用規約](https://genshin.mihoyo.com/ja/company/terms)

参照元：[Genshin Impact - Response to Script, Plug-In, and Third-Party Software Issues](https://genshin.mihoyo.com/en/news/detail/5763)

4．リバースエンジニアリングや逆コンパイル等を行い、悪意のあるソフトウェアに書き換えられた本ソフトウェアの2次配布物については、一切の責任を負いません。

5．その他、本ソフトウェアを利用して生じた、如何なる損害も保障することはできません。
 
# Author
  
* 作成者 こなとーふ
* Twitter [@konatofu_game](https://twitter.com/konatofu_game)

# License
[Visual Studio 2019](https://visualstudio.microsoft.com/)

[SQLite](https://ja.wikipedia.org/wiki/SQLite)

[MIT license](https://en.wikipedia.org/wiki/MIT_License)
