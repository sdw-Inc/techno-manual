---
layout: default
title: 出荷伝票出力
parent: 出荷伝票
grand_parent: 出荷管理
nav_order: 2
has_children: false
---

# 出荷伝票出力

<br>

1. [品質管理システム]トップ画面から「出荷伝票」を選択します。

    <table><tr><td>
    <img src="../../../../assets/images/shipment-control/shipping-slip/pdf-slip/1.png" width="70%">
    </td></tr></table>

1. [出荷伝票用 製品一覧]で製品を絞り込んでチェックボックスにチェックを入れ、「出荷伝票作成」をクリックします。

    <table><tr><td>
    <img src="../../../../assets/images/shipment-control/shipping-slip/pdf-slip/2.png" width="90%">
    </td></tr></table>

    「出荷伝票作成」クリック時に以下の条件に当てはまる場合、確認/エラーメッセージを表示します。
     - 納品日がすでに入力済の製品を選択 → <span style="color:rgb(255, 188, 2); ">**確認メッセージ**</span>
     - 10件を超える製品を選択 → <span style="color:rgb(255, 0, 0); ">**エラーメッセージ**</span>
     - 複数の異なる部位を選択 → <span style="color:rgb(255, 0, 0); ">**エラーメッセージ**</span>

1. 出荷伝票に記載する項目を入力し、「プレビュー」をクリックします。

    <table><tr><td>
    <img src="../../../../assets/images/shipment-control/shipping-slip/pdf-slip/3.png" width="60%">
    </td></tr></table>

    {: .warning }
    納品日の入力は必須となります。
    

1. 「pdf保存/反映」クリックで選択した製品の完了表印刷を行います。

    <table><tr><td>
    <img src="../../../../assets/images/shipment-control/shipping-slip/pdf-slip/4.png" width="65%">
    </td></tr></table>

    {: .note }
    「pdf保存/反映」をクリックしたタイミングで、設定した[納品日]が製品マスタの[納品日]に自動で反映されます。

    <table><tr><td>
    <img src="../../../../assets/images/shipment-control/shipping-slip/pdf-slip/5.png" width="90%">
    </td></tr></table>

    出荷伝票内容

    <span style="color: #ff1493; ">①</span> 物件マスタ：正式名称  
    <span style="color: #ff1493; ">②</span> 設定した車番  
    <span style="color: #ff1493; ">③</span> 設定した号車  
    <span style="color: #ff1493; ">④</span> 設定した出荷検査日  
    <span style="color: #ff1493; ">⑤</span> 設定した担当印  
    <span style="color: #ff1493; ">⑥</span> 製品マスタ：部位名称(作業所様控は表示なし)  
    <span style="color: #ff1493; ">⑦</span> 製品マスタ：製品番号  
    <span style="color: #ff1493; ">⑧</span> 製品マスタ：打設日  
    <span style="color: #ff1493; ">⑨</span> 製品が表示されている行に○  
    <span style="color: #ff1493; ">⑩</span> 設定した納品日

* * *

## 物件検索プルダウン表示順変更

<br>

物件に紐づく全製品が下記の条件を満たす場合、検索プルダウンで該当の物件を末尾に表示します。
- 納品日入力済 & 納品日＞現在日付 or 廃棄日入力済

<table><tr><td>
<img src="../../../../assets/images/shipment-control/shipping-slip/pdf-slip/6.png" width="100%">
</td></tr></table>