Dataset **Vehicle Wheel Detection** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/R/3/6n/cZtOyelhbk60jgXKuN319bo9mYiRMnCoQcfevxQN21ErJemYfMNSJCllyLSBlbM794fN53jhv3LnWvoFsG4s5rJGjDr8xxOWEPocB9lh4eB1IwgAGmmmLxs9RDi4.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Vehicle Wheel Detection', dst_path='~/dtools/datasets/Vehicle Wheel Detection.tar')
```
The data in original format can be 🔗[downloaded here](https://www.kaggle.com/datasets/dataclusterlabs/vehicle-wheel-detection/download?datasetVersionNumber=1)