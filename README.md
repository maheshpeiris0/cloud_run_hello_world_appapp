# cloud_run_hello_world_appapp

Log into gcloud: <br>
gcloud auth login <br>

Configure docker: <br>
gcloud auth configure-docker europe-west1-docker.pkg.dev (make sure to specify appropriate region)

docker tag SOURCE-IMAGE LOCATION-docker.pkg.dev/PROJECT-ID/REPOSITORY/IMAGE:TAG

docker tag SOURCE-IMAGE LOCATION-docker.pkg.dev/PROJECT-ID/REPOSITORY/IMAGE:TAG
