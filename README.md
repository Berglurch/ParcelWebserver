# ci_cd-pipeline

docker build -t parcel-server .
docker run -it --rm -p 8085:80 --name=parcel-server parcel-server