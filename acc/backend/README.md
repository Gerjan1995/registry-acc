go into output dir
build image with following syntax:
docker build . -t registry-backend-prod:0.1; docker tag registry-backend-prod:0.1 daasdtr01.dtr:5000/mycity/registry-backend-prod:0.1; docker push daasdtr01.dtr:5000/mycity/registry-backend-prod:0.1

n.b. this build is based on nginx alpine release, lightweight but doesnt include stuff like rc-service