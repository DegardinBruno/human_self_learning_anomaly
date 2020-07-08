# Human Activity Analysis: Iterative Weak/Self-Supervised Learning Frameworks for Detecting Abnormal Events

<div align="center">
    <img src="fig/WSS_Schema.png", width=100%">
</div>


##### Libraries version:
* Keras: 2.4.3
* TensorFlow: 2.2.0
* Scipy: 1.4.1
* Scikit-learn: 0.21.3
* NumPy: 1.17.3


## Prepare datasets

To train your model and employ self-supervision for each network, the following directory structure is created:

```
|-- annotation
|   |-- strong
|   |   |-- train.csv           // empty, to be filled by the WS Model and Bayesian Classifier
|   |   |-- test.csv
|   |   |-- val.csv
|   |   |-- unlabeled_set.csv
|   |   |-- test_notes.csv
|   |   `-- val_notes.csv
|   `-- weak
|       |-- train.csv
|       |-- test.csv
|       |-- val.csv
|       |-- unlabeled_set.csv
|       |-- test_notes.csv
|       |-- val_notes.csv
|-- models
|   |-- pattern_model
|   |   |-- 0                   // WSS framework iterations
|   |   |-- 1
|   |   |-- ...
|   |-- strong_model
|   |   |-- 0                   // WSS framework iterations
|   |   |-- 1
|   |   |-- ...
    `-- weak_model
|       |-- 0                   // WSS framework iterations
|       |-- 1
|       |-- ...
```

## Citation
Please cite this paper in your publications if it helps your research:

    @inproceedings{degardin2020human,
      author = {Degardin, Bruno and Proença, Hugo},
      title = {Human Activity Analysis: Iterative Weak/Self-Supervised Learning Frameworks for Detecting Abnormal Events},
      booktitle={IEEE International Joint Conference on Biometrics},
      year = {2020},
      organization={IEEE}
    }

    
