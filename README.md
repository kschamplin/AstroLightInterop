# AstroLightInterop

Tools to operate on datasets between light classification models.

Consists of `data converters` and `model interfaces`

### Data converters

These modify datasets to fit a different format for other models.

| Input      | RAPID format | PLAsTiCC format | SuperNNova Format |
|------------|--------------|-----------------| ----------------- |
| PLAsTiCC   | yes          | ---             | planned |
| SPCC       | via PLAsTiCC | planned         | via PLAsTiCC |
| SuperNNova | via PLAsTiCC | planned         | via PLAsTiCC |
|          |              |                 |

#### Usage
TODO

### Model interfaces

These serve as a standard way to evaluate different models. 

| Model | Testing | Training
| ----- | ------- | -------- |
| RAPID | yes | in progress |
| AVOCADO | planned | planned |
| SuperNNova | planned | planned |
| DeepPhotAstro | planned | planned |

#### Usage
All models take PLAsTiCC-formatted data as their input.


