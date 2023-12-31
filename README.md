# Ontology

Analysis of UFO sightings around the world using Python, Pandas, Seaborn, Matplotlib, Jupyter Notebook, VScode, Anaconda, Kaggle

## Notes

- FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints.

- FastAPI project wrapper is in OntologyML folder

## Duplicate conda envinronment

```
conda list --export > requirements.txt

conda create --name <envname> --file requirements.txt

```

## Steps

```
Select kernel python 3.10 tensorflow

conda create --name ontology

conda activate ontology

conda install pandas

conda install seaborn

conda install transformers

conda install pytorch torchvision -c pytorch

conda install fastapi

conda install "uvicorn[standard]"

python-multipart

```

* Activate ontology kernel in VScode


## Run uvicorn server

```
uvicorn main:app --reload
```

## Steps for Dockerizing

```

```

## PROD

```
uvicorn 'main:app' --host=0.0.0.0 --port=80
```

## Screenshots

![Screenshot 1](https://raw.githubusercontent.com/codelabspro/ontology/main/screenshots/screenshot_1.png)

![Screenshot 2](https://raw.githubusercontent.com/codelabspro/ontology/main/screenshots/screenshot_2.png)

![Screenshot 3](https://raw.githubusercontent.com/codelabspro/ontology/main/screenshots/screenshot_3.png)

## Kaggle Dataset for Ontology

https://www.kaggle.com/datasets/camnugent/ufo-sightings-around-the-world?resource=download


## Hugging Face Dataset for Ontology

https://huggingface.co/dandelin/vilt-b32-finetuned-vqa

https://huggingface.co/docs/transformers/model_doc/idefics

