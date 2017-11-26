Google Container Builder Quickstart

https://cloud.google.com/container-builder/docs/quickstart-docker

Build and push image with a Dockerfile:
```
gcloud container builds submit --tag gcr.io/[PROJECT_ID]/quickstart-image .
```

Do the same using a _build reuest_:

```
gcloud container builds submit --config cloudbuild.yaml .
```