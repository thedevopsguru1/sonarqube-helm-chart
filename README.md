# sonarqube
```
helm repo add sonarqube https://SonarSource.github.io/helm-chart-sonarqube
```
```
helm repo update
```
```
helm upgrade --install -n sonarqube sonarqube sonarqube/sonarqube --create-namespace -f values.yaml
```
```
helm upgrade --install -n sonarqube sonarqube sonarqube/sonarqube
```
