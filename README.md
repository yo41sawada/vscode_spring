# ABOUT THIS REPOSITORY
Visual Studio Code で Spring 開発を行うことを検証するリポジトリです。

# 環境・前提条件
- macOS
  - Monterey：12.0.1（21A559）
  - Apple M1 Pro
- Java：OpenJDK 11.0.14
- Maven：3.8.5
- Visual Studio Code
  - Extension Pack for Java
    - Language support for Java (TM) by Red Hat
    - Debugger for Java
    - Test Runner for Java
    - Maven for Java
    - Project Manager for Java
    - IntelliCode
  - Spring Boot Extention Pack
    - Spring Initializr Java Support
    - Spring Boot Tools
    - Spring Boot Dashboard  

# コンパイル
- Visual Studio Code の設定
- Maven を用いる場合

# 実行
## 通常の実行
DemoApplication.java を開き、main メソッド付近に表示されている Run を押下

## Maven コマンドから実行
```
mvn spring-boot:run
```

## Maven で作成した実行可能 jar から実行
```
java -jar ./demo/target/java -jar demo-1.0-SNAPSHOT.jar
```