# REST API in golang

curl localhost:10000
curl localhost:10000/articles
curl localhost:10000/article/1

curl --header "Content-Type: application/json" \
  --request POST \
  --data '{ "Id": "3", "Title": "Newly Created Post", "desc": "The description for my new post", "content": "my articles content" }' \
  http://localhost:10000/article