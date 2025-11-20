# public-example-158

Now here we will pull a dockerhub image - nginx 
So we will pull the latest nginx image
First do docker login

docker pull nginx:1.29.3
docker images 
docker tag nginx:1.29.3 
howaboutwepullsomeimages/nginx:v0.1.0
docker images
docker push howaboutwepullsomeimages/nginx:v0.1.0

git add .
git commit -m "deploy nginx"
git push
