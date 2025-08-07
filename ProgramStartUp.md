# ProgramStartUp
<br>

- **リポジトリの作成**
  1. GitHub上にてリモートリポジトリの作成を行う
  1. sourcetreeを開きリポジトリのURLをコピーを使ってクローンしローカルリポジトリを作成する
  1. プロジェクトを作成する際に先ほどのリポジトリのパス内に入れる

- gitignoreをリポジトリ内に入れてgitのトラッキングの対象外にできる（gitに管理させないファイルを記述するファイル⇒gitignore）

- GeminiAPIキーを取得し、そのURLを使って生成AIGenminiの機能を使える

- Geminetを使いGeminiAPIを簡易的に扱える（Nugetを使ってインストールする）
  1. Geminetを検索
  1. Geminetのサイトに載っているソースコードを貼り付け"GEMINI_API_KEY"にURLを入力
  1. Environment.GetEnvironmentVariableの記述を削除
  1. 実行するとContentsに書いた内容の返信をAIがする

- ユーザーシークレットを使って使いたい非公開情報をソースコードに記述しないことができる
  1. VisualStudioのプロジェクトを右クリック
  1. ユーザーシークレットの管理
  1. sercrets.jsonのタブが現れるのでこの中にAPIキーを入れる

例）
```
{
  "Sercrets": {
    "Message": "GEMINI＿API＿KEY"
  }
}
```