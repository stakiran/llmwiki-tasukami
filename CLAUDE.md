# Tasukami Wiki
**LLM Wiki** とは、LLM につくらせた Wiki である。今回は Kerpathy の LLM Wiki をベースとする。

raw として拙作 **タスク管理を噛み砕く** の原稿を入れている。略称は **たすかみ**。ここから LLM Wiki をつくる。これを **Tasukami Wiki** と名付ける。このリポジトリの目的は、Tasukami Wiki として何をつくれるかを模索することである。

## ディレクトリ構成
- raw/
    - たすかみの原稿を入れている
- wXX/
    - Tasukami Wiki が構築される
    - w1、w2、……のように複数つくることを想定する
- riw/
    - LLM に生成させたコンテンツを保存する
    - Tasukami Wiki、また LLM Wiki とは無関係である
    - 勝手に読み込むな。読み書きが必要な場合はこちらから指示する

## 現在のモード

```yaml
current_mode: "w1"
```
