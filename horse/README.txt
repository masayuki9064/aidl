＜当スクリプトの目的＞
・サラブレッドの画像を取り込んで、牡馬・牝馬の分類を行うスクリプトです。
  ResNetで作成しました。
  なお、セン馬は未対応です。

＜実行上の注意＞
・当スクリプト「horse_bunrui.ipynb」は、
  Google Colaboratory上で動かす前提で作っております。

・事前にマイドライブ直下に、「horse_bunrui.ipynb」と「data」フォルダを丸ごと置いてください。
  (data.zipを解凍して置いてください。)

・ランタイムの種別がGPUになっていることを必ず確認してください。

・「horse_bunrui.ipynb」を実行すると
   "/content/drive" をマウントする処理が走ります。
   表示されたリンク先の認証キーを
   コンソール上に出てきたテキストボックスに入力願います。

・生成されたモデルのファイル「horse_bunrui_model.hdf5」や、
  重みファイル「weights.xx.hdf5」は、
  マイドライブ直下に自動生成されたoutput配下に出力されます。
  起動時に、output配下のファイル・サブディレクトリは削除されますので、
  必要とあらば退避してください。

-----
(c) 2019 Masayuki Isobe
============================================================================


＜参考＞
画像の取得元は「netkeiba」です。
