# 更新履歴

 - master/HEAD
   * Firefox 25に対応
   * 除外リストが空の時に、一定時間でバックグラウンドのタブを休止する機能が働いていなかったのを修正（by YosukeM, thanks!）
 - 0.1.2013053101
   * Mozilla Add-onsのEditorによるレビューで、後方互換性のためにライブラリ内に含めてあった・このアドオンでは問題を起こし得ないコードが原因でレビューを蹴られる状況だったため、ライブラリを削除した
 - 0.1.2013052901
   * Mozilla Add-onsのEditorによるレビューで、後方互換性のためにライブラリ内に含めてあった・このアドオンでは到達し得ないコードが原因でレビューを蹴られる状況だったため、ライブラリから当該コードを削除した
   * [セッション保存APIの仕様変更](http://dutherenverseauborddelatable.wordpress.com/2013/05/23/add-on-breakage-continued-list-of-add-ons-that-will-probably-be-affected/)に追従
 - 0.1.2013040601
   * タブの再読み込み時に、休止されていたタブを自動的に復元するようにした
 - 0.1.2012122901
   * 公開
