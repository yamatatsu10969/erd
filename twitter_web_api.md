# Twitter Web API

|Method|Path|Description|
|---|---|---|
|GET|/users/{user_id}|ユーザの取得|
|GET|/users/{user_id}/tweets|ユーザのツイートの一覧を取得|
|POST|/users/{user_id}/tweets|ツイートの作成|
|DELETE|/users/{user_id}/tweets/{tweet_id}}|tweet_id を受け取ってツイートの削除|
|POST|/users/{user_id}/replies|リプライを作成|
|POST|/users/{user_id}/retweets|リツイートの作成|
|POST|/users/{user_id}/quote_tweets|引用リツイートの作成|
|GET|/users/{user_id}/following|フォロー一覧|
|GET|/users/{user_id}/followers|フォロワー一覧|
|POST|/users/{user_id}/following/|ユーザのフォロー|
|DELETE|/users/{user_id}/following/|ユーザのアンフォロー|
|GET|/users/{user_id}/lists|リストの一覧を取得|
|POST|/users/{user_id}/lists|リストの作成|
|DELETE|/users/{user_id}/lists/{list_id}|list_id を受け取って削除|
|POST|/users/{user_id}/lists/{list_id}/members|list_id を受け取ってリストにユーザを追加|
||||
