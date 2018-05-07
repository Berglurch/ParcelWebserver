# ci_cd-pipeline

docker build -t parcel-frontend:1.0 .
docker run -d --restart always -p 8080:80 --name=parcel-frontend parcel-frontend:1.0