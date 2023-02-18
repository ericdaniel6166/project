##### Building and pushing images to Docker Hub

- Clone from all repos: [all_repos](all_repos.md) 
- Building and pushing images to Docker Hub 
<br>Ex:
<br>docker build -f logger-service.dockerfile -t <dockerhub_id>/<image_name>:<tag_name> .
<br>docker push <dockerhub_id>/<image_name>:<tag_name>
<br>docker build -f logger-service.dockerfile -t eric6166/logger-service:1.0.0 .
<br>docker push eric6166/logger-service:1.0.0