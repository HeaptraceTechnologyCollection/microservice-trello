# Trello as a microservice
An OMG service for trello, it is a task management app that gives you a visual overview of what is being worked on and who is working on it.

[![Open Microservice Guide](https://img.shields.io/badge/OMG-enabled-brightgreen.svg?style=for-the-badge)](https://microservice.guide)
<!-- [![Build Status](https://travis-ci.com/heaptracetechnology/microservice-intercom.svg?branch=master)](https://travis-ci.com/heaptracetechnology/microservice-intercom)
[![codecov](https://codecov.io/gh/heaptracetechnology/microservice-intercom/branch/master/graph/badge.svg)](https://codecov.io/gh/heaptracetechnology/microservice-intercom)
[![GolangCI](https://golangci.com/badges/github.com/golangci/golangci-web.svg)](https://golangci.com) -->


## [OMG](hhttps://microservice.guide) CLI

### OMG

* omg validate
```
omg validate
```
* omg build
```
omg build
```
### Test Service

* Test the service by following OMG commands

### CLI

##### Get Cards
```sh
$ omg run get_cards -a board_id=<BOARD_ID> -e API_KEY=<API_KEY> -e ACCESS_TOKEN=<TOKEN>
```

## License
### [MIT](https://choosealicense.com/licenses/mit/)

## Docker
### Build
```
docker build -t microservice-trello .
```
### RUN
```
docker run -p 3000:3000 microservice-trello
```
