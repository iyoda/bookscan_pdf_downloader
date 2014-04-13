bookscan_pdf_downloader
=======================
BOOKSCANの依頼したもの一覧ページからPDFを自動でダウンロードしますMacOSX 10.4以降に対応

automatorを使ってます。

使い方

1. bookscan_pdf_list.workflow と download.workflow をダウンロード
2. bookscan_pdf_list.workflow を automator で開き「ワークフローを実行:ワークフロー」を ダウンロードしたdownload.workflowに設定
3. 必要ならdownload.workflowの「URLをダウンロード:場所」を変更
4. SafariでBOOKSCANにログインして依頼したもの一覧ページ(PDFのダウンロードリンクが表示されているページ)を開きます
5. bookscan_pdf_list.workflow を実行
