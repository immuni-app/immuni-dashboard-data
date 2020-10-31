# App download trend data format

## Data update
- Every day at 5 pm (UTC). 

Please note that if the data on downloads from Apple and Google are not yet available at the designated time, the update is postponed to the next day.

## Data format

**Reference file:** andamento-download.csv<br>

| Field Name                  | Description (ITA)                       | Description                            | Format                       | Example             |
|-----------------------------|-----------------------------------|----------------------------------------|-------------------------------|---------------------|
| **data**                        | Data di riferimento            | reference data                   | YYYY-MM-DD HH:MM:SS | 2020-06-01 00:00:00 |
| **ios**                       | numero di download giornalieri dell'app per iOS | daily downloads for the iOS app           |  number     |         3         |
| **android**              | numero di download giornalieri dell'app per Android | daily downloads for the Android app        |  number                        | 3                  |
| **ios_android**       | numero di download giornalieri complessivi       | daily downloads for both iOS and Android apps                     | number             | 3             |
| **ios_total**                         | numero di download totali dell'app per iOS                        | total downloads for the iOS app                                  | number                         | 3          |
| **android_total**                        | numero di download totali dell'app per Android                       | total downloads for the Android app                              | number                         | 3         |
| **ios_android_total**      | numero di download complessivi totali        | total downloads for both the iOS and Android apps    | number                        | 3                   |


These data are also available in a json format.

### Note
Please note:
The *download* value does not include app updates and re-installations.
