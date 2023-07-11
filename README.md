# Book_NotNet6
.NET 6　プログラミング入門

+ URL https://bookplus.nikkei.com/atcl/catalog/22/04/24/00112/

## 目次

### 第一章 .NET6の仕組み

#### 1.1 .NETの始まり
+ 1.1.1. .NET Frameworkの歴史
+ 1.1.2. .NET 共通言語ランタイム(CLR)
+ 1.1.3. .NET Coreの歴史
+ 1.1.4. .NET Standardの歴史

#### 1.2 環境依存を超える .NETランタイム
1.2.1. プログラムの動作環境
1.2.2. 共通中間言語(IL)
1.2.3. プログラム言語による記述の違い
1.2.4. 中間言語を逆アセンブル

#### 1.3 .NETならではのテクニック
1.3.1. リフレクション
1.3.2. 属性
1.3.3. T4
1.3.4. ジェネリック
1.3.5. ildasm

### 第二章 .NET6の開発環境

#### 2.1 Visual Studio 2022
+ 省略

#### 2.2 Visual Studio Code
+ 省略

#### 2.3 Visual Studio for Mac
+ 省略

#### 2.4 dotnetコマンド
2.4.1. .NET SDKのダウンロード
2.4.2. dotnetコマンドの情報
2.4.3. .NETランタイムの切り替え
2.4.4. .NETランタイムの場所(Windows)
2.4.5. .NETランタイムの場所(Linux)
2.4.6. そのほかの.NETランタイム

#### 2.5 dotnet-efパッケージ
2.5.1. dotnet toolでのインストール
2.5.2. ローカル環境へのインストール
2.5.3. dotnet efコマンドの確認

### 第三章 WindowsフォームとWPF

#### 3.1 Windowsフォームアプリケーション
3.1.1. デスクトップアプリケーション
3.1.2. フォームデザイナー
3.1.3. フォームのコードビハイド
3.1.4. コントロールのウィンドウハンドルと名前
3.1.5. コントロールの動的なデザイン
3.1.6. コントロールのイベント処理
3.1.7. Win32 APIの利用
3.1.8. .NETでのウィンドウハンドルの利用

#### 3.2 WPFアプリケーション
3.2.1. XAML
3.2.2. XAMLのイベント記述
3.2.3. WPFのデザインとXAMLのロード
3.2.4. WPFアプリケーションの実行
3.2.5. XAMLとMVVMパターン
3.2.6. Prismパッケージの利用
3.2.7. Prismを利用したアプリの実行
3.2.8. .NET6でのデスクトップ環境

#### 3.3 Windowsフォームのコントロール
3.3.1. ユーザーコントロールの作成
3.3.2. Windowsフォームコントロールのプロジェクト
3.3.3. ユーザーコントロールとカスタムコントロールの違い
3.3.4. テストプロジェクトの作成
3.3.5. ユーザーコントロールのクラス定義
3.3.6. テストフォームのコード

#### 3.4 WPFのコントロール
3.4.1. WPFユーザーコントロールの作成
3.4.2. WPFユーザーコントロールのXAML
3.4.3. テストプロジェクトの作成
3.4.4. WPFユーザーコントロールのデザイン
3.4.5. WPFアプリケーションのデザイン
3.4.6. 状況依存プロパティの作成
3.4.7. MVVMパターンの活用

#### 3.5 .NET MAUIアプリケーション
3.5.1. .NET MAUIとは
3.5.2. MAUIアプリケーションの作成
3.5.3. XAMLの記述
3.5.4. MAUIアプリケーションの実行

### 第四章 ASP.NET MVCとWeb API

#### 4.1 Webアプリケーション
4.1.1. MVCパターンのWebアプリケーション
4.1.2. ASP.NET Core Webアプリ
4.1.3. Webアプリケーションの実行
4.1.4. Webページの構造

#### 4.2 ASP.NET MVCアプリケーション
4.2.1. MVCパターン
4.2.2. ASP.NET Core Webアプリ
4.2.3. Modelクラスの作成

#### 4.3 スキャフォードの利用
4.3.1. スキャフォードの作成
4.3.2. Entity Frameworkパッケージ
4.3.3. CURDアクセス
4.3.4. コントローラークラスとビュー
4.3.5. ブラウザでの表示

#### 4.4 Web API
4.4.1. Web APIのレスポンス
4.4.2. Web APIプロジェクトの作成
4.4.3. APIコントローラーの作成
4.4.4. Swegger
4.4.5. Postman

#### 4.5 Web API (DB編)
4.5.1. Entity Frameworkパッケージのインストール
4.5.2. モデルクラスの作成
4.5.3. コントローラークラスの作成
4.5.4. ルーティング設定

#### 4.6 Web APIとReact
4.6.1. シングルページアプリケーション
4.6.2. reactプロジェクトの作成
4.6.3. reactプロジェクトのホスティング
4.6.4. 一覧ページを追加
4.6.5. Reactの実行

#### 4.7 gRPC
4.7.1. gRPCとは
4.7.2. .protoファイルの作成
4.7.3. gRPCサーバーサイド
4.7.4. gRPCクライアントサイド
4.7.5. grpcuiの利用
4.7.6. Reactからの呼び出し

### 第五章 Entity Framework

#### 5.1 Entity Frameworkの使いどころ
5.1.1. LINQの活用
5.1.2. メソッド呼び出し
5.1.3. クエリの分割
5.1.4. LINQ記法

#### 5.2 SQL Serverに接続
5.2.1. Microsoft.EntityFrameworkCore.SqlServerパッケージ
5.2.2. WordPressのテーブルを活用
5.2.3. モデルクラスの作成
5.2.4. スキャフォールディングアイテムの作成
5.2.5. 応答されるJSON形式のデータ
5.2.6. SaveChangesAsyncメソッド

