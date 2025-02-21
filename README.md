# ハンズオン Maven プロジェクト

このプロジェクトは、Maven を使用して Java アプリケーションをビルドおよび実行する方法を学ぶためのハンズオンガイドです。

## 必要条件

- Java 11
- Maven 3.x
- Docker

## ビルド手順

1. プロジェクトをクローンします。
    ```sh
    git clone https://github.com/timeless-residents/handson-maven.git
    cd handson-maven
    ```

2. Maven を使用してプロジェクトをビルドします。
    ```sh
    mvn clean package
    ```

3. Docker イメージをビルドします。
    ```sh
    docker build -t handson-maven .
    ```

## 実行手順

1. Docker コンテナを起動します。
    ```sh
    docker run -p 8080:8080 handson-maven
    ```

2. ブラウザで `http://localhost:8080` にアクセスしてアプリケーションを確認します。

## ライセンス

このプロジェクトは MIT ライセンスの下でライセンスされています。
