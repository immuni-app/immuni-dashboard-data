<h1 align="center">Immuni Open Data</h1>

<div align="center">
<img src="logo.png">
</div>

<!-- Badges -->
<div align="center">
    <!-- CoC -->
    <a href="CODE-OF-CONDUCT.md">
      <img src="https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg" />
    </a>
    <!-- last commit -->
    <a href="https://github.com/immuni-app/immuni-dashboard-data/commits/master">
      <img src="https://img.shields.io/github/last-commit/immuni-app/immuni-dashboard-data" />
    </a>
</div>

<br />

<div align="center">
  <h3>
    <a href="https://www.immuni.italia.it/">
      Website
    </a>
    <span> | </span>
    <a href="https://github.com/immuni-app/documentation">
      Documentation
    </a>
  </h3>
</div>

# Description

This repository contains the data collected by the National contact-tracing system "Immuni".

In particular, the following data are uploaded every day at 5 pm (UTC):
- daily download trend for both the iOS and the Android platforms;
- daily trend of both positive users and notifications sent, at national level;
- weekly trend of both positive users and notifications sent, at regional level.

Furthermore, it is possible to check the interactive visualization of this dataset on the dedicated [immuni dashboard](https://www.immuni.italia.it/dashboard.html).

# Contents

- [Repository structure](#repository-structure)
- [Data format](#data-format)
- [Data update](#data-update)
- [License](#license)

# Repository structure
```
immuni-dashboard-data/
│
├── dati/
│   ├── andamento-dati-nazionali.csv
│   ├── andamento-dati-nazionali.json
│   ├── andamento-download.csv
│   ├── andamento-download.json
│   ├── andamento-settimanale-dati-regionali-latest.csv
│   ├── andamento-settimanale-dati-regionali-latest.json
│   ├── andamento-settimanale-dati-regionali.csv
│   ├── andamento-settimanale-dati-regionali.json
```

# Data format
- [Download trend data](https://github.com/immuni-app/immuni-dashboard-data/blob/master/format-download-trend.md)
- [National trend data](https://github.com/immuni-app/immuni-dashboard-data/blob/master/format-national-trend.md)
- [Regional trend data](https://github.com/immuni-app/immuni-dashboard-data/blob/master/format-regional-trend.md)

# Data update
App download trend data: every day at 5 pm (UTC).

National trend data: every day at 5 pm (UTC).

Regional trend data: every monday at 5 pm (UTC).
# License

## Authors / Copyright

2020 (c) Commissario straordinario per l'emergenza Covid-19 - Presidenza del Consiglio dei Ministri.

The version control system  in place provides attribution for specific lines of code.

## Third party components licenses

## License details

The license for this repo is a [Creative Commons Attribution 4.0 International](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0). Please see the [LICENSE](LICENSE) file for extended reference.
