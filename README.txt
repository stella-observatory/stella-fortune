星々と月の占い（GitHub Pages 公開用・軽量版）

1. ZIPを解凍してください。
2. GitHub の stella-fortune リポジトリのルートに、index.html / guide.html / favicon.ico / assets フォルダー / README.txt をアップロードしてください。
3. Settings → Pages → Deploy from a branch → main / (root) → Save を選びます。
4. 公開サイトで各占いが使えるか確認してください。

公開後、Discord や X のカード画像（OGP）が表示されない場合は、index.html の次のタグを確認してください。
<meta property="og:image" content="assets/ogp.jpg"/>
<meta name="twitter:image" content="assets/ogp.jpg"/>
この２つの content を https://ユーザー名.github.io/stella-fortune/assets/ogp.jpg のような公開サイトの完全なURLに変更してください。

注意事項は guide.html の利用案内に掲載しています。
メイン画面から「大切なお知らせ」の大きなパネルや種類数の宣伝文句を削除して、占いを選びやすく整えています。

演出強化版：星々と月の占いのロゴは旧デザインを維持。各占いの光・星・カードの動きを強化し、文字の種類数などは非表示。
