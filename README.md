# example-go-gcp-storage-app
## Description
This app is used in the [gke-poc-toolkit](https://github.com/GoogleCloudPlatform/gke-poc-toolkit) to show how workload identity can be used to provide an app depoyed into GKE RBAC to a Google Cloud Storage bucket.

This app is a very simple GCP storage file uploader written in go and leverages the extra dope gin framework.

## Usage
Call the api and pass in a file.
`curl -F "file=@./test" http://localhost:8080/cloud-storage-bucket`
