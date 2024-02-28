# Stargazing Calculator

LANGUAGE: JAPANESE

### [ダウンロードする](https://github.com/mahiromiyake/stargazing/releases)

## 概要
ローカルバージョンのStargazing Calculatorは、アプリを開くとコンソールが表示され、同時にブラウザが開いてローカルサーバへアクセスされます。
GUIは[Webバージョン](https://www.skycluster.jp/stargazing)の見た目とほぼ同じで、同じように操作できます。

## インストール方法
アプリケーションは、上記のリンクからダウンロード、インストールしてください。  
実行にはPythonと２つの外部ライブラリのインストールが必要です。以下の手順に従ってください。  
[1] [Pythonをインストールする](https://www.python.org/downloads/)  
[2] ライブラリをインストールする  
以下のコマンドをターミナルに打ち込んでください。  

`pip install Flask pyephem`

## ローカルサーバ停止方法
ブラウザを閉じただけでは、ローカルサーバを停止することはできません。  
使用後は、**コンソールを閉じる**ことで停止できます。
