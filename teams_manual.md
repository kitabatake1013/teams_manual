% 画面読み上げソフトとキーボードを用いたMicrosoft Teams操作マニュアル
% 北畠　一翔
% 2020/06/16

## お断り

この文書は、筑波技術大学保健科学部の学生向けに作成したものです。
Microsoft Teamsの画面レイアウトは、管理者の設定によって多少変化します。
そのため、状況によってはここでの説明と合致しないこともあり得ますので、あらかじめご了承ください。

また、学校用のTeamsと職場用のTeamsでは、画面レイアウトや使える機能が大きく異なります。
ここでは、学校用Teamsについて説明しています。

## はじめに

Microsoft Teamsは、複数人で共同作業をするために開発された、「グループウェア」と呼ばれるソフトの一つです。

沢山の機能があり、操作もやや複雑です。
そこで、このマニュアルでは、よく使いそうな操作を中心に、操作方法の概要を説明します。

なお、本マニュアルでは、「フォーカスを移動する」という表現が多数用いられています。
ここでいう「フォーカス」は、キーボードの操作対象を指します。
この用語はほとんどの場合、「カーソル」と読み替えても差し支えありません。

## スクリーンリーダーの初期設定

スクリーンリーダーでTeamsを操作するために、事前に下記の設定を行うと便利です。
いか、各スクリーンリーダーごとに、設定方法を説明します。

### PC-Talker

1. Ctrl+Alt+F12を押して、PC-Talkerの設定メニューを開きます。このコマンドが動作せず、関係ない画面が表示された場合には、MySupportを起動し、[ツール]→[PC-Talkerの初期設定]→[Intel Graphicsホットキーの設定]を実行すると解決することが多いようです。
2. 上下カーソルキーで、[アプリケーション拡張設定]を選択してEnterキーを押します。
3. Tabキーで、[Internet Explorer ダイレクト操作キーを使用する]に移動して、チェックされている場合にはSpaceキーでチェックを外します。
4. Tabキーで[設定]ボタンに移動して、SpaceまたはEnterキーで実行します。

なお、この設定を行うと、Internet Explorerなどでページ内を移動する操作が、Ctrl+矢印キーに変更されます。
矢印キーだけでページ内を移動させたい場合は、必要に応じて上記の設定を変更してください。
また、Teamsを操作する際にCtrl+矢印キーを押す必要は、基本的にはありません。

### NVDA

NVDAには、Webサイトなどを閲覧するために用いる「ブラウズモード」という特殊なモードがあります。
しかし、Teamsを操作する際にはブラウズモードを無効にした方が便利です。
下記の設定を行うことで、Teamsを操作しようとした際に自動的にブラウズモードに切り替わらないようにすることができます。

1. NVDAキー+Nを押して、NVDAメニューを開きます。
2. 上下カーソルキーで、[設定]を選択して、Enterまたは右カーソルキーを押します。
3. 上下カーソルキーで[設定]を選択してEnterキーを押します。
4. [カテゴリ]のリストで、上下カーソルを押して[ブラウズモード]に移動します。
5. Tabキーで[ページ読み込み時にブラウズモードを有効にする]に移動して、チェックが付いている場合にはSpaceキーでチェックを外します。
6. Tabキーで[OK]ボタンを選択して、EnterキーかSpaceキーを押します。

なお、上記の手順では、Internet Explorerを含む全てのアプリケーションに対する設定が変更されます。
Teamsが動作しているときのみ設定を反映させたい場合には、「設定プロファイル」機能を用いると便利です。
詳しくは、ユーザーガイドなどを参照してください。

また、場合によっては、Teamsを操作する際にブラウズモードに切り替わっていることがあります。
ブラウズモードとフォーカスモード（ブラウズモードが無効の通常の状態）の間を切り替えるには、NVDAキー+Spaceを押します。
このコマンドを実行する度に、初期設定では「ガシャ」、「ポン」という効果音が再生されます。
「ガシャ」と鳴った状態がフォーカスモードで、「ポン」と鳴った状態がブラウズモードです。

### JAWS for Windows

