# cloud_run_hello_world_appapp

Log into gcloud: <br>
gcloud auth login <br>

Configure docker: <br>
gcloud auth configure-docker europe-west1-docker.pkg.dev (make sure to specify appropriate region)

docker tag SOURCE-IMAGE LOCATION-docker.pkg.dev/PROJECT-ID/REPOSITORY/IMAGE:TAG

docker tag SOURCE-IMAGE LOCATION-docker.pkg.dev/PROJECT-ID/REPOSITORY/IMAGE:TAG

<br>
Docker command: <br>

docker build -t image-name . 
<br>
docker tag image-name gcr.io/Google-Cloud-Project-Name/image-name:tag 
<br>
docker push gcr.io/Google-Cloud-Project-Name/image-name:tag
