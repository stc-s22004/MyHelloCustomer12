# MyHelloCustomer12

s22004

第6章ConstraintLayoutのサンプルプログラムConstraintLayoutSampleをもとに、以下の内容を満たすアプリKadai12を作成しなさい。
　１） 新たにメールのタイトルを入力するためのラベルと入力欄を追加する。
　２） 送信ボタンを押すと、名前、タイトル、メールアドレス、質問内容からなるテキストをToastを使って表示される。
　３） 確認ボタンを押すと送信確認のためのダイアログが表示され、先と同じ内容のテキストをToastを使って表示する。
　４） クリアボタンを押すと、すべての入力欄が空欄となること。

[補足] Toastの代わりにSnackbarを利用してもよい。以下はTostをコメントして、Snackbarを追加したボタンリスナーの例。

private class ButonClickListener implements View.OnClickListener{
　　@Override
　　public void onClick(View v) {
　　　　//Toast.makeText(getApplicationContext(), ""Toas Sample", Toast.LENGTH_LONG).show();
 　　　　Snackbar.make(v, "Snackbar Sample", Snackbar.LENGTH_LONG).show();
　　}
}


提出締切：　7月18日（火）12:00まで
提出方法：　各自、科目担当よりエミュレーター上での実行結果の確認を受けること。確認後に、プロジェクト(レポジトリ)をGitHubへpublicでアップし、そのURL（コミットハッシュ値付き）をGoogle Classroomの提出先へ提出のこと。
