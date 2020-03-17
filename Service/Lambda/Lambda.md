# Lambda

## Table of Contents
<!--toc-->
* [Abstruct](#abstruct)

* [Function](#function)
  * [対応言語](#対応言語)
  * [handler名について](#handler名について)
  * [Test](#test)
* [VPC Lambda](#vpc-lambda)
  * [Security Group](#security-group)
* [Layer](#layer)
* [Reference](#reference)
<!--toc-->

## Abstruct


## Function
### 対応言語
```
Python, C#, JAVA, Node.js, Ruby etc.
```
Lambda関数がトリガーされた際に、実際に実行する処理を記載。
handlerが実際に実行するメイン処理。

### handler名について
Pythonの場合
ファイル名.メソッド名


### Test
test button
Lambdaのインスタンスが立ち上げ直されるようだ。

## VPC Lambda
Lambda関数をVPC内に配置する場合



### Security Group
inbound: all Deny(default)
で問題ない。

## Layer
複数のLambda関数で同じライブラリを別々に読み込んでいる際に、まとめて1箇所から読むのに使用。

## Reference




