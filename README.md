# appengine

Example application for Google App Engine (As of November 2018)

## Run locally

* Install [Go 1.11+](https://golang.org/dl/)

```
PORT=8080 go run *.go
```

## Deploy

* Create an application in the [Google Cloud Platform Console](https://console.cloud.google.com/)
* Remember the `project-id` for later
* Install and initialize the [Google Cloud SDK](https://cloud.google.com/sdk/)

```
gcloud auth login
gcloud config set project <project-id>
gcloud app deploy app/app.yaml -v v1
```
