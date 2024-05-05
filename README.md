厚生労働省が配信するRSSの書式がvalidでない問題を修復し、正しいRSSを配布するためのGitHub Pagesと関連する自動化を提供します。

[![Deploy static content to Pages](https://github.com/KengoTODA/valid-mhlw-rss/actions/workflows/deploy.yml/badge.svg)](https://github.com/KengoTODA/valid-mhlw-rss/actions/workflows/deploy.yml)

|変換元|変換先|書式の正しさ|
|-----|-----|----------|
|https://www.mhlw.go.jp/stf/news.rdf|https://www.kengo-toda.jp/valid-mhlw-rss/stf/news.rdf|<a href="http://validator.w3.org/feed/check.cgi?url=https%3A//www.kengo-toda.jp/valid-mhlw-rss/stf/news.rdf"><img src="https://validator.w3.org/feed/images/valid-rss.png" alt="[Valid RSS]" title="Validate news.rdf" /></a>|
|https://www.mhlw.go.jp/stf/kinkyu.rdf|https://www.kengo-toda.jp/valid-mhlw-rss/stf/kinkyu.rdf|<a href="http://validator.w3.org/feed/check.cgi?url=https%3A//www.kengo-toda.jp/valid-mhlw-rss/stf/kinkyu.rdf"><img src="https://validator.w3.org/feed/images/valid-rss.png" alt="[Valid RSS]" title="Validate kinkyu.rdf" /></a>|
|https://www.mhlw.go.jp/rss/inful_news.rdf|https://www.kengo-toda.jp/valid-mhlw-rss/rss/inful_news.rdf|<a href="http://validator.w3.org/feed/check.cgi?url=https%3A//www.kengo-toda.jp/valid-mhlw-rss/rss/inful_news.rdf"><img src="https://validator.w3.org/feed/images/valid-rss.png" alt="[Valid RSS]" title="Validate inful_news.rdf" /></a>|

# forkしてご利用される方へ

[`.github/workflows/deploy.yml` の `cron:` 部分](https://github.com/KengoTODA/valid-mhlw-rss/blob/d598fd3ccde5ef0dde7372cfefe08ddafa30fc2c/.github/workflows/deploy.yml#L7)を書き換えて、厚生労働省のウェブサイトへのアクセス時刻を分散するようご配慮いただけますと幸いです。

# Copyright

Copyright &copy; 2024, Kengo TODA
