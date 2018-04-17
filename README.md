```
gcloud beta functions deploy ocr-extract --trigger-bucket smartbook-receipts --entry-point processImage

gsutil cp [PATH_TO_IMAGE] gs://smartbook-receipts
```