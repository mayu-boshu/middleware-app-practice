# middleware-app-practice

## 概要

COACHTECH 教材 Tutorial 10-2「ミドルウェア ハンズオン演習」で作成した成果物です。
カスタムミドルウェアを使って、管理者のみアクセスできる「管理者専用ページ」を保護します

## 使用技術

- PHP 8.x
- Laravel 10.x
- カスタムミドルウェア
- Laravel Fortify（認証）

## 学んだこと

- ミドルウェアの仕組み
- ミドルウェア作成と Kernel.php での登録
- ルートへのミドルウェア適用方法

## 動作確認

管理者でログインして確認：

❶http://localhost にアクセス
❷admin@example.com / password でログイン
❸「管理者ページにアクセス」をクリック
→ 管理者ページが表示されれば成功です！

一般ユーザーでログインして確認：

①ログアウト
②user@example.com / password でログイン
③「管理者ページにアクセス」をクリック
→ 403エラーが表示されれば成功です！
