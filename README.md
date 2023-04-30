# hatena-blog

はてなブログをGitHubで管理する。

https://kotsutsumi.hatenablog.com/


```sh
# ドラフト投稿
docker-compose run --rm blogsync post --title=draft --draft kotsutsumi.hatenablog.com < draft.md

# 取得
docker-compose run --rm blogsync pull kotsutsumi.hatenablog.com
```