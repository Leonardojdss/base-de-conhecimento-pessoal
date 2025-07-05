## Criar arquivo sonar-project.properties
```sh
# Root project information
sonar.projectKey=RAG-new-algorithm
sonar.projectName=RAG-new-algorithm
sonar.projectVersion=1.0

# SonarQube Local configuration
sonar.host.url=http://localhost:9000
sonar.token=inserir_token

# Path to source code
sonar.sources=src

# Path to test files
sonar.tests=tests

# Python-specific properties
sonar.python.coverage.reportPaths=coverage.xml
sonar.language=py
sonar.sourceEncoding=UTF-8

# Exclude files
sonar.exclusions=**/env/**,**/__pycache__/**,**/migrations/**
```
## Executar comando
```bash
sonar-scanner
```
