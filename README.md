# PowerTAC
Part of game theory course: PowerTAC simulator

Generating wholesale strategy for PowerTAC simulator


### For running server

```
cd server
mvn -Pcli -Dexec.args="--sim --boot-data finals_2021_1.xml --weather-data log/finals_2021_1.state --brokers Team13"
```

### For running broker

```
cd brokers
mvn compile
mvn exec:exec
```
