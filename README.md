# sam
AWS SAM

https://docs.aws.amazon.com/lambda/latest/dg/test-sam-cli.html

sam local start-api

$ curl http://localhost:3000/products 
"This is a LIST operation, return all products"

$ curl -XDELETE http://localhost:3000/products/1
"This is a DELETE operation on product ID 1"