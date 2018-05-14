# ci_cd-pipeline

docker build -t parcel-frontend .
docker run -it --rm -p 8085:80 --name=parcel-frontend parcel-frontend

docker run -d --restart always --network=parcelnetwork -p 8080:80 --name=parcel-frontend parcel-frontend:1.0