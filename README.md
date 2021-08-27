# ISW2-Software-Testing

## JCS   [![Build Status](https://app.travis-ci.com/gabrielequatrana/JCSTest.svg?branch=main)](https://app.travis-ci.com/gabrielequatrana/JCSTest)
Repository progetto: https://github.com/gabrielequatrana/JCSTest
  
Esecuzione dei test e analisi automatica del coverage tramite Jacoco
```bash
mvn clean verify -P coverageProfile
```
Report coverage: ```target\jacoco-gen\jcs-coverage```

# Bookkeeper  [![Build Status](https://app.travis-ci.com/gabrielequatrana/bookkeeper.svg?branch=master)](https://app.travis-ci.com/gabrielequatrana/bookkeeper) [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=gabrielequatrana_bookkeeper&metric=coverage)](https://sonarcloud.io/dashboard?id=gabrielequatrana_bookkeeper)
Repository progetto: https://github.com/gabrielequatrana/bookkeeper
  
Esecuzione dei test e analisi del coverage tramite Jacoco
```bash
mvn clean verify
```

Esecuzione framework PIT:
```bash
mvn clean verify -P mutation-coverage
```
Report coverage: ```bookkeeper-tests\target\site\jacoco-aggregate```\
Report mutation testing:  ```bookkeeper-server\target\pit-reports```


# Tajo [![Build Status](https://app.travis-ci.com/gabrielequatrana/tajo.svg?branch=master)](https://app.travis-ci.com/gabrielequatrana/tajo) [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=gabrielequatrana_tajo&metric=coverage)](https://sonarcloud.io/dashboard?id=gabrielequatrana_tajo)
Repository progetto: https://github.com/gabrielequatrana/tajo
  
Esecuzione dei test e analisi coverage tramite JaCoCo:
```bash
mvn clean verify
```
Esecuzione framework PIT:
```bash
mvn clean verify -P mutation-coverage
```
Report coverage: ```tajo-tests\target\site\jacoco-aggregate```\
Report mutation testing: ```tajo-core\target\pit-reports```
