# Discord News Bot

このBotはDiscordのコミュニティサーバーで使用するためのニュース自動投稿Botです。Pythonで開発されており、News APIを使用して最新のトップニュースを取得し、指定されたDiscordのWebhook URLに投稿します。以下は主な機能説明です:

- 指定した国とカテゴリに基づいてトップニュースを取得できます。
- 投稿内容にはニュースのタイトル、要約、およびURLが含まれます。
- 投稿には任意でタイトルを含めることができます。

## 導入方法

**事前準備:**

- News APIのAPIキーを取得してください。News APIの公式サイト(https://newsapi.org/) でアカウントを作成し、APIキーを取得してください。**※取得したAPIキーは絶対に第三者に公開しないでください。**
- DiscordのWebhook URLを取得してください。DiscordのサーバーにWebhookを作成し、そのURLを取得してください。

**1. Zipファイルのダウンロードを行い解凍してください**
コマンドプロンプトでのダウンロードもしくはGithub上の**<>code**からダウンロードしてください。

コマンドプロンプト：下記のリポジトリをクローンしてください。
```
git clone https://github.com/Paraccoli/DiscordBot_News.git
cd DiscordBot_News
```

**2. config.pyファイルから取得したAPIキーとWebhook URLを設定します:**
```python
# config.py
# News APIのAPIキーを指定します
API_KEY = 'your_api_key'
# Discord Webhook urlの指定
DISCORD_WEBHOOK_URL = 'your_webhook_url'
```


**3. 必要なライブラリをインストールします:**

```
pip install requests
```


**4. Botを実行します:**

```
python Discord_NEWS.py
```


これでBotがDiscordのニュースを自動投稿する準備が整いました！

## その他リソース

- PythonでNewsAPIの日本語記事を取得する方法(https://qiita.com/hatt_takumi/items/fbe6df7b6eb72cc8985c)
- Python と News API を使ってニュース記事を収集する(https://zenn.dev/uinoue/articles/660ee202373f64#%E5%85%A5%E5%8A%9B%EF%BC%88%E3%83%AA%E3%82%AF%E3%82%A8%E3%82%B9%E3%83%88%E3%83%91%E3%83%A9%E3%83%A1%E3%83%BC%E3%82%BF%EF%BC%89)

## 作成者

- 作成者: Paraccoli
- GitHub: (https://github.com/xM1guel)

