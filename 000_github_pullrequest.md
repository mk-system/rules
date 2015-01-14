PullRequest 手順書

MKシステムで社内ルールを改善したいところを見つけたらPullRequest を作成して、議論を行います
以下が手順書です

gitが得意な人は勝手にやってください


=======================================



1. forkする

  ![](000_github_pullrequest/01.png)

2. 所属している組織を選択(必要であれば)

  ![](000_github_pullrequest/02.png)

3. 変更したい規定を選択

  ![](000_github_pullrequest/03.png)

4. 編集をクリック

  ![](000_github_pullrequest/04.png)

5. 変更する

  ![](000_github_pullrequest/05.png)

6. 変更内容をプレビューで確認

  ![](000_github_pullrequest/06.png)

7. ページ下部で変更内容を記入してcommit

  ![](000_github_pullrequest/07.png)

  例:
  ooのxxx を--- に変更した

  等完結で分かりやすい文章を心がけましょう
  補足点があれば下の欄に入力してください


8. レポジトリトップに戻る

  ![](000_github_pullrequest/08.png)

  複数のファイルを変更したい場合は、手順3 に戻ります。
  変更が完了したら手順9に進みます。


9. プルリクエスト作成画面に移動

  ![](000_github_pullrequest/09.png)
  ![](000_github_pullrequest/10.png)

10. 変更内容が意図した内容であるかを確認

  ![](000_github_pullrequest/11.png)

  意図しない変更の時は分かりそうな人を捕まえて聞いてください。

11. タイトルと変更内容の概要を記入

  ![](000_github_pullrequest/12.png)

  1にはこの変更のタイトルを入力してください

  2には
  後から見た時に、その変更が
  - なぜ必要であったか？
  - どのように変更したか？

  等を簡潔に記載してください。

  内容の記載が終わったら3を押してください

12. 不要になったフォークの削除

  ![](000_github_pullrequest/13.png)
  Settings をクリックして
  
  ![](000_github_pullrequest/14.png)

  Optionsページを下部にスクロールします

  ![](000_github_pullrequest/15.png)

  Denger Zone のDelete this repository をクリック

  ![](000_github_pullrequest/16.png)

  1に アカウント名/MK-Rules を入力して

  2の I understand the consequences, delete this repositoryをクリックします

  ※管理者アカウントでやらないように

以上






