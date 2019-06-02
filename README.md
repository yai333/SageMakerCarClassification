# SageMaker Car classification

Object detection for car classification using the Amazon SageMaker Object Detection algorithm with a public dataset of [Cars Dataset from Stanford](http://ai.stanford.edu/~jkrause/cars/car_dataset.html).

## SageMaker

- CarClassification.ipynb

## Deploy Serverless Api gateway

```
sls deploy
```

## Invoke SageMaker endpoint

```
curl -d '{"img_url":"https://image-url.jpg"}' -H "Content-Type: application/json" -X POST https://sagemaker_endpoint_url
```
