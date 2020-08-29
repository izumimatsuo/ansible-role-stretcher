# ansible-role-stretcher [![Build Status](https://travis-ci.org/izumimatsuo/ansible-role-stretcher.svg?branch=master)](https://travis-ci.org/izumimatsuo/ansible-role-stretcher)

CentOS 7 に stretcher を導入する ansible role です。

## 主な仕様

- インスタンス起動時に、指定したManifestファイルでデプロイ実行
- consulが導入されていたら、デプロイイベントのwatchを実行

## 設定項目

以下の設定項目は上書き可能。

| 項目名                     | デフォルト値| 説明                             |
| -------------------------- | ----------- | -------------------------------- |
| stretcher_autorun_manifest | none        | 自動起動させる Manifest ファイル |

