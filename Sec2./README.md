# Sec. 2 : Swift

この章では、プロジェクト作成モードの、Single View Applicationテンプレートを用いて一歩ずつSwiftについて勉強していきます。
まずは、以下の設定で新しいプロジェクトを作成しましょう。

## プロジェクトの作成

| Project Name  | Team          | Organiztion Name    | Organization Identifier  | Language | Devices   |
| :-----------: |:-------------:| :------------------:| :-----------------------:| :-------:| :--------:|
| TestApp       | 任意(Ex; MRSK) | 任意(Ex; MRSK, Inc.)| 任意(Ex; jp.mrsk)         | Swift    | Universal | 

※Organization Identifierは慣例的に、逆DNS形式をとるようです。

## ViewController.swiftを選択

プロジェクトを作成すると、アプリ開発に最低限必要なファイルが自動的に生成されます。
生成されたファイルは、Xcodeの画面の左側のナビゲータエリア（下図）で確認できます。

<img src="https://cloud.githubusercontent.com/assets/28682101/26484800/15fa5f0e-422f-11e7-9496-dcdfd1be57ab.png" width="400">

ナビゲータエリアから、ViewController.swiftを選択してください。

このファイルには、viewDidLoad()とdidReceiveMemoryWarning()という２つの関数(func)が最初から定義されています。

viewDidLoad()はアプリ画面の読み込みが終了した後に、自動的に実行される部分です。この関数にテストコードを書き込んでいくことにします。


# 目次
 
 - #### 2-1. 基本 
 - #### 2-2. 関数
 - #### 2-3. ストリング 
 - #### 2-4. 配列 
 - #### 2-5. 辞書 
 - #### 2-6. 集合 
 - #### 2-7. オプショナル 
 - #### 2-8. クラス 
 - #### 2-9. 構造体 
