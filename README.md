# disaster_report_bot
災害情報レポートボット

先遣隊システム

動作時の環境変数

APPLICATION_NAME　　　　アプリケーション名　　DropBoxフォルダ名に利用

authstr      Google Spread　Sheet アクセス認証用　JSON

DROPBOXACCESSTOKEN　　　　　　　　　　　DropBoxアクセストークン

LineMessageAPIChannelAccessToken　　　　LINE　アクセストークン

LineMessageAPIChannelSecret　　　　　　LINEAPIチャンネルシークレット

MapURL　　　　　　　　　地図表示モジュールURL

SPEECHAPIKEY　　　　　　Google Speech API　Key
             (設定が無い場合でもOK その場合音声文字変換は行わない)

SPREADSHEET_ID　　　　　Google Spread Sheet　ID


20200507
DropBoxのバイナリデータ保存ホルダをアプリケーション別に分けた


20190503   Line bot で送信   テキスト  写真   ボイスメッセージ   

20190518   サーバ側 暫定でDropBox に格納   Lineで送信した場合写真に位置情報がつかない
