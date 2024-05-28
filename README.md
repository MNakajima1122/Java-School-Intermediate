# Java-School-Intermediate
TechPit_Javaスクール_中級総合問題

1.概要

ユーザー情報の一覧確認と、新規登録ができるアプリケーションです。

・ユーザー情報一覧画面:現在登録されているすべてのユーザー情報を一覧表示します

・ユーザー新規登録画面:ユーザー名、パスワード、メールアドレスを入力し、新規登録をします。パスワードはハッシュ化されて保存されます。

2.使用技術

・java ver21.0.2

・springframework.book version3.2.5

・spring.dependency-managment version1.1.4

・Gradle

・Spring Web

・Thymeleaf

・Lomback

・PostgreSQL Driver

・MySQL

・Mybatis

・Docker/Docker-compose

・A5:SQL Mk-2 SQL Client/ER Diagram tool

・VS code

3.構成

・UserRequest.java:ユーザー新規登録画面の入力を処理します。

・UserController.java:各画面の表示・遷移や、入力・出力処理など、リクエストに対する処理を呼び出します。

・UserService.java:UserController.javaに呼び出された指示を処理するインターフェース的な役割を持ちます。

・UserRepojitory.java:データベースとデータのやり取りをします。

・UserMapper.java:UserRepository.javaに呼び出されたメソッドを処理します。対応するUserMapper.xmlでSQLを定義します。

