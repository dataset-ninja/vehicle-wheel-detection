Dataset **Vehicle Wheel Detection** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/R/b/6b/qX2jLzjssouglwvSiLOUSoA8VYUaPEKEQXPuS60X9h7LtVJZPIiFWyBkf2Oyvd75ofp1uAPl1V1mZxMJYy95xPCn9hNDyzpVFxduChwFXsiYMorbajyCDnN83m1m.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Vehicle Wheel Detection', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/dataclusterlabs/vehicle-wheel-detection/download?datasetVersionNumber=1).