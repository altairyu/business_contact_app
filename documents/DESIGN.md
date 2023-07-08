<details>

<summary><h2>業務フロー図</h2></summary>


- 暫定版

![業務フロー図MVP版](images/flow_chart.png)

</details>

<details>

<summary><h2>画面遷移図</h2></summary>

- 暫定版

![画面遷移図](images/screen_transition.png)

</details>

<details>

<summary><h2>ワイヤーフレーム</h2></summary>

- 暫定版

<details>
<summary><h3>ログイン画面</h3></summary>

![ログイン画面](images/login.png)

</details>

<details>
<summary><h3>定型文・送信パターン一覧画面</h3></summary>

![定型文・送信パターン一覧画面](images/message_list.png)

</details>

<details>
    
<summary><h3>定型文新規作成画面</h3></summary>

![定型文新規作成画面](images/create_sentence.png)

</details>

<details>

<summary><h3>定型文編集画面</h3></summary>

![定型文編集画面](images/update_sentence.png)

</details>

<details>

<summary><h3>送信パターン新規作成画面</h3></summary>

![送信パターン新規作成画面](images/create_transmission_pattern.png)

</details>

<details>
    
<summary><h3>送信パターン編集作成画面</h3></summary>

![送信パターン編集画面](images/update_transmission_pattern.png)

</details>


</details>


<details>

<summary><h2>テーブル設計</h2></summary>


※ コア機能分のみ。適宜アップデートします。


<details>

<summary><h3>テーブル：template_messages</h3></summary>

| カラム名    | データ型         | NULL | キー      | 初期値 | AUTO INCREMENT |
|---------|--------------|----|---------|-----|----------------|
| id      | BIGINT       | NO | PRIMARY |     | YES            |
| name    | VARCHAR(255) | NO |         |     |                |
| message | TEXT         | NO |         |     |                |

</details>

</details>



<details>

<summary><h2>システム構成図</h2></summary>

- 暫定版

![システム構成図](images/infrastructure_configuration_diagram.png)

</details>
