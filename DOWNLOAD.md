Dataset **Dataset of Annotated Food Crops and Weed Images** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://www.dropbox.com/scl/fi/pqgo9rtza830gu4ofr73x/dataset-of-annotated-food-crops-and-weed-images-DatasetNinja.tar?rlkey=cludxa2z546dvwjec7rxyovo3&dl=1)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Dataset of Annotated Food Crops and Weed Images', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://data.mendeley.com/datasets/nj4vtk4tt6/1).