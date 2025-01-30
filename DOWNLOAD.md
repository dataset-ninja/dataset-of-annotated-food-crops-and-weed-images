Dataset **Dataset of Annotated Food Crops and Weed Images** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzI4NTdfRGF0YXNldCBvZiBBbm5vdGF0ZWQgRm9vZCBDcm9wcyBhbmQgV2VlZCBJbWFnZXMvZGF0YXNldC1vZi1hbm5vdGF0ZWQtZm9vZC1jcm9wcy1hbmQtd2VlZC1pbWFnZXMtRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAieWNablhJNjBkWms1VnFzd3lpRHNCNWNPM3pIandaK3lud1RRbnlJbm13MD0ifQ==)

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