#### 5.3 MySQLに接続
5.3.1. MySql.EntityFrameworkCoreパッケージ
5.3.2. モデルクラスの修正
5.3.3. 接続文字列を環境変数から取得
5.3.4. MySQL版の実行

#### 5.4 SQLiteに接続
5.4.1. Microsoft.EntityFrameworkCore.Sqliteパッケージ
5.4.2. SQLite用のテーブル作成
5.4.3. 接続文字列の設定
5.4.4. データベースのファイルの場所

#### 5.5 LINQの使い方
5.5.1. InMemoryの利用
5.5.2. DbContextクラスの記述
5.5.3. エンティティクラスの記述
5.5.4. テストプロジェクトの利用
5.5.5. 初期データの作成
5.5.6. 一覧取得
5.5.7. 付属データを同時に取得
5.5.8. 条件に変数を利用
5.5.9. 条件に文字列を利用
5.5.10. ソート機能
5.5.11. 内部結合と外部結合
5.5.12. 集計関数の利用

#### 5.6 SQLの直接実行
5.6.1. データコンテキストの準備
5.6.2. データベース接続
5.6.3. 一覧取得
5.6.4. 付属情報を内部結合で取得
5.6.5. 条件の設定
5.6.6. 外部結合と集計関数の利用

#### 5.7 コードファーストの利用
5.7.1. SQL Serverの接続クラス
5.7.2. エンティティクラス
5.7.3. パッケージマネージャーコンソール
5.7.4. Add-Migrationコマンド
5.7.5. Update-Databaseコマンド

### 第六章 Blazer

#### 6.1 Blazorのクライアントアプリ
6.1.1. シングルページアプリケーション(SPA)
6.1.2. Blazeor WebAssemblyアプリの作成
6.1.3. WebAssemblyアプリの起動
6.1.4. blazor.webassembly.jsの読み込み
6.1.5. ロード対象のアセンブリ
6.1.6. Counter.razorの動作
6.1.7. Counter.razorのコードコンバート
6.1.8. ナビゲーションの表示

#### 6.2 Blazorコンポーネント
6.2.1. Blazorコンポーネントの追加
6.2.2. Blazorコンポーネントのコード
6.2.3. バインディング

#### 6.3 Razor記法
6.3.1. @を使った記法
6.3.2. @codeを使った記法
6.3.3. @ifや@foreach
6.3.4. そのほかのRazor記法

#### 6.4 Blazorのサーバーアプリ
6.4.1. 2つのBlazorアプリケーションの違い
6.4.2. Blazorサーバーアプリの作成
6.4.3. Blazorサーバーアプリのホスト
6.4.4. Blazorアプリケーションの互換性

#### 6.5 ログ出力の違い
6.5.1. コンソール出力の記述
6.5.2. WebAssemblyアプリでの出力
6.5.3. サーバーアプリでの出力

#### 6.6 データベースへの接続
6.6.1. Blazorサーバーアプリでデータの読み込み
6.6.2. LINQの利用

#### 6.7 dotnetコマンドでプロジェクト作成
6.7.1. dotnetコマンドのプロジェクトテンプレート
6.7.2. blazorwasm
6.7.3. blazorserver

#### 6.8 メニューにないBlazorアプリ
6.8.1. App.razorの変更
6.8.2. メニューにないBlazor
6.8.3. Appの表示位置

### 第七章 Azure

#### 7.1 Webアプリ
7.1.1. Webアプリケーションのサービス方法
7.1.2. Webアプリの作成
7.1.3. GitHubへ登録
7.1.4. デプロイ先のApp Service
7.1.5. 同期の実行

#### 7.2 Azure Functions
7.2.1. Azure Functionsの利点
7.2.2. WebHook Httpトリガー
7.2.3. WebHook Httpトリガー(データベース接続)
7.2.4. タイマートリガー
7.2.5. Cosmos DBトリガー
7.2.6. BLOBストレージのトリガー

### 第八章 Linux環境

#### 8.1 Linux環境
8.1.1. Ubuntu環境
8.1.2. 署名のインストール
8.1.3. .NET6 SDKのインストール
8.1.4. インストール先の確認
8.1.5. .NETのバージョン確認

#### 8.2 Raspberry Pi環境
8.2.1. Raspberry Piの用途
8.2.2. インストールスクリプトの実行
8.2.3. 環境変数の設定
8.2.4. infoスイッチで確認

#### 8.3 Nginxの利用
8.3.1. Nginxのインストール
8.3.2. ファイアウォールの設定
8.3.3. リバースプロキシの設定
8.3.4. Nginxの起動


### 第九章 モバイル開発

#### 9.1 .NET MAUIとは
9.1.1. マルチプラットフォームフレームワーク
9.1.2. 2つのアプリの同時開発
9.1.3. UIを共通化
9.1.4. 動作プラットフォームのための記述
9.1.5. dotnetコマンド

#### 9.2 MAUIプロジェクトの作成と実行
9.2.1 .NET MAUIプロジェクトの作成
9.2.2 Androidシミュレーターで実行する
9.2.3. iOSシミュレーターで実行する
9.2.4. ラベルを追加する
9.2.5. ボタンを追加する

#### 9.3 MVVMパターンを使う
9.3.1. Prism.Coreパッケージの利用
9.3.2. MVVMパターンの実行

#### 9.4 Web APIを呼び出す
9.4.1. モバイル環境でのデータ通信
9.4.2. HttpClientクラス
9.4.3. Web APIサーバーへの接続

索引

