# spring-boot-study
## 概要
本プロジェクトは、「Spring Boot2徹底活用」(以下教材)で取り扱われているサンプルプロジェクト(以下サンプル)  
https://github.com/miyabayt/spring-boot-doma2-sample  
を自社の学習用にコーディングし独自の改変を行ったもの。
上記URLのサンプル内のREADME.mdに、必要な環境構築方法や説明がほぼほぼ記載されている。 　

## 注意点
### ※学習を始める時点でいくつかの前提知識が求められる。
#### 必須(教材が開発初心者を対象にしていないため、どれか1つでも欠けると学習に大きく支障をきたす)
・Javaの初歩知識。Java Silver程度+JDBC等  
・DBの知識。MySQLの環境構築、初歩的なSQLの理解  
・Springの入門知識。udemyのspring入門の理解  
・IDEでの開発経験。環境構築、設定方法、エラー解析、デバッグetc  

#### 推奨
・Javaの基本文法知識(Java gold程度あればほとんどのクラスはすぐ理解できる)  
・gitの基礎知識(学習者が各々のブランチでプロジェクトを管理できるようになる)  
その他詳細な知識は各モジュールのドキュメントに記載しているので参照すること。  

### ※通常の研修やプログラミング教材とは進め方が異なる。  
・膨大なサンプルを見ればわかるが、単独で作業できる範囲を遥かに超えている。  
・教材に記載されているコードは全体から見て相当少ない。  
・Springの機能やクラスの役割などの解説もかなりカットされている。  
以上の観点から、教材の内容の学習以前に、どのように学習を進めていくかを学習者本人が試行錯誤する必要がある。  

### ※本プロジェクトはサンプルの機能を一部カットしてある。メイン機能は現時点で以下の通り。
ユーザ管理機能、ファイル操作機能、セキュリティ機能、メール機能  

### 差分
・サンプルと本プロジェクトには差分がある。差分点、変更理由などは各クラスにコメントを残してある。  

## 品質管理  
試験を手動で実施して、テスト結果を社内サーバに置いている。  
テスト項目書、マトリクス共に個人で作成していてレビューを通していないので、ミスやパターン漏れ抜れの可能性がある。  
気付いた場合は学習者の追記、修正を推奨。  
商用開発ではないのであまり厳しめには実施していない。
