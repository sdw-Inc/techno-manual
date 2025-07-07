---
layout: default
title: 打設期限マスタ
parent: 事前設定
grand_parent: 工程管理
nav_order: 4
has_children: false
---

# 打設期限マスタ

目次  
- [概要](#概要)   
- [インポート](#インポート)    
- [手動登録・更新](#手動登録更新)  
- [エクスポート](#エクスポート)  

* * *

## 概要
設定することで、打設期限をWEB工程表上に表示することができます。  
打設期限マスタは、以下の条件が一致する製品マスタと紐付き、  
内容が更新されるたびに紐づく製品マスタの[建方想定日]、[打設期限]の値を自動更新します。  

- 打設期限マスタと製品マスタの[物件コード]が同一  
- 打設期限マスタと製品マスタの[建方区分]が同一
<br>
<br>

* * *

## インポート

1. 下記リンクから、打設期限データを入力するエクセルファイルをダウンロードします。  
    [Excelファイルダウンロード](../../../../assets/files/process-control/pre-configuration/registration-pouring/pouringMst_format.xlsx "other type of attachments")

    {: .warning }
    ヘッダー名はインポート時の照合に使われているため、変更しないようお願いします。

    <table><tr><td>
    <img src="../../../../assets/images/process-control/pre-configuration/registration-pouring/1.png" width="65%">
    </td></tr></table>

1. エクセルファイルのフォーマットに沿って、登録したい任意の値を入力します。

    <table><tr><td>
    <img src="../../../../assets/images/process-control/pre-configuration/registration-pouring/2.png" width="65%">
    </td></tr></table>

1. [基幹システム]TOP画面から「打設期限」をクリックし、[打設期限一覧]画面に遷移します。

    <table><tr><td>
    <img src="../../../../assets/images/process-control/pre-configuration/registration-pouring/3.png" width="75%">
    </td></tr></table>

1. 画面右上の「エクセルインポート」をクリックし、インポートするファイルを選択します。

    <table><tr><td>
    <img src="../../../../assets/images/process-control/pre-configuration/registration-pouring/4.png" width="70%">
    </td></tr></table>

    <table><tr><td>
    <img src="../../../../assets/images/process-control/pre-configuration/registration-pouring/5.png" width="70%">
    </td></tr></table>

1. [インポート順の設定]で以下の設定を確認し「インポート」をクリックします。  
    2回目以降は設定が記憶されるため、設定を変更せずにインポート可能です。  
    <br>

    【初回】  
    ① 1/xxx  
    ② 「フィールド名として使用」  
    ③ 「照合名順」  


    【二回目以降の表示】  
    ① 2/xxx  
    ② 「データ」  
    ③ 「照合名順」  

    <table><tr><td>
    <img src="../../../../assets/images/process-control/pre-configuration/registration-pouring/6.png" width="90%">
    </td></tr></table>

1. [打設期限インポート確認]画面で内容を確認し、問題なければ「インポート」をクリックします。  

    インポートステータスは以下の通りです。

    <table><tr><td>
    <img src="../../../../assets/images/process-control/pre-configuration/registration-pouring/7.png" width="80%">
    </td></tr></table>

    <table><tr><td>
    <img src="../../../../assets/images/process-control/pre-configuration/registration-pouring/8.png" width="95%">
    </td></tr></table>

1. [打設期限一覧]画面にインポートした打設期限が表示されます。

    <table><tr><td>
    <img src="../../../../assets/images/process-control/pre-configuration/registration-pouring/9.png" width="85%">
    </td></tr></table>

<br>

* * *

## 手動登録・更新

1. [打設期限一覧]画面の「新規」をクリックします。

    <table><tr><td>
    <img src="../../../../assets/images/process-control/pre-configuration/registration-pouring/10.png" width="80%">
    </td></tr></table>


1. 登録したい物件名称を選択して「作成」をクリックします。

    <table><tr><td>
    <img src="../../../../assets/images/process-control/pre-configuration/registration-pouring/11.png" width="80%">
    </td></tr></table>

1. 登録・更新したい内容を手動入力します。

    <table><tr><td>
    <img src="../../../../assets/images/process-control/pre-configuration/registration-pouring/12.png" width="80%">
    </td></tr></table>

<br>

* * *

## エクスポート

1. エクスポートしたいデータを検索で絞り込みます。

    <table><tr><td>
    <img src="../../../../assets/images/process-control/pre-configuration/registration-pouring/13.png" width="80%">
    </td></tr></table>


1. 「エクスポート」をクリックし、ファイル名を指定して「OK」をクリックします。

    <table><tr><td>
    <img src="../../../../assets/images/process-control/pre-configuration/registration-pouring/14.png" width="80%">
    </td></tr></table>

1. 出力先を選択して「保存」をクリックします。

    <table><tr><td>
    <img src="../../../../assets/images/process-control/pre-configuration/registration-pouring/15.png" width="75%">
    </td></tr></table>

1. 打設期限マスタをExcel形式でエクスポートすることができます。

    <table><tr><td>
    <img src="../../../../assets/images/process-control/pre-configuration/registration-pouring/16.png" width="80%">
    </td></tr></table>