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
     </body>
     </html>

    #include <stdio.h>
    void main() {
    int a[5] = {10, 20, 30, 40, 50};
    int b;
    int *p;

    p = &a[0];
    printf("配列Aの先頭のアドレスは%pです\n", p);
    printf("はじめにPの指している値は%dです\n", *p);

    p+=2;
    printf("ここでPの指している値は%dです\n", *p);

    printf("bの中身は%dです\n", a[1]);

    b = *(p-1);
    printf("bの中身は%dです\n", b);
    }
