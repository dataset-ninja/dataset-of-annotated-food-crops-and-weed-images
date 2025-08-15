Dataset **Dataset of Annotated Food Crops and Weed Images** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMjg1N19EYXRhc2V0IG9mIEFubm90YXRlZCBGb29kIENyb3BzIGFuZCBXZWVkIEltYWdlcy9kYXRhc2V0LW9mLWFubm90YXRlZC1mb29kLWNyb3BzLWFuZC13ZWVkLWltYWdlcy1EYXRhc2V0TmluamEudGFyIiwgInNpZyI6ICJwWXBhcU9jb2svOEVBeUdGZXF2QmdYMHpMMktBS3RwVDFudlJOTUdQWXNZPSJ9?response-content-disposition=attachment%3B%20filename%3D%22dataset-of-annotated-food-crops-and-weed-images-DatasetNinja.tar%22)

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