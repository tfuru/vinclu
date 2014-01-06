vinclu

実装サンプル
http://jsdo.it/t_furu/iP0O

======

    // jqery ライブラリの読み込み
    <script type="text/javascript" src="http://code.jquery.com/jquery.js"></script>
    // LED ライブラリの読み込み
    <script type="text/javascript" src="vinclu_led.js"></script>
    
    <script type="text/javascript">
    // 点灯
    led1 = new VincluLed(100,100);
    //Blink開始 穏やかに瞬く
    led1.blinkOn(200);
    //Blink停止
    led1.blinkOff();
    </script>

======
