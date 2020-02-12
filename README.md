# AIRCRACK

<img src="https://assets.gitlab-static.net/uploads/-/system/project/avatar/16811260/aircrack-ng-new-logo.jpg" width="200" height="200"/>

## INDEX

  - [AIRCRACK](#aircrack)
  - [INDEX](#index)
  - [BADGES](#badges)
  - [INTRODUCTION](#introduction)
  - [PREREQUISITES](#prerequisites)
  - [INSTALL](#install)
  - [LICENSE](#license)

## BADGES

[![pipeline status](https://gitlab.com/oda-alexandre/aircrack/badges/master/pipeline.svg)](https://gitlab.com/oda-alexandre/aircrack/commits/master)

## INTRODUCTION

Docker image of :

- [aircrack](https://www.aircrack-ng.org)

Continuous integration on :

- [gitlab](https://gitlab.com/oda-alexandre/aircrack/pipelines)

Automatically updated on :

- [docker hub public](https://hub.docker.com/r/alexandreoda/aircrack)

## PREREQUISITES

Use [docker](https://www.docker.com)

Use a carte wifi with mode monitor

## INSTALL

```docker run -ti --rm --name aircrack -v ${HOME}:/home/aircrack --network host --cap-add=NET_ADMIN alexandreoda/aircrack```

## LICENSE

[![GPLv3+](http://gplv3.fsf.org/gplv3-127x51.png)](https://gitlab.com/oda-alexandre/aircrack/blob/master/LICENSE)
