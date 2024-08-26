# ブログ作成(テスト用)
Wordpress Github Pagesで作った、技術ブログ。  

無料で簡単に作成できる点が良い

<img width="1344" alt="スクリーンショット 2024-07-01 2 24 15" src="https://github.com/iwatanabee/test-blog/assets/83575309/d79203b4-37eb-4574-b648-226a0bca1ec7">  

<img width="1344" alt="スクリーンショット 2024-07-01 2 24 33" src="https://github.com/iwatanabee/test-blog/assets/83575309/8370769a-a37c-45fe-a454-a04579dc7ca3">

<img width="1343" alt="スクリーンショット 2024-07-01 2 24 56" src="https://github.com/iwatanabee/test-blog/assets/83575309/6a5491ed-9767-4198-9d17-93cb11ecd251">


## デプロイするときに気をつけること
・ github pages が対応しているWordpressのテーマを使って制作しないと、デプロイできない。　　
Wordpress　「github pages」で対応しているテーマでブログを作成→wordpressのプラグインの「Simply Static」で静的化→デプロイ　　
 
・ Simply Static のURLを「https://iwatanabee.github.io/」にする
・ https://web.skipjack.tokyo/php/xampp-ssl/ ssl化を行う
・ カテゴリーなどのURL設定を半角英数字にしないとURLがおかしくなるので、Simply static で静的化した時に文字化けが起こる
![image](https://github.com/user-attachments/assets/35ab2b54-f20f-4a38-82ee-1f7190a9748e)
・文字化け対策で以下のことをやる
![image](https://github.com/user-attachments/assets/e646fb48-e02d-4519-baf7-6c6e2cfa1bb7)



<img width="750" alt="スクリーンショット 2024-08-10 2 29 10" src="https://github.com/user-attachments/assets/76983d24-5844-4d61-9815-7361dc40257c">

<img width="733" alt="スクリーンショット 2024-08-10 2 29 30" src="https://github.com/user-attachments/assets/99c69182-150b-452d-86db-f549cb60c79a">

・サイトマップを作成する
github pagesでデプロイしたホームページはURLからはアクセス可能だが、検索しても出てこないので、Googleに申請しなくてはいけない
Google serch console で申請をする  
![image](https://github.com/user-attachments/assets/39e31b1b-6170-484f-a7ae-5493e1faff99)
