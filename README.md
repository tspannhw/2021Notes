# 2021Notes


curl -X POST 'https://example.com/api/v1/dags/{dag_id}?update_mask=is_paused' \
-H 'Content-Type: application/json' \
--user "username:password" \
-d '{
    "is_paused": true
}'
