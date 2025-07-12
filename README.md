# RoboSoccer-Referee-Board

ロボサッカーの審判用ボードと、集計用のwebアプリです。
通信については、それぞれのsetting画面を開き、
honbu.html側で、mySDP copyボタンを押し、sdpをshinpan.htmlの「相手の...」と書かれているところに貼り付ける。
次にshinpan.html側のmySDP copyボタンを押し、sdpをhonbu.htmlの「相手の...」と書かれているところに貼り付ける。
これで(不具合が起きなければ)接続が完了します。
この状態で審判をすると、結果がhonbu.htmlに送られ、対戦相手を決め、また、ランキングをつけれます。(勝利したら1点同点なら両方に0.5点)
