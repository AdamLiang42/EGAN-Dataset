# SynResLoadPattern

Here we introduce the *`ERGAN-Dataset`*, which includes synthetic residential load patterns. These patterns closely emulate the temporal dependencies and distribution features present in genuine training data. It offers a broad and varied collection of load patterns, making it a prime resource for both researchers and practitioners. It's designed for in-depth analysis, simulation, and study in the field of residential electricity consumption.


## Data Description
The *`ERGAN-Dataset`* contains 1 million generated residential load pattern profiles. Each profile represents normalized daily electricity consumption, at 1 hour resolution, with values spanning from 0 to 1.

## Data Construction
The residential load pattern profiles in the dataset were generated using the Ensemble Recurrent Generative Adversarial Network (ERGAN) Framework we proposed. It generative framework was trained on a real-world dataset sourced from the Pecan Street database. This foundational training set includes hourly load data for 417 households over a year, specifically from Jan. 1, 2017, to Dec. 31, 2017. The data was normalized to represent a diverse array of daily load patterns and consumption habits.

## Dataset Location
The dataset is located under the following directory: [ERGAN-Dataset](https://github.com/AdamLiang42/ERGAN-Dataset/tree/main/ergan_dataset)

## Publications:
<!-- Welcome to cite our publications on this project. -->
TBD


## Acknowledgments:
We would like to acknowledge the sponsorship from FIT Startup Funding of Monash University and the Australian Research Council (ARC) Discovery Early Career Researcher Award (DECRA) under Grant DE230100046.

## License:
This *`ERGAN-Dataset`* is made available under the Open Database License: http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the database are licensed under the Database Contents License: http://opendatacommons.org/licenses/dbcl/1.0/.
