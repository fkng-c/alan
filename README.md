  <!DOCTYPE html>
  <html>
  <head>
   <title>Alan</title>
  </head>
  <body>
    <h1 class="blue-text">自己紹介</h1>
    <ul>
      <li>名前；Alan</li>
      <li>年齢；１８</li>
      <li>好きな食べ物；酢豚</li>
    </ul>
    
    <hr>
    <h1 class="blue-text">好きなことについて</h1>
    <h3>音楽</h3>
    <p>EDMが好きです。大人になった頃、フェスに行ってみたいです。</p>
    <h3>ゲーム</h3>
    <p>主にパズドラと荒野行動をプレイしています。一緒に遊びましょう！</p>
    <h3></h3>
    <p></p>
    <h3></h3>
    <p></p>
    
    <footer>
    <a href="https://twitter.com/eemmbab">Alanのツイッター</a>
    </footer>
  
    <form>
    <div class="form-item">内容</div>
    <textarea name="body"></textarea>
    <input type="submit" value="送信">
    </form>
    
    <?php
    echo $_POST['body'];
    ?>
    </body>
    </html>
