# Twitter Web API

|Method|Path|Description|
|---|---|---|
|GET|/users/{user_id}|ユーザ(user_id)の取得|
|GET|/users/{user_id}/tweets|ユーザ(user_id)のツイートの一覧を取得|
|POST|/tweets|ツイートの作成|
|DELETE|/tweets/{tweet_id}|tweet_id を受け取ってツイートの削除|
|POST|/tweets/{tweet_id}/replies|リプライを作成|
|POST|/tweets/{tweet_id}/retweets|リツイートの作成|
|POST|/tweets/{tweet_id}/quote_tweets|引用リツイートの作成|
|GET|/users/{user_id}/follows|ユーザ(user_id)のフォロー一覧|
|GET|/users/{user_id}/followers|ユーザ(user_id)のフォロワー一覧|
|POST|/follows/{follow_user_id}|ユーザ(follow_user_id)をフォロー|
|DELETE|/follows/{follow_user_id}|ユーザ(follow_user_id)を削除|
|GET|/users/{user_id}/lists|ユーザ(user_id)のリストの一覧を取得|
|POST|/lists|リストの作成|
|DELETE|/lists/{list_id}|list_id を受け取って削除|
|POST|/lists/{list_id}/list_members/{user_id}|リスト(list_id) を受け取ってリストにユーザ(user_id)を追加|
