# SonarQube Configuration - TP28

## Token Information
- **Token Name:** TP
- **Project Key:** TP28
- **SonarQube URL:** http://localhost:9000

## Token (Keep this secure!)
```
sqp_cc41bea424f64c4affdbc5914e39c1679b3ca0a5
```
# With Maven
mvn clean verify sonar:sonar \
  -Dsonar.projectKey=TP28 \
  -Dsonar.host.url=http://localhost:9000 \
  -Dsonar.login=sqp_cc41bea424f64c4affdbc5914e39c1679b3ca0a5
