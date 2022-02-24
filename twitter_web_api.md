# Twitter Web API

|Method|Path|Description|
|---|---|---|
|GET|/users/{user_id}|ユーザ(user_id)の取得|
|GET|/users/{user_id}/tweets|ユーザ(user_id)のツイートの一覧を取得|
|POST|/users/{user_id}/tweets|ユーザ(user_id)のツイートの作成|
|DELETE|/users/{user_id}/tweets/{tweet_id}}|tweet_id を受け取ってツイートの削除|
|POST|/users/{user_id}/replies|ユーザ(user_id)のリプライを作成|
|POST|/users/{user_id}/retweets|ユーザ(user_id)のリツイートの作成|
|POST|/users/{user_id}/quote_tweets|ユーザ(user_id)の引用リツイートの作成|
|GET|/users/{user_id}/following|ユーザ(user_id)のフォロー一覧|
|GET|/users/{user_id}/followers|ユーザ(user_id)のフォロワー一覧|
|POST|/users/{user_id}/following/|ユーザ(user_id)がユーザ(bodyで送られてくるuser_id)をフォロー |
|DELETE|/users/{user_id}/following/{following_user_id}|ユーザ(user_id)がユーザ(following_user_id)をアンフォロー|
|GET|/users/{user_id}/lists|ユーザ(user_id)のリストの一覧を取得|
|POST|/users/{user_id}/lists|ユーザ(user_id)のリストの作成|
|DELETE|/users/{user_id}/lists/{list_id}|リスト(list_id)を受け取って削除|
|POST|/users/{user_id}/lists/{list_id}/members|ユーザ(user_id)のリスト(list_id) を受け取ってリストにユーザ(user_id)を追加|
