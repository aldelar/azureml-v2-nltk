# azureml-v2-nltk

## Install the AZ ML CLI V2 extension

```
az extension add -n ml
```

## Create the environment

```
cd training
az ml environment create -f environment.yml
```

## Run the pipeline (from repo root)

```
az ml job create -f pipeline.yml