JAWSでTeamsを使用する場合、特別な設定は必要ありません。
ただし、こちらではJAWS2019リリース2の環境でのみテストを行っていますが、JAWSのバージョンによっては、Insert+Vで簡単設定を開き、仮想PCカーソルを無効にする必要があるかもしれません。

また、 [Teams用JAWSスクリプト](https://dlee.org/teams/) も利用できます。
ただし、Teamsの表示言語を日本語に設定している場合、一部の機能は正しく動作しないようです。
以下の説明では、上記のスクリプトをインストールしていない環境を想定しています。

## Teamsの基本操作

### 画面内を移動する

Teamsを起動すると、画面には沢山の項目が表示されます。
Tabキーを使ってそれらの間を移動できます。
また、Ctrl+F6キーを使うことで、Tabキーよりもやや大きな単位で項目の間を移動できます。
また、Ctrl+Eを押すと、いつでも[検索]に移動するので、そこを基点にして操作するという方法もあります。

### 使いたい機能を選択する

Teamsには、「チャット」、「チーム」、「通話」、「予定表」など、いろいろな機能があります。
どの機能を使うかによって、画面の内容が大きく変化します。

Ctrl+Eを押して「検索」に移動した後、Ctrl+F6を押すと、「アプリバー」に移動します。
ここには、利用可能な機能が縦１列に並んでいます。
目的の項目でEnterキーを押すと、画面の表示内容が切り替わります。
アプリバーでHomeキーを押すと一番上の項目、Endキーを押すと一番下の項目が選択されます。

筑波技術大学で使用しているTeamsの場合には、以下のような項目があります。

最新情報
:   最新の通知を確認できます。
チャット
:   １対１、または複数人のグループでチャット（メッセージのやりとり）ができます。
チーム
:   現在自分が所属しているチームが表示されます。最もよく使用する機能かもしれません。
課題
:   現在、この機能はスクリーンリーダーでは使用できないようです。誤ってこのモードに切り替えてTabキーを押してしまうと、キーボードのみでTeamsの画面に戻ることはできません。
予定表
:   会議の予定を確認したり、ここから会議に参加したりすることができます。
通話
:   通話を発信できます。なお、「チャット」から相手を選び、そこから通話を発信することもできるため、あえてここを開く必要はほとんどありません。
ファイル
:   （後日追記予定）
さらに追加されたアプリ
:   （後日追記予定）
アプリ
:   （後日追記予定）
ヘルプ
:   ヘルプを閲覧できます。

なお、アプリバーにフォーカスを移動しなくても、Ctrl+数字キー（テンキー不可）で、該当する項目を選択することができます。
例えば、Ctrl+1で最新情報、Ctrl+2でチャットを直接実行できます。

## 「チーム」、「チャネル」、「スレッド」について

ここでは、Microsoft Teamsにおける「チーム」や「チャネル」といった概念について、簡単に説明します。
Teamsは元々仕事で使うアプリですが、身近な例として「文化祭を企画する」ということを考えると、これらの概念がなぜ必要なのか、イメージできると思います。

### 「チーム」とは

通常、文化祭などの行事を開催する際には、「実行委員会」などと呼ばれる組織が作られ、その中でいろいろなことが決まっていきます。
当然、実行委員会には沢山のメンバーがいるため、メンバー同士それぞれが１対１で話し合っていたのでは時間がかかってしまいます。
そこで、メンバー全員で話し合うための場所が必要になります。

このようなとき、最近は「LINEグループを作ってしまう」ということがよく行われますが、それに近いのが、Teamsにおける「チーム」です。
つまり、「文化祭実行委員会」というチームを作って、そこで話し合うということです。

### 「チャネル」とは

文化祭実行委員会と言っても、全ての事柄について全員で話し合うとは限りません。
例えば、何人かはステージ発表のことを決める係かもしれませんし、他の何人かは模擬店の担当かもしれません。

LINEの場合、その都度「ステージ発表」、「模擬店」というグループを作る必要があります。
しかし、既に実行委員会全体のグループがあるのに、全く別のグループを作って話し合うというのは非効率的です。

そこで、Teamsのチーム内には、「チャネル」という、小さな会議室のようなものを作ることができます。
例えば、「文化祭実行委員会」チームの中に、「ステージ発表」、「模擬店」などのチャネルを作り、そこで話し合うと言うことです。

また、チャネルには「パブリック」のチャネルと「プライベート」のチャネルがあります。
「パブリック」のチャネルの中で行われたやりとりは、そのチームの参加者全員に見えていて、だれでも発言できます。
それに対して、「プライベート」のチャネル内でのやりとりは、一部のメンバー（チャネルを作った人が招待したメンバー）にしか確認できません。

先ほどの文化祭の例で言えば、「ステージ発表」というプライベートチャネルを作り、そこで話し合って決まったことを、そのチーム内のパブリックチャネルに投稿することで、話し合いをスムーズに進められます。

なお、チームを作成すると、自動的に「一般」というパブリックチャネルが作られます。

### 「スレッド」とは

一つのチャネル内で、複数の話題を扱わなければいけないことがあります。
例えば、「ステージ発表」チャネルでは、「ステージ発表のプログラム（順番）」、「必要な機材」というように、いくつかの話題について話し合う必要があります。

このようなとき、全てのメッセージが日時順に並んでいると、会話の内容がわかりにくくなってしまいます。
そこで、各話題ごとにメッセージを整理できると便利です。
「スレッド」とは、一つのチャネル内で、内容（トピック）ごとにメッセージを整理するために作られた機能です。

また、各スレッドには、件名（タイトル）を設定できます。
例えば、「ステージ発表のプログラムについて」という名前が付いていれば、後で読み直したとき、そのスレッドでは何が話し合われたのかが一目でわかり、大変便利です。

新しいスレッドを作る際には、わかりやすい件名を追加するようにしましょう。

### 補足：「組織」について

Teamsに限らず、グループウェアやSNSには、ユーザーを検索する機能があります。
例えば、FaceBookのユーザー検索で「佐藤」と入力すると、日本中の「佐藤」さんが検索され、膨大な量の検索結果が表示されます。
しかし、Teamsで同じことをしても、結果はそれほど多くありません。
なぜ、このようなことが起きるのでしょうか。

Microsoft Teamsは、自分が所属する「組織」の中で使用されることが一般的です。
例えば、私たちは「筑波技術大学」という組織に所属しており、全ての情報はこの組織内で共有されます。
従って、ユーザー検索を行った場合でも、同じ組織に所属するユーザーしか検索できません。

ただし、例外として、組織外のユーザーを「ゲスト」として招待することもできます。
この機能により、特定のチームに外部のユーザーを追加して、全員でTeamsを利用することが可能になります。

## 「チーム」の操作

「チーム」画面を使用することで、自分が所属しているチームを確認したり、各チーム内に用意されたチャネルを表示したり、メッセージの送受信を行ったりできます。

「チーム」を開くには、Ctrl+3を押すか、アプリバーから「チーム」を選択します。

### 自分が所属しているチームを確認する

以前「チーム」から何らかのチームを開いていた場合、自動的にチームのメッセージが表示されます。
もう一度Ctrl+3を押すことで、チーム一覧が表示されるようになります。

チーム一覧が開くと、自動的にチーム一覧にフォーカスが移動します。
あるいは、Ctrl+F6を何度か押して、「アプリバー」の次の項目（環境によって変化する）に移動後、Tabキーで「あなたのチーム」と読み上げる場所を探し、もう１度Tabキーを押すことで、確実にチーム一覧に移動できます。

チーム一覧では、上下左右のカーソルキー（主に左右カーソル）を使って、チームの間を移動できます。
目的のチームを探し、Enterキーを押すと、選択したチームの「一般」チャネルのチャット画面（メッセージのやりとりをする画面、詳細は後述）が表示されます。
また、チーム一覧でチームを選択している状態でCtrl+Shift+矢印キーを押すと、チームの並べ替えができます。

### チャネルの切り替え

チームを開くと、基本的には「一般チャネル」が表示されます。
他のチャネルに切り替えるには、Ctrl+F6を何度か押して、「チームのチャネル一覧」に移動します。
このとき、関係ないチーム名が読み上げられることがありますが、これはTeamsの不具合だと思われます。
上下カーソルキーで目的のチャネルを選び、Enterを押すと、表示が切り替わります。

### チャット画面の操作

チャネルを選択すると、過去に送受信されたメッセージのスレッドと、新しいメッセージを送信するためのコントロールが表示されます。

チャット画面を開くと、メッセージ一覧かメッセージ入力エリアのいずれかにフォーカスが移動します。
「～さんからのn件の返信のある会話のスレッド」などと読み上げた場合は、メッセージリストにフォーカスがあります。
ここでTabキーを押すと、「新しい会話を開始します。@を入力して、誰かにメンションしてください。」と読み上げるコントロールがありますが、これが新しいメッセージを入力するテキスト編集エリアです。

#### メッセージの閲覧

メッセージ一覧で上下カーソルを押すと、過去に送受信されたメッセージを確認できます。
新しいメッセージは下に表示されます。

メッセージがスレッドになっている場合、スレッドに件名が設定されていれば件名が、設定されていなければ最も古いメッセージが表示されます。
スレッドに含まれるメッセージを確認するには、スレッドを選択してEnterキーを押します。
スレッドに大量の返信が含まれる場合、新しいものしか表示されません。
さらに古いメッセージを確認するには、「n件の返信」などと読み上げた所でEnterを押します。
また、スレッドの一番下には「返信」ボタンがあり、ここでEnterキーを押すと、このスレッドに返信できます。

メッセージに対して「いいね!」などのリアクションで応答するには、メッセージを選択してEnterキーを押します。
左右カーソルで目的の応答を選び、Enterを押すと送信されます。
また、ここでTabキーを１回押すと、「その他のオプション」に移動します。
ここでEnterキーを押すとメニューが開き、自分が送信したメッセージであれば、メッセージの編集や削除を行うことができます。
また、メッセージにリンクや会議の情報、添付ファイルなどが含まれる場合は、「その他のオプション」からさらにTabキーを押すことで、それらにアクセスできます。

#### メッセージの作成

メッセージの編集領域でTabキーを押すと、「書式設定」と読み上げる部分があります。
ここで左右カーソルキーを押すと、「書式設定」、「添付」などが選択できます。

「書式設定」を選択してEnterキーを押すと、「作成ボックス」が開き、いろいろな機能を利用できます。
作成ボックスを開いた状態でShift+Tabを何度か押すと、「件名を追加」と読み上げる部分があり、スレッドの件名を設定できます。
また、通常、メッセージを編集してEnterキーを押すと、作成したメッセージが送信されますが、作成ボックスを開いている状態では、Enterキーで改行を挿入できます。
メッセージの編集が終わったら、Tabキーで送信ボタンに移動してEnterキーを押します。

### 「ファイル」の使い方

各チャネルで送受信したファイルを一覧表示することができます。

1. スレッド一覧でShift+Tabを何度か押すと、「投稿タブ」と読み上げる部分があります。
2. ここで左右カーソルを押すと、「ファイル」タブを見つけることができます。「ファイル」タブを選択してEnterキーを押すと、画面が切り替わり、送受信したファイルの一覧にフォーカスが移動します。

上下カーソルキーでファイルやフォルダの間を移動します。
フォルダを選択してEnterキーを押すと、フォルダに保存されたファイルを確認できます。
選択したアイテムをダウンロードするときは、アプリケーションキー（またはShift+F10）でコンテキストメニューを開き、上下カーソルキーで[ダウンロード]を選択してEnterキーを押します。

## チャット機能の利用

ここまでは、「チーム」や「チャネル」というような、組織の中でやりとりをする方法について解説してきました。
しかし、Teamsには、LINEやSkypeのようなチャット機能（LINEのトークのようなもの）も用意されています。
個人的なやりとりだけではなく、「チャネルを作るほどではないけれど、数人で会話したい」という場合にも活用できます。

### 新しく会話を開始する

新しく会話を始めるには、次の操作を行います。

1. Ctrl+Nを押すか、[新しいチャット]ボタン（検索ボックスからShift+Tabを数回押した所にあります）を実行します。
2. チャットをしたい相手の情報を入力する画面になります。名前やメールアドレスを入力します。全てを覚えていなくても、入力を始めると自動的に検索され、結果が表示されます。検索結果にアクセスするには、下矢印キーを押します。該当するユーザが見つかったら、Tabキーを押して確定します。複数人でチャットをしたい場合には、続けて他のユーザを検索します。設定が終わったら、もう一度Tabキーを押します。
3. 自動的に、選択したユーザとのチャット画面に移動します。

### 最近送受信したチャットの履歴から選択する

以前にチャットをしたことがある相手とチャットを開始する場合、上記の手順を毎回実行するのは大変です。
そこで、Teamsでは、チャットの履歴を一覧表示して、そこから選択してチャット画面を開くことができます。

1. Ctrl+2を押して、[チャット]を開きます。この操作を行った際、最後に送受信したチャットが開いた場合には、もう一度同じ操作を行います。
2. チャット履歴のリストにフォーカスが移動します。上下カーソルキーで、チャットを開始したい相手を選択します。個人チャットの場合には、相手のステータス（状態）が読み上げられます。
3. 目的の項目が見つかったら、Enterキーを押して、チャット画面を開きます。

### チャット画面の操作

チャット画面の構造は、チャネルでメッセージを送受信する画面とほとんど同じです。
ただし、チャットには「スレッド」が存在しないため、メッセージ一覧で上下カーソルキーを押すことで、全てのメッセージが確認できます。
また、メッセージ一覧でShift+Tabを何度か押すと、音声通話やビデオ通話を発信するボタンがあります。特別な操作をしなくても、このボタンを実行することで、簡単に通話を発信できます。

## [ファイル]タブの操作

Teamsでは、ファイルの共有を簡単に行うことができます。
現在会話をしているチャネル、または個人やグループでのチャットにファイルをアップロードすることで、必要に応じてダウンロードしたり、編集したりできます。

### [ファイル]タブを開く

会話履歴が表示されるリストからShift+Tabを何度か押すと、[投稿]や[ファイル]などのタブを切り替えられる部分があります。
左右カーソルで目的のタブを選択し、Enterキーを押すと切り替わります。
通常、最初は[投稿]タブが選択されており、右カーソルを押すと[ファイル]タブが選択されます。
なお、PC-Talkerではこの部分を正しく読み上げないようです。

### [ファイル]タブの操作

[ファイル]タブを開くと、既に現在のチャットにファイルがアップロードされている場合は、ファイルリストにフォーカスが移動します。
ファイルがなければリストが表示されないため、どこにもフォーカスがないような状態になります。
その場合は、Tabキーを１度押すと[戻る]ボタンにフォーカスが移動するため、TabキーやCtrl+F6の操作で、[ファイル]タブの中のコントロールにフォーカスを移動できます。

ファイルリストでは、上下カーソルキーを押して項目の間を移動できます。
選択したフォルダやファイルを開くには、Enterキーを押します。
アプリケーションキー（またはShift+F10）でコンテキストメニューが開き、ダウンロードなどの操作が実行できます。
Teams上でファイルを開くと専用のビューワーが起動し、正しく読み上げられないことが多いため、ファイルの内容を確認する際はダウンロードした方が操作しやすくなります。

項目一覧でShift+Tabを押すか、最上段の項目で上カーソルを押すと、「ヘッダ」などと呼ばれる領域に移動します。
左右カーソルを押すと、[全て選択]や[名前]、[更新日時]などの項目が選択できます。
[名前[や[更新日時]でEnterキーを押すとメニューが開き、ここから項目の並べ替えができます。

列ヘッダからさらにShift+Tabを押すと、「コマンドバー」にフォーカスが移動します。
左右カーソルキーで実行したい項目を選択し、Enterキーで実行します。

### ファイルのアップロード

コマンドバーで[アップロード]を実行すると、現在表示されているフォルダにファイルがアップロードされます。
このとき、アップロードするフォルダを間違えた場合は、該当するファイルを選択後、コマンドバーから[移動]を実行すると、アップロードするフォルダを選択できます。

### 「添付」に関する補足

[投稿]タブでメッセージにファイルを添付することができますが、この機能について、少し補足説明をします。

Teamsでメッセージにファイルを「添付する」とは、該当する会話の[ファイル]タブにアップロードされたファイルをメッセージに紐付けるという意味になると理解した方がわかりやすいでしょう。
添付画面で[コンピュータからアップロード]を選択した場合も、自動的に[ファイル]タブにアップロードされ、メッセージとそのファイルが紐付けられます。

## 予定表の操作

「予定表」は、後述する会議機能を使用する際によく使われます。
予定表を開くには、Ctrl+5をおすか、アプリバーから予定表を選択してEnterキーを押します。

予定表の表示形式には、「日」、「週」、「稼働日」、「平日」など、いくつかの種類があります。
表示形式を変更する際は、Ctrl+F6を何度か押してカレンダー領域に移動した後、Shift+Tabを１回押します。
左右カーソルで「予定表ビュー」と読み上げられるところに移動後、Enterキーでメニューを開き、上下カーソルで目的の項目を選択してEnterキーを押します。

カレンダーの画面では、左右カーソルキーで日付、上下カーソルキーで時間を移動します。
また、Tab/Shift+Tabで、登録された予定の間を移動できます。
さらに後の予定を表示したり、以前の予定を表示したりするには、Ctrl+Alt+左右矢印を使用します。

## 会議機能を使う

Teamsには、会議を行う機能があります。
この機能は、複数人での通話や授業に活用できます。
なお、Teamsの会議は、特定のチャネルで行われることが多いですが、必ずしもチャネル上で行う必要はありません。

会議関係の操作は、[チーム]か[予定表]のいずれかの画面から実行できます。

### [チーム]から操作する場合

#### 新たな会議を開始する

会議を行いたいチャネルを開き、そのチャネル上ですぐに会議を始めることができます。
以下の操作は、既存のスレッドに対して返信する場合にも使用でき、その場合は、該当するスレッドで会議が開始されます。

メッセージを入力する編集エリアで、Tabキーを押すと「書式」ボタンがあります。
ここから、左右カーソルで、[今すぐ会議]ボタンを探し、Enterキーで実行します。
この操作により、簡単に会議を始めることができます。

なお、一つのチャネル上では複数の会議を開催できますが、一つのスレッドで行える会議は一つだけです。

#### 会議に参加する

チャネルのスレッド一覧で会議が行われているスレッドを選択すると、「ミートアップが進行中です」と通知されます。
Enterきーでこのスレッドを開くと、最上段に「会議中」と読み上げる部分があります。
ここでEnterキーを押すと、会議に参加するための[参加]ぼたんが表示されます。

[参加]ボタンを実行すると、マイクやカメラを有効にするのか、無効にするかを選択する画面が表示されます。
必要な設定が終わったら、[会議に参加]ボタンを実行します。

### [予定表]を使用する場合

[予定表]を使うと、あらかじめ会議の予定を設定して、参加者の出欠確認をした上で会議をすることができます。

#### 会議の予定を設定する

予定表を開き、カレンダーのエリアからShift+Tabを何度か押して、[新しい会議]ボタンに移動して実行します。
会議の予定を設定する画面が開きます。
各コントロールの間を移動するには、TabキーまたはShift+Tabキーを使用します。

- 最初に、この会議のタイトルを入力します。これは、予定表に表示されるため、わかりやすいタイトルを付けるようにしましょう。
- 次に、[必須出席者を追加]、[任意出席者を追加]という部分があります。チャネル上で会議を行うのでなく、手動でメンバーを追加したい場合には、ここで追加するユーザを設定します。
- 次に、会議の開始・終了日時を設定します。[終日]に設定することもできます。
- [繰り返し]機能を使用すると、毎週決まった時間に会議を行うなど、定期的な予定を設定できます。
- 次に、[チャネルを追加]があります。特定のチャネル上で会議を行いたい場合は、ここで設定します。上下カーソルキーでチームを選び、右カーソルキーで展開し、さらにそのチーム内のチャネルを選択します。最後にTabキーを押すと、設定が確定されます。
- その他、必要事項の設定が終わったら、Shift+Tabを何度か押して、[保存]ボタンを選択して実行します。

なお、チャネル上での会議を設定した場合は、自動的に新しいスレッドが作成され、「会議を予定」というメッセージが投稿されます。

#### 会議の予定を承諾・辞退する

自分が所属するチャネルで会議の予定が設定されると、自動的に予定表に予定が追加され、「会議出席依頼」として、メールが送信されます。
このとき、出席依頼を承諾するのか、辞退するのかを選択する必要があります。
この操作はOutlookからも行えますが、Teamsの予定表から返信することもできます。

予定表から会議を選択してEnterキーを押すと、会議の詳細が表示されます。
自動的に、フォーカスが出欠確認のボタンに移動します。
Enterキーでこのボタンを実行後、Tabキーで「承諾」や「辞退」などを選択してEnterキーで確定できます。
また、定期的な会議として設定されている場合は、今回の会議のみに返信するのか、今後行われる全ての会議に返信するのかを選択できます。

#### 会議に参加する

予定表から会議に参加するには、会議を選択してEnterキーを押します。
会議の詳細が表示され、Shift+Tabを何度か押すと、[参加]ボタンがあります。
このボタンを実行すると、マイクやカメラを有効にするのか、無効にするかを設定する画面になります。
適宜選択して[会議に参加]ボタンを実行すると、会議に参加できます。

なお、まだ会議が始まっておらず、自分が最初の参加社であった場合は、会議に参加した時点で会議が開始されます。
また、予定表に登録されている会議が始まると、通知音が再生されます。

## 会議・通話中の操作

会議中の画面と通話中の画面は、同じような構造になっています。
TabキーやShift+Tabキーで各コントロール間を移動できます。
また、会議に誰かが参加したり、会議から誰かが退出したりすると、そのことがスクリーンリーダーで読み上げられます。

また、会議・通話中にCtrl+数字キーを押すと、通常のTeamsの画面に戻ります。
また、この状態でも画面の一部に通話コントロールが表示されており、切断などの操作を行ったり、通話を開始した直後の画面に戻ったりできます。

キーボードで通話コントロールにアクセスする場合、表示されている画面によって、通話コントロールが表示される場所が変化します。
Ctrl+F6では通話コントロールに移動できません。
ほとんどの場合は、Ctrl+Eで検索ボックスに移動後、TabキーやShift+Tabキーを何度か押すことで、通話コントロールに移動できます。

### 会議の参加者を確認する

会議画面で[参加者を表示]ボタンを実行すると、現在誰が会議に参加しているかを確認できます。
このボタンを実行後、Tabキーを何度か押すと、参加者の一覧にフォーカスが移動します。
ここで上下カーソルキーを押すと、参加者の名前を順番に確認できます。
参加者の一覧を閉じるには、Shift+Tabキーを何度か押して、[右側のウインドーを閉じる]ボタンに移動して実行します。

また、この画面には、会議に参加していないメンバーの一覧もあります。
一覧から項目を選択し、アプリケーションキーかShift+F10を押すと、[会議への参加を依頼]という項目があります。
通常、会議が始まった際には着信音は鳴りませんが、これを実行することで、指定したメンバーにのみ着信音を鳴らすことができます。

## その他の役立つヒント

### Teamsのウインドーが操作できなくなったら

下記の問題は、Teamsの２０２０年５月２７日の更新で修正されました。
お困りの方は、最新版への更新をお試しください。

Windows+Mでデスクトップにフォーカスを移動した後、Alt+TabでTeamsに戻ってきた際など、Tabキーなどを押しても何も読み上げられず、操作できなくなることがあります。
私が試したところ、スクリーンリーダーとしてNVDAやJAWSを使用している際にこの現象が発生するようです。

このような状態になった際には、Alt+Spaceでシステムメニューを開き、[元のサイズに戻す]または[最大化]のうち、利用可能な方を実行すると、正常な状態に戻ります。
あるいは、下記の操作を行うことでも復旧できる場合があります。

1. Windows+上カーソルを押す。
2. Windows+下カーソルを押す。
3. 再度Windows+上カーソルを押す。

### コマンド検索

Teamsには沢山のコマンド（命令）が用意されており、基本的には各コマンドにキーボード操作が割り当てられています。
しかし、中には、キーボード操作が割り当てられていないコマンドもあります。
また、全ての操作を覚えるのは大変です。
そのような場合に活用できるのが、コマンド検索の機能です。

Teams上でCtrl+/（スラッシュ）を押すか、検索ボックス（Ctrl+E）に「/（スラッシュ）」を入力した後、キーワードを入力すると、コマンドを検索できます。
検索結果が表示されたら、下カーソルキーで順番に確認できます。
目的のコマンドが見つかったら、Enterキーで実行できます。

### キーボードショートカットの確認

TeamsのウインドーでCtrl+.（ピリオド）を押すと、Teamsで利用可能なショートカットキーの一覧が表示されます。
内容をスクリーンリーダーで読み上げさせるには、スクリーンリーダーのブラウザ読み上げコマンドを使用する必要があります。

### チャネルの新着メッセージを通知させる

チャネルに入った直後は、新着メッセージの通知は無効になっています。
重要なメッセージを見落とす可能性があるため、新たなチャネルに入った直後に、下記の設定を行うことをお勧めします。

1. チームのチャネル一覧で設定したいチャネルを選択し、Spaceキーを押します。
2. 上下カーソルキーで、[チャネルの通知]を選択してEnterキーを押します。
3. 通知を設定する画面が表示され、最初の項目である[このチャネルに投稿があるたびに通知する]にフォーカスが移動します。Spaceキーでメニューを開き、上下カーソルキーで[バナーとフィード]を選択してEnterキーを押します。
4. Tabキーで[全ての返信を含む]チェックボックスに移動して、Spaceキーでチェックします。
5. Tabキーで[保存]ボタンに移動して、SpaceキーまたはEnterキーで実行します。

以上の設定を行うことで、チャネルに投稿がある度に「Microsoft Teams通知」というウインドーが表示され、同時に通知音が再生されるようになります。

### Teamsの設定をする

Teamsの設定ダイアログを開くには、Ctrl+,（カンマ）を押します。
あるいは、ctrl+Eで検索ボックスに移動後、Tabキーを押してプロフィールボタンに移動し、Spaceキーで開くメニューから設定を選択することもできます。

設定画面は、複数のタブで構成されています。
設定画面を開いた直後は、タブを選択するコントロールにフォーカスがあり、[一般]タブが選択されています。
上下カーソルキーで目的のタブに移動後、Enterキーを押すと画面が切り替わります。
設定画面の各コントロールの間を移動するには、TabやShift+Tabを使用します。

例えば、[デバイス]タブでは、通話や会議に使用するカメラやマイクの設定ができます。
また、[通知]タブには、どのような場合に通知を表示させるか、通知音を再生するかといった設定があります。

変更した設定は、自動的に保存されます。
設定画面を閉じるには、[閉じる]ボタンを押すか、Escapeキーを押します。

### マイクの音量が勝手に変わってしまう現象について

Teamsで通話や会議を行った際、自動的にマイクのボリュームが変更されます。
通常は特に気にする必要はありませんが、ご使用のマイクによっては、ノイズなどが原因で音量が下がってしまうことがあります。

現在のところ、Teamsの設定には、音量の自動調整を無効化する設定は用意されていません。
しかし、どうしてもこの現象を回避したい場合は、 [ボリュームロッカー](https://www.vector.co.jp/soft/winnt/art/se476651.html) というソフトを使うことで、音量を一定に保つことができます。

## 参考資料

- [キーボードと音声による Microsoft Teams 基本操作ガイド](https://www.microsoft.com/ja-jp/enable/o365v.aspx)
- [Microsoft Teams でスクリーン リーダーを使用した基本的なタスク](https://support.office.com/ja-jp/article/microsoft-teams-%E3%81%A7%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3-%E3%83%AA%E3%83%BC%E3%83%80%E3%83%BC%E3%82%92%E4%BD%BF%E7%94%A8%E3%81%97%E3%81%9F%E5%9F%BA%E6%9C%AC%E7%9A%84%E3%81%AA%E3%82%BF%E3%82%B9%E3%82%AF-538a8741-f21b-4b04-b575-9df70ed4105d#picktab=windows)
- [An Introduction to Microsoft Teams and JAWS ? Freedom Scientific（英語）](https://www.freedomscientific.com/webinars/microsoft-teams-and-jaws/)

（以上